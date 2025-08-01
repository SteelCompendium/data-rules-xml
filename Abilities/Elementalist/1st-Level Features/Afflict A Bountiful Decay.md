<ability>
  <name>Afflict a Bountiful Decay</name>
  <flavor>Your curse causes your foe&apos;s flesh to rot off as spores that aid your allies.</flavor>
  <keywords>
    <keyword>Green</keyword>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Rot</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>elementalist</class>
    <feature_type>trait</feature_type>
    <file_dpath>Elementalist/1st-Level Features</file_dpath>
    <item_id>afflict-a-bountiful-decay</item_id>
    <item_index>16</item_index>
    <item_name>Afflict a Bountiful Decay</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.elementalist.1st-level-feature:afflict-a-bountiful-decay</scc>
    <scdc>1.1.1:7.1.9.1:16</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/elementalist/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>2 + R corruption damage</t1>
      <t2>4 + R corruption damage</t2>
      <t3>6 + R corruption damage</t3>
    </effect>
    <effect type="mundane">Choose yourself or one ally within distance. That character can end one effect on them that is ended by a saving throw or that ends at the end of their turn.</effect>
  </effects>
</ability>
