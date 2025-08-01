<ability>
  <name>Advanced Tactics</name>
  <flavor>Your leadership aids an ally.</flavor>
  <keywords>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Triggered</type>
  <distance>Ranged 10</distance>
  <target>One ally</target>
  <trigger>The target deals damage to another creature.</trigger>
  <metadata>
    <class>tactician</class>
    <feature_type>trait</feature_type>
    <file_dpath>Tactician/1st-Level Features</file_dpath>
    <item_id>advanced-tactics</item_id>
    <item_index>04</item_index>
    <item_name>Advanced Tactics</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.tactician.1st-level-feature:advanced-tactics</scc>
    <scdc>1.1.1:9.1.4.1:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/tactician/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">The target gains 2 surges, which they can use on the triggering damage.</effect>
    <effect type="mundane" cost="Spend 1 Focus">If the damage has any potency effect associated with it, the potency is increased by 1.</effect>
  </effects>
</ability>
