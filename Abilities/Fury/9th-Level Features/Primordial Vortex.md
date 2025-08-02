<ability>
  <name>Primordial Vortex</name>
  <cost>11 Ferocity</cost>
  <flavor>You channel the power of the Primordial Chaos to pull foes to you.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>3 burst</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>fury</class>
    <cost>11 Ferocity</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Ferocity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Fury/9th-Level Features</file_dpath>
    <item_id>primordial-vortex-11-ferocity</item_id>
    <item_index>06</item_index>
    <item_name>Primordial Vortex (11 Ferocity)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.fury.9th-level-feature:primordial-vortex-11-ferocity</scc>
    <scdc>1.1.1:14.2.5.6:06</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/fury/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>3 damage; vertical pull 3</t1>
      <t2>5 damage; vertical pull 5</t2>
      <t3>8 damage; vertical pull 7</t3>
    </effect>
    <effect type="mundane">If this forced movement causes a target to slam into you, you take no damage from the collision and the target takes the damage you would have taken.</effect>
  </effects>
</ability>
