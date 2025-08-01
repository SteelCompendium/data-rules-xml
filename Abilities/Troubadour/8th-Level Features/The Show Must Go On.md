<ability>
  <name>The Show Must Go On</name>
  <cost>11 Drama</cost>
  <flavor>You shine a bright light on the players on the stage and compel them to finish the performance.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Maneuver</type>
  <distance>5 cube within 10</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>troubadour</class>
    <cost>11 Drama</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Drama</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Troubadour/8th-Level Features</file_dpath>
    <item_id>the-show-must-go-on-11-drama</item_id>
    <item_index>02</item_index>
    <item_name>The Show Must Go On (11 Drama)</item_name>
    <level>8</level>
    <scc>mcdm.heroes.v1:feature.ability.troubadour.8th-level-feature:the-show-must-go-on-11-drama</scc>
    <scdc>1.1.1:5.2.3.2:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/troubadour/8th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>6 damage; P &lt; WEAK, the target can&apos;t willingly leave the area (EoT)</t1>
      <t2>8 damage; P &lt; AVERAGE, the target can&apos;t willingly leave the area (save ends)</t2>
      <t3>12 damage; the target can&apos;t willingly leave the area (EoT); if P &lt; STRONG, they can&apos;t willingly leave the area (save ends)</t3>
    </effect>
    <effect type="mundane">Each ally within distance can&apos;t obtain lower than a tier 2 outcome on the next test they make before the start of your next turn.</effect>
  </effects>
</ability>
