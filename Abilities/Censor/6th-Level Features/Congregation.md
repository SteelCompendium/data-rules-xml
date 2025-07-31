<ability>
  <name>Congregation</name>
  <cost>9 Wrath</cost>
  <flavor>You focus your allies&apos; wrath on a chosen foe.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <metadata>
    <class>censor</class>
    <cost>9 Wrath</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Wrath</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Censor/6th-Level Features</file_dpath>
    <item_id>congregation-9-wrath</item_id>
    <item_index>05</item_index>
    <item_name>Congregation (9 Wrath)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.censor.6th-level-feature:congregation-9-wrath</scc>
    <scdc>1.1.1:5.2.2.3:05</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/censor/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>8 + M damage; as a free triggered action, one ally within 10 squares of the target can use a strike signature ability against the target</t1>
      <t2>12 + M damage; as a free triggered action, one ally within 10 squares of the target can use a strike signature ability that gains an edge against the target</t2>
      <t3>16 + M damage; as a free triggered action, two allies within 10 squares of the target can each use a strike signature ability that gains an edge against the target</t3>
    </effect>
    <effect type="mundane">Each ally can shift up to 2 squares and gains 2 surges before making the strike.</effect>
  </effects>
</ability>
