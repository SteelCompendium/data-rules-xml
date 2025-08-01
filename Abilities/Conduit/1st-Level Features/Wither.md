<ability>
  <name>Wither</name>
  <flavor>A bolt of holy energy saps the life from a foe.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature or object</target>
  <metadata>
    <class>conduit</class>
    <feature_type>trait</feature_type>
    <file_dpath>Conduit/1st-Level Features</file_dpath>
    <item_id>wither</item_id>
    <item_index>12</item_index>
    <item_name>Wither</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.conduit.1st-level-feature:wither</scc>
    <scdc>1.1.1:10.1.8.1:12</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/conduit/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>3 + I corruption damage; P &lt; WEAK, the target takes a bane on their next power roll</t1>
      <t2>5 + I corruption damage; P &lt; AVERAGE, the target takes a bane on their next power roll</t2>
      <t3>8 + I corruption damage; P &lt; STRONG, the target takes a bane on their next power roll</t3>
    </effect>
  </effects>
</ability>
