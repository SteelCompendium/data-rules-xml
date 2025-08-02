<ability>
  <name>Every Step … Death!</name>
  <flavor>You show your foe a glimpse of their fate after death. Magic, Ranged, Strike Main action</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>censor</class>
    <feature_type>trait</feature_type>
    <file_dpath>Censor/1st-Level Features</file_dpath>
    <item_id>every-step-death</item_id>
    <item_index>9</item_index>
    <item_name>Every Step … Death!</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.censor.1st-level-feature:every-step-death</scc>
    <scdc>1.1.1:14.1.7.1:09</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/censor/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>5 + P psychic damage</t1>
      <t2>7 + P psychic damage</t2>
      <t3>10 + P psychic damage</t3>
    </effect>
    <effect type="mundane">Each time the target willingly moves before the end of your next turn, they take 1 psychic damage for each square they move.</effect>
  </effects>
</ability>
