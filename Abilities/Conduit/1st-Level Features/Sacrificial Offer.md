<ability>
  <name>Sacrificial Offer</name>
  <flavor>Divine magic tears at your foe and defends a nearby friend.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>conduit</class>
    <feature_type>trait</feature_type>
    <file_dpath>Conduit/1st-Level Features</file_dpath>
    <item_id>sacrificial-offer</item_id>
    <item_index>05</item_index>
    <item_name>Sacrificial Offer</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.conduit.1st-level-feature:sacrificial-offer</scc>
    <scdc>1.1.1:5.1.7.1:05</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/conduit/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>2 + I corruption damage</t1>
      <t2>4 + I corruption damage</t2>
      <t3>6 + I corruption damage</t3>
    </effect>
    <effect type="mundane">Choose yourself or one ally within distance. That character can impose a bane on one power roll made against them before the end of their next turn.</effect>
  </effects>
</ability>
