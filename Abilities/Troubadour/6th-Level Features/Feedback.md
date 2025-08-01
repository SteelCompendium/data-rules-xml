<ability>
  <name>Feedback</name>
  <cost>9 Drama</cost>
  <flavor>Your music pounds the crowd to the beat until their hearts can&apos;t stand it anymore.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Magic</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Three 3 cubes within 1</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>troubadour</class>
    <cost>9 Drama</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Drama</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Troubadour/6th-Level Features</file_dpath>
    <item_id>feedback-9-drama</item_id>
    <item_index>01</item_index>
    <item_name>Feedback (9 Drama)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.troubadour.6th-level-feature:feedback-9-drama</scc>
    <scdc>1.1.1:9.2.3.3:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/troubadour/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">A prone target ignores this ability.</effect>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>7 sonic damage; P &lt; WEAK, prone</t1>
      <t2>10 sonic damage; P &lt; AVERAGE, prone</t2>
      <t3>13 sonic damage; P &lt; STRONG, prone</t3>
    </effect>
  </effects>
</ability>
