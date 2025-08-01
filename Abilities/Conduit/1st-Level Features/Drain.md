<ability>
  <name>Drain</name>
  <flavor>You drain the energy from your target to revitalize yourself or an ally.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <metadata>
    <class>conduit</class>
    <feature_type>trait</feature_type>
    <file_dpath>Conduit/1st-Level Features</file_dpath>
    <item_id>drain</item_id>
    <item_index>33</item_index>
    <item_name>Drain</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.conduit.1st-level-feature:drain</scc>
    <scdc>1.1.1:6.1.8.1:33</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/conduit/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>2 + I corruption damage</t1>
      <t2>5 + I corruption damage</t2>
      <t3>7 + I corruption damage</t3>
    </effect>
    <effect type="mundane">You or one ally within distance can spend a Recovery.</effect>
  </effects>
</ability>
