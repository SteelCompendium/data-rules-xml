<ability>
  <name>Panic in Their Lines</name>
  <cost>9 Focus</cost>
  <flavor>You confuse your foes, causing them to turn on each other.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1 or ranged 5</distance>
  <target>Two creatures</target>
  <metadata>
    <class>tactician</class>
    <cost>9 Focus</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Focus</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Tactician/6th-Level Features</file_dpath>
    <item_id>panic-in-their-lines-9-focus</item_id>
    <item_index>04</item_index>
    <item_name>Panic in Their Lines (9 Focus)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.tactician.6th-level-feature:panic-in-their-lines-9-focus</scc>
    <scdc>1.1.1:10.2.4.3:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/tactician/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>6 + M damage; slide 1</t1>
      <t2>9 + M damage; slide 3</t2>
      <t3>13 + M damage; slide 5</t3>
    </effect>
    <effect type="mundane">If a target is force moved into another creature, they must make a free strike against that creature.</effect>
  </effects>
</ability>
