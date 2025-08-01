<ability>
  <name>Hit and Run</name>
  <flavor>Staying in constant motion helps you slip out of reach after a brutal assault.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature or object</target>
  <metadata>
    <class>fury</class>
    <feature_type>trait</feature_type>
    <file_dpath>Fury/1st-Level Features</file_dpath>
    <item_id>hit-and-run</item_id>
    <item_index>8</item_index>
    <item_name>Hit and Run</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.fury.1st-level-feature:hit-and-run</scc>
    <scdc>1.1.1:5.1.4.1:08</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/fury/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>2 + M damage</t1>
      <t2>5 + M damage</t2>
      <t3>7 + M damage; A &lt; STRONG, slowed (save ends)</t3>
    </effect>
    <effect type="mundane">You can shift 1 square.</effect>
  </effects>
</ability>
