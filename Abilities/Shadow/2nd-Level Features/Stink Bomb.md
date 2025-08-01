<ability>
  <name>Stink Bomb</name>
  <cost>5 Insight</cost>
  <flavor>Putrid yellow gas explodes from a bomb you toss.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Main action</type>
  <distance>3 cube within 10</distance>
  <target>Each creature in the area</target>
  <metadata>
    <class>shadow</class>
    <cost>5 Insight</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Insight</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Shadow/2nd-Level Features</file_dpath>
    <item_id>stink-bomb-5-insight</item_id>
    <item_index>05</item_index>
    <item_name>Stink Bomb (5 Insight)</item_name>
    <level>2</level>
    <scc>mcdm.heroes.v1:feature.ability.shadow.2nd-level-feature:stink-bomb-5-insight</scc>
    <scdc>1.1.1:5.2.3.5:05</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/shadow/2nd-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>2 poison damage</t1>
      <t2>5 poison damage</t2>
      <t3>7 poison damage</t3>
    </effect>
    <effect type="mundane">The gas remains in the area until the end of the encounter. Any creature who starts their turn in the area and has M &lt; AVERAGE is weakened (save ends).</effect>
  </effects>
</ability>
