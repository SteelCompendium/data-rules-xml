<ability>
  <name>Tough Crowd</name>
  <cost>5 Drama</cost>
  <flavor>Your fans don&apos;t seem to like the opening act …</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Main action</type>
  <distance>3 cube within 10</distance>
  <target>Special</target>
  <metadata>
    <class>troubadour</class>
    <cost>5 Drama</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Drama</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Troubadour/2nd-Level Features</file_dpath>
    <item_id>tough-crowd-5-drama</item_id>
    <item_index>03</item_index>
    <item_name>Tough Crowd (5 Drama)</item_name>
    <level>2</level>
    <scc>mcdm.heroes.v1:feature.ability.troubadour.2nd-level-feature:tough-crowd-5-drama</scc>
    <scdc>1.1.1:13.2.3.5:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/troubadour/2nd-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">The area is haunted by a swirling horde of phantoms until the end of the encounter. Allies can enter any square of the area without spending movement. At the end of each of your turns, you can make one power roll that targets each enemy in the area.</effect>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>5 corruption damage; M &lt; WEAK, pull 1 toward the center of the area</t1>
      <t2>9 corruption damage; M &lt; AVERAGE, pull 2 toward the center of the area</t2>
      <t3>12 corruption damage; M &lt; STRONG, pull 3 toward the center of the area</t3>
    </effect>
  </effects>
</ability>
