<ability>
  <name>Relentless Death</name>
  <cost>11 Ferocity</cost>
  <flavor>You won&apos;t escape your fate.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Self; see below</distance>
  <target>Self</target>
  <metadata>
    <class>fury</class>
    <cost>11 Ferocity</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Ferocity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Fury/8th-Level Features</file_dpath>
    <item_id>relentless-death-11-ferocity</item_id>
    <item_index>01</item_index>
    <item_name>Relentless Death (11 Ferocity)</item_name>
    <level>8</level>
    <scc>mcdm.heroes.v1:feature.ability.fury.8th-level-feature:relentless-death-11-ferocity</scc>
    <scdc>1.1.1:7.2.5.2:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/fury/8th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You shift up to your speed. Each enemy you move adjacent to during this movement takes damage equal to twice your Might score. Then make one power roll that targets each enemy you move adjacent to during this shift. You gain 1 ferocity for each target who dies as a result of this ability (maximum 11 ferocity).</effect>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>Any target whose Stamina is equal to or less than 8 dies.</t1>
      <t2>Any target whose Stamina is equal to or less than 11 dies.</t2>
      <t3>Any target whose Stamina is equal to or less than 17 dies.</t3>
    </effect>
  </effects>
</ability>
