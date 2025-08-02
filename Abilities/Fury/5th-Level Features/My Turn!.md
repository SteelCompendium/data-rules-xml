<ability>
  <name>My Turn!</name>
  <cost>9 Ferocity</cost>
  <flavor>You quickly strike back at a foe.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Free triggered</type>
  <distance>Melee 1</distance>
  <target>The triggering creature</target>
  <trigger>A creature causes you to be winded or dying, or damages you while you are winded or dying.</trigger>
  <metadata>
    <class>fury</class>
    <cost>9 Ferocity</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Ferocity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Fury/5th-Level Features</file_dpath>
    <item_id>my-turn-9-ferocity</item_id>
    <item_index>03</item_index>
    <item_name>My Turn! (9 Ferocity)</item_name>
    <level>5</level>
    <scc>mcdm.heroes.v1:feature.ability.fury.5th-level-feature:my-turn-9-ferocity</scc>
    <scdc>1.1.1:14.2.5.4:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/fury/5th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>6 + M damage</t1>
      <t2>9 + M damage</t2>
      <t3>13 + M damage</t3>
    </effect>
    <effect type="mundane">You can spend a Recovery.</effect>
  </effects>
</ability>
