<ability>
  <name>Gravitic Well</name>
  <cost>9 Clarity</cost>
  <flavor>You bend gravity into a fine point and pull your foes toward it.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Telekinesis</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>4 cube within 10</distance>
  <target>Each creature and object in the area</target>
  <metadata>
    <class>talent</class>
    <cost>9 Clarity</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/6th-Level Features</file_dpath>
    <item_id>gravitic-well-9-clarity</item_id>
    <item_index>07</item_index>
    <item_name>Gravitic Well (9 Clarity)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.6th-level-feature:gravitic-well-9-clarity</scc>
    <scdc>1.1.1:6.2.1.3:07</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>6 damage; vertical pull 5 toward the center of the area</t1>
      <t2>9 damage; vertical pull 7 toward the center of the area</t2>
      <t3>13 damage; vertical pull 10 toward the center of the area</t3>
    </effect>
    <effect type="mundane">Targets closest to the center of the area are pulled first.</effect>
    <effect type="mundane" name="Strained">The size of the area increases by 2. You also target yourself and each ally within distance.</effect>
  </effects>
</ability>
