<ability>
  <name>Parry</name>
  <flavor>Your quick reflexes cost an enemy the precision they seek.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Triggered</type>
  <distance>Melee 2</distance>
  <target>Self or one ally</target>
  <trigger>A creature deals damage to the target.</trigger>
  <metadata>
    <class>tactician</class>
    <feature_type>trait</feature_type>
    <file_dpath>Tactician/1st-Level Features</file_dpath>
    <item_id>parry</item_id>
    <item_index>01</item_index>
    <item_name>Parry</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.tactician.1st-level-feature:parry</scc>
    <scdc>1.1.1:5.1.3.1:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/tactician/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You can shift 1 square. If the target is you, or if you end this shift adjacent to the target, the target takes half the damage. If the damage has any potency effect associated with it, the potency is decreased by 1.</effect>
    <effect type="mundane" cost="Spend 1 Focus">This ability&apos;s distance becomes Melee 1 + your Reason score, and you can shift up to a number of squares equal to your Reason score instead of 1 square.</effect>
  </effects>
</ability>
