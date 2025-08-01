<ability>
  <name>Morning Light</name>
  <cost>5 Piety</cost>
  <flavor>Light shines at your command, burning your foes and blessing your</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Magic</keyword>
  </keywords>
  <type>Main action</type>
  <distance>3 burst</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>conduit</class>
    <cost>5 Piety</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Piety</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Conduit/2nd-Level Features</file_dpath>
    <item_id>morning-light-5-piety</item_id>
    <item_index>9</item_index>
    <item_name>Morning Light (5 Piety)</item_name>
    <level>2</level>
    <scc>mcdm.heroes.v1:feature.ability.conduit.2nd-level-feature:morning-light-5-piety</scc>
    <scdc>1.1.1:5.2.8.5:09</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/conduit/2nd-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>4 fire damage</t1>
      <t2>6 fire damage</t2>
      <t3>10 fire damage</t3>
    </effect>
    <effect type="mundane">Each ally in the area deals fire damage equal to your Intuition score with their next strike made before the end of their next turn.</effect>
  </effects>
</ability>
