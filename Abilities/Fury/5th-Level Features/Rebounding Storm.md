<ability>
  <name>Rebounding Storm</name>
  <cost>9 Ferocity</cost>
  <flavor>You knock around enemies like playthings.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>Two creatures or objects</target>
  <metadata>
    <class>fury</class>
    <cost>9 Ferocity</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Ferocity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Fury/5th-Level Features</file_dpath>
    <item_id>rebounding-storm-9-ferocity</item_id>
    <item_index>04</item_index>
    <item_name>Rebounding Storm (9 Ferocity)</item_name>
    <level>5</level>
    <scc>mcdm.heroes.v1:feature.ability.fury.5th-level-feature:rebounding-storm-9-ferocity</scc>
    <scdc>1.1.1:5.2.4.4:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/fury/5th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>9 damage; push 3</t1>
      <t2>14 damage; push 5</t2>
      <t3>19 damage; push 7</t3>
    </effect>
    <effect type="mundane">When a target would end this forced movement by colliding with a creature or object, they take damage as usual, then are pushed the remaining distance away from the creature or object in the direction they came from. As long as forced movement remains, this effect continues if the target collides with another creature or object.</effect>
  </effects>
</ability>
