<ability>
  <name>Call the Thunder Down</name>
  <cost>3 Piety</cost>
  <flavor>You ask your saint for thunder and your prayer is answered.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Magic</keyword>
    <keyword>Range</keyword>
  </keywords>
  <type>Main action</type>
  <distance>3 cube within 10</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>conduit</class>
    <cost>3 Piety</cost>
    <cost_amount>3</cost_amount>
    <cost_resource>Piety</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Conduit/1st-Level Features</file_dpath>
    <item_id>call-the-thunder-down-3-piety</item_id>
    <item_index>04</item_index>
    <item_name>Call the Thunder Down (3 Piety)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.conduit.1st-level-feature:call-the-thunder-down-3-piety</scc>
    <scdc>1.1.1:8.2.8.1:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/conduit/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>2 sonic damage; push 1</t1>
      <t2>3 sonic damage; push 2</t2>
      <t3>5 sonic damage; push 3</t3>
    </effect>
    <effect type="mundane">You can push each willing ally in the area the same distance, ignoring stability.</effect>
  </effects>
</ability>
