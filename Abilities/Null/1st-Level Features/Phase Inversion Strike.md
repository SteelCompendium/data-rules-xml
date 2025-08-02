<ability>
  <name>Phase Inversion Strike</name>
  <flavor>You step momentarily out of phase as you pull an enemy through you.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Psionic</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature or object</target>
  <metadata>
    <class>null</class>
    <feature_type>trait</feature_type>
    <file_dpath>Null/1st-Level Features</file_dpath>
    <item_id>phase-inversion-strike</item_id>
    <item_index>8</item_index>
    <item_name>Phase Inversion Strike</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.null.1st-level-feature:phase-inversion-strike</scc>
    <scdc>1.1.1:14.1.6.1:08</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/null/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>\\4 + A damage; push 2</t1>
      <t2>6 + A damage; push 4</t2>
      <t3>8 + A damage; push 6</t3>
    </effect>
    <effect type="mundane">Before the push is resolved, you teleport the target to a square adjacent to you and opposite the one they started in. If the target can&apos;t be teleported this way, you can&apos;t push them.</effect>
  </effects>
</ability>
