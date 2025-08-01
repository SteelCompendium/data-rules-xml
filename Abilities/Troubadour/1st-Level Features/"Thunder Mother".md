<ability>
  <name>&quot;Thunder Mother&quot;</name>
  <flavor>All for thunder motherrr! ♪ Run and hide for coverrr!♪</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Performance</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>No action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>troubadour</class>
    <feature_type>trait</feature_type>
    <file_dpath>Troubadour/1st-Level Features</file_dpath>
    <item_id>thunder-mother</item_id>
    <item_index>01</item_index>
    <item_name>&quot;Thunder Mother&quot;</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.troubadour.1st-level-feature:thunder-mother</scc>
    <scdc>1.1.1:13.1.3.1:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/troubadour/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">At the end of each combat round while this performance is active, you can make a power roll against the target that ignores cover. You can&apos;t target the same creature twice with this effect.</effect>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>Lightning damage equal to your level</t1>
      <t2>Lightning damage equal to 5 + your level</t2>
      <t3>Lightning damage equal to 10 + your level</t3>
    </effect>
  </effects>
</ability>
