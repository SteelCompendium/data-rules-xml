<ability>
  <name>Phase Hurl</name>
  <cost>11 Discipline</cost>
  <flavor>You throw your foe out of phase with this manifold, causing them to harm other enemies as they return.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Psionic</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <metadata>
    <class>null</class>
    <cost>11 Discipline</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Discipline</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Null/8th-Level Features</file_dpath>
    <item_id>phase-hurl-11-discipline</item_id>
    <item_index>03</item_index>
    <item_name>Phase Hurl (11 Discipline)</item_name>
    <level>8</level>
    <scc>mcdm.heroes.v1:feature.ability.null.8th-level-feature:phase-hurl-11-discipline</scc>
    <scdc>1.1.1:14.2.6.2:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/null/8th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>9 + A damage; push 5; I &lt; WEAK, dazed (save ends)</t1>
      <t2>13 + A damage; push 7; I &lt; AVERAGE, dazed (save ends)</t2>
      <t3>18 + A damage; push 10; I &lt; STRONG, dazed (save ends)</t3>
    </effect>
    <effect type="mundane">The target and each creature or object they collide with from this forced movement takes psychic damage equal to the total number of squares the target was force moved. While the target is dazed this way, they see glimpses of creatures from other parts of the timescape.</effect>
  </effects>
</ability>
