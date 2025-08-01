<ability>
  <name>Force of Storms</name>
  <cost>9 Ferocity</cost>
  <flavor>You strike an enemy hard enough to be a projectile that knocks a crowd of creatures around.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <metadata>
    <class>fury</class>
    <cost>9 Ferocity</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Ferocity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Fury/6th-Level Features</file_dpath>
    <item_id>force-of-storms-9-ferocity</item_id>
    <item_index>01</item_index>
    <item_name>Force of Storms (9 Ferocity)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.fury.6th-level-feature:force-of-storms-9-ferocity</scc>
    <scdc>1.1.1:5.1.3.3:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/fury/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>7 + M damage; push 3</t1>
      <t2>11 + M damage; push 5</t2>
      <t3>16 + M damage; push 7</t3>
    </effect>
    <effect type="mundane">When the target ends this forced movement, each creature within 2 squares of the target is pushed 3 squares.</effect>
  </effects>
</ability>
