<ability>
  <name>Sentenced</name>
  <cost>5 Wrath</cost>
  <flavor>The shock of your condemnation freezes your enemy in their boots.</flavor>
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
    <file_dpath>Censor/2nd-Level Features</file_dpath>
    <item_id>sentenced-5-wrath</item_id>
    <item_index>02</item_index>
    <item_name>Sentenced (5 Wrath)</item_name>
    <level>2</level>
    <scc>mcdm.heroes.v1:feature.ability.censor.2nd-level-feature:sentenced-5-wrath</scc>
    <scdc>1.1.1:5.1.1.5:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/censor/2nd-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>5 + P damage; P &lt; WEAK, restrained (save ends)</t1>
      <t2>9 + P damage; P &lt; AVERAGE, restrained (save ends)</t2>
      <t3>12 + P damage; P &lt; STRONG, restrained (save ends)</t3>
    </effect>
    <effect type="mundane">While the target is restrained this way, your abilities that impose forced movement can still move them.</effect>
  </effects>
</ability>
