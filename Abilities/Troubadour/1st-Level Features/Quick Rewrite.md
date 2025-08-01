<ability>
  <name>Quick Rewrite</name>
  <cost>3 Drama</cost>
  <flavor>You write something unexpected into the scene that hinders your enemy.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>3 cube within 10</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>troubadour</class>
    <cost>3 Drama</cost>
    <cost_amount>3</cost_amount>
    <cost_resource>Drama</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Troubadour/1st-Level Features</file_dpath>
    <item_id>quick-rewrite-3-drama</item_id>
    <item_index>01</item_index>
    <item_name>Quick Rewrite (3 Drama)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.troubadour.1st-level-feature:quick-rewrite-3-drama</scc>
    <scdc>1.1.1:13.2.3.1:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/troubadour/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>4 damage; P &lt; WEAK, slowed (save ends)</t1>
      <t2>5 damage; P &lt; AVERAGE, slowed (save ends)</t2>
      <t3>6 damage; P &lt; STRONG, restrained (save ends)</t3>
    </effect>
    <effect type="mundane">The area is difficult terrain for enemies.</effect>
  </effects>
</ability>
