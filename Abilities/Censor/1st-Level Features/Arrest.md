<ability>
  <name>Arrest</name>
  <cost>5 Wrath</cost>
  <flavor>“I got you, you son of a bitch.”</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <metadata>
    <class>censor</class>
    <cost>5 Wrath</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Wrath</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Censor/1st-Level Features</file_dpath>
    <item_id>arrest-5-wrath</item_id>
    <item_index>03</item_index>
    <item_name>Arrest (5 Wrath)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.censor.1st-level-feature:arrest-5-wrath</scc>
    <scdc>1.1.1:10.2.7.1:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/censor/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>6 + M holy damage; grabbed</t1>
      <t2>9 + M holy damage; grabbed</t2>
      <t3>13 + M holy damage; grabbed</t3>
    </effect>
    <effect type="mundane">If the target makes a strike against a creature while grabbed this way, you can spend 3 wrath to deal holy damage to them equal to your Presence score, then change the target of the strike to another target within the strike&apos;s distance.</effect>
  </effects>
</ability>
