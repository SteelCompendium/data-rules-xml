<ability>
  <name>Impaled!</name>
  <flavor>You skewer your enemy like a boar upon a spit.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature of your size or smaller</target>
  <metadata>
    <class>fury</class>
    <feature_type>trait</feature_type>
    <file_dpath>Fury/1st-Level Features</file_dpath>
    <item_id>impaled</item_id>
    <item_index>04</item_index>
    <item_name>Impaled!</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.fury.1st-level-feature:impaled</scc>
    <scdc>1.1.1:5.1.5.1:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/fury/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>2 + M damage; M &lt; WEAK, grabbed</t1>
      <t2>5 + M damage; M &lt; AVERAGE, grabbed</t2>
      <t3>7 + M damage; M &lt; STRONG, grabbed</t3>
    </effect>
  </effects>
</ability>
