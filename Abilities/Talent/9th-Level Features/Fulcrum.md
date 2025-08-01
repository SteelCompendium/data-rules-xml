<ability>
  <name>Fulcrum</name>
  <cost>11 Clarity</cost>
  <flavor>You precisely manipulate the creatures around you.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Psionic</keyword>
    <keyword>Telekinesis</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Special</distance>
  <target>Each enemy and object in the area</target>
  <metadata>
    <class>talent</class>
    <cost>11 Clarity</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/9th-Level Features</file_dpath>
    <item_id>fulcrum-11-clarity</item_id>
    <item_index>03</item_index>
    <item_name>Fulcrum (11 Clarity)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.9th-level-feature:fulcrum-11-clarity</scc>
    <scdc>1.1.1:10.2.1.7:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">Make a power roll to determine the area of this ability. Each target is vertical pushed 6 squares. You can target only objects of size 1L or smaller.</effect>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>2 burst</t1>
      <t2>3 burst</t2>
      <t3>4 burst</t3>
    </effect>
    <effect type="mundane" name="Strained">You can choose to reduce the size of the burst by 2 (to a minimum of 1 burst) to give the forced movement distance a +2 bonus. You take half the total damage all targets take from forced movement.</effect>
  </effects>
</ability>
