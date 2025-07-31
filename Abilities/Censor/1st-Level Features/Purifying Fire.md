<ability>
  <name>Purifying Fire</name>
  <cost>5 Wrath</cost>
  <flavor>The gods judge, fire cleanses.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>Melee 1 or ranged 5</distance>
  <target>One creature</target>
  <metadata>
    <class>censor</class>
    <cost>5 Wrath</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Wrath</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Censor/1st-Level Features</file_dpath>
    <item_id>purifying-fire-5-wrath</item_id>
    <item_index>06</item_index>
    <item_name>Purifying Fire (5 Wrath)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.censor.1st-level-feature:purifying-fire-5-wrath</scc>
    <scdc>1.1.1:5.2.7.1:06</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/censor/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>5 + M holy damage; M &lt; WEAK, the target has fire weakness 3 (save ends)</t1>
      <t2>9 + M holy damage; M &lt; AVERAGE, the target has fire weakness 5 (save ends)</t2>
      <t3>12 + M holy damage; M &lt; STRONG, the target has fire weakness 7 (save ends)</t3>
    </effect>
    <effect type="mundane">While the target has fire weakness from this ability, you can choose to have your abilities deal fire damage to the target instead of holy damage.</effect>
  </effects>
</ability>
