<ability>
  <name>Epic</name>
  <cost>11 Drama</cost>
  <flavor>Your story tells a tale of the villain&apos;s waning power and how the heroes rose to the occasion to stop them.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Maneuver</type>
  <distance>Melee 1 or ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>troubadour</class>
    <cost>11 Drama</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Drama</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Troubadour/9th-Level Features</file_dpath>
    <item_id>epic-11-drama</item_id>
    <item_index>05</item_index>
    <item_name>Epic (11 Drama)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.troubadour.9th-level-feature:epic-11-drama</scc>
    <scdc>1.1.1:6.2.3.7:05</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/troubadour/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>The target takes a bane on ability rolls (save ends).</t1>
      <t2>The target has a double bane on ability rolls (save ends).</t2>
      <t3>The target has a double bane on power rolls (save ends).</t3>
    </effect>
    <effect type="mundane">Choose one ally within distance. While the target is affected by this ability, each time they use an ability, that ally can make a free strike against them after the ability is resolved.</effect>
  </effects>
</ability>
