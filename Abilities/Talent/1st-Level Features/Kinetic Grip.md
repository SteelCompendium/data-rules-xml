<ability>
  <name>Kinetic Grip</name>
  <flavor>You lift and hurl your foe away from you.</flavor>
  <keywords>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Telekinesis</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature or object</target>
  <metadata>
    <class>talent</class>
    <feature_type>trait</feature_type>
    <file_dpath>Talent/1st-Level Features</file_dpath>
    <item_id>kinetic-grip</item_id>
    <item_index>02</item_index>
    <item_name>Kinetic Grip</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.talent.1st-level-feature:kinetic-grip</scc>
    <scdc>1.1.1:9.1.1.1:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/talent/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>Slide 2 + R</t1>
      <t2>Slide 4 + R</t2>
      <t3>Slide 6 + R; prone</t3>
    </effect>
    <effect type="mundane" name="Strained">You must vertical push the target instead of sliding them.</effect>
  </effects>
</ability>
