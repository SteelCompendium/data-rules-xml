<ability>
  <name>No Dying on My Watch</name>
  <cost>5 Focus</cost>
  <flavor>You prioritize saving an ally over your own safety.</flavor>
  <keywords>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Triggered</type>
  <distance>Ranged 5</distance>
  <target>One enemy</target>
  <trigger>The target deals damage to an ally.</trigger>
  <metadata>
    <class>tactician</class>
    <cost>5 Focus</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Focus</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Tactician/2nd-Level Features</file_dpath>
    <item_id>no-dying-on-my-watch-5-focus</item_id>
    <item_index>03</item_index>
    <item_name>No Dying on My Watch (5 Focus)</item_name>
    <level>2</level>
    <scc>mcdm.heroes.v1:feature.ability.tactician.2nd-level-feature:no-dying-on-my-watch-5-focus</scc>
    <scdc>1.1.1:6.2.4.5:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/tactician/2nd-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You move up to your speed toward the triggering ally, ending this movement adjacent to them or in the nearest square if you can&apos;t reach an adjacent square. The triggering ally can spend a Recovery and gains 5 temporary Stamina for each enemy you came adjacent to during the move. You then make a power roll against the target.</effect>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>R &lt; WEAK, the target is frightened of the triggering ally (save ends)</t1>
      <t2>R &lt; AVERAGE, the target is frightened of the triggering ally (save ends)</t2>
      <t3>R &lt; STRONG, the target is frightened of the triggering ally (save ends)</t3>
    </effect>
  </effects>
</ability>
