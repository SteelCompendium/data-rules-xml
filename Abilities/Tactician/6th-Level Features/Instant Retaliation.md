<ability>
  <name>Instant Retaliation</name>
  <cost>9 Focus</cost>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Free triggered</type>
  <distance>Melee 1</distance>
  <target>One ally</target>
  <trigger>A creature deals damage to the target.</trigger>
  <metadata>
    <class>tactician</class>
    <cost>9 Focus</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Focus</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Tactician/6th-Level Features</file_dpath>
    <item_id>instant-retaliation-9-focus</item_id>
    <item_index>05</item_index>
    <item_name>Instant Retaliation (9 Focus)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.tactician.6th-level-feature:instant-retaliation-9-focus</scc>
    <scdc>1.1.1:6.2.4.3:05</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/tactician/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">The target takes half the damage. You then make a power roll against the triggering creature.</effect>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>A &lt; WEAK, dazed (save ends)</t1>
      <t2>A &lt; AVERAGE, dazed (save ends)</t2>
      <t3>A &lt; STRONG, dazed (save ends)</t3>
    </effect>
  </effects>
</ability>
