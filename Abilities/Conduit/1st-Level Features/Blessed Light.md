<ability>
  <name>Blessed Light</name>
  <flavor>Burning radiance falls upon your foe, transferring some of their energy to a nearby ally.</flavor>
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
    <item_id>blessed-light</item_id>
    <item_index>11</item_index>
    <item_name>Blessed Light</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.conduit.1st-level-feature:blessed-light</scc>
    <scdc>1.1.1:13.1.8.1:11</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/conduit/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>3 + I holy damage</t1>
      <t3>8 + I holy damage</t3>
    </effect>
    <effect type="mundane">One ally within distance gains a number of surges equal to the tier outcome of your power roll.</effect>
  </effects>
</ability>
