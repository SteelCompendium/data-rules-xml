<ability>
  <name>Halt Miscreant!</name>
  <flavor>You infuse your weapon with holy magic that makes it difficult for your foe to get away.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>Melee 1</distance>
  <target>One creature or object</target>
  <metadata>
    <class>censor</class>
    <feature_type>trait</feature_type>
    <file_dpath>Censor/1st-Level Features</file_dpath>
    <item_id>halt-miscreant</item_id>
    <item_index>04</item_index>
    <item_name>Halt Miscreant!</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.censor.1st-level-feature:halt-miscreant</scc>
    <scdc>1.1.1:7.1.7.1:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/censor/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>2 + M holy damage; P &lt; WEAK, slowed (save ends)</t1>
      <t2>5 + M holy damage; P &lt; AVERAGE, slowed (save ends)</t2>
      <t3>7 + M holy damage; P &lt; STRONG, slowed (save ends)</t3>
    </effect>
  </effects>
</ability>
