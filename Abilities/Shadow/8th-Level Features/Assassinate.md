<ability>
  <name>Assassinate</name>
  <cost>11 Insight</cost>
  <flavor>A practiced attack will instantly kill an already weakened foe.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature or object</target>
  <metadata>
    <class>shadow</class>
    <cost>11 Insight</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Insight</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Shadow/8th-Level Features</file_dpath>
    <item_id>assassinate-11-insight</item_id>
    <item_index>03</item_index>
    <item_name>Assassinate (11 Insight)</item_name>
    <level>8</level>
    <scc>mcdm.heroes.v1:feature.ability.shadow.8th-level-feature:assassinate-11-insight</scc>
    <scdc>1.1.1:9.2.2.2:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/shadow/8th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>12 + A damage</t1>
      <t2>18 + A damage</t2>
      <t3>24 + A damage</t3>
    </effect>
    <effect type="mundane">A target who is not a minion, leader, or solo creature and who is winded after taking this damage is reduced to 0 Stamina.</effect>
  </effects>
</ability>
