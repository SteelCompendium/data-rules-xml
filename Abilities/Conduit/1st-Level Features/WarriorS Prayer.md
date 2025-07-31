<ability>
  <name>Warrior&apos;s Prayer</name>
  <flavor>Your quickly uttered prayer lends aggressive divine energy to a friend engaged in melee.</flavor>
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
    <item_id>warriors-prayer</item_id>
    <item_index>30</item_index>
    <item_name>Warrior&apos;s Prayer</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.conduit.1st-level-feature:warriors-prayer</scc>
    <scdc>1.1.1:5.1.12.1:30</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/conduit/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>3 + I holy damage</t1>
      <t2>6 + I holy damage</t2>
      <t3>9 + I holy damage</t3>
    </effect>
    <effect type="mundane">You or one ally within distance gains temporary Stamina equal to your Intuition score.</effect>
  </effects>
</ability>
