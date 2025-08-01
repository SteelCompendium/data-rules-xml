<ability>
  <name>Pillar of Holy Fire</name>
  <cost>11 Wrath</cost>
  <flavor>Your enemy&apos;s guilt fuels a holy flame that burns your foes.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <metadata>
    <class>censor</class>
    <cost>11 Wrath</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Wrath</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Censor/8th-Level Features</file_dpath>
    <item_id>pillar-of-holy-fire-11-wrath</item_id>
    <item_index>03</item_index>
    <item_name>Pillar of Holy Fire (11 Wrath)</item_name>
    <level>8</level>
    <scc>mcdm.heroes.v1:feature.ability.censor.8th-level-feature:pillar-of-holy-fire-11-wrath</scc>
    <scdc>1.1.1:6.2.7.2:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/censor/8th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>9 + M damage; I &lt; WEAK, dazed (save ends)</t1>
      <t2>13 + M damage; I &lt; AVERAGE, dazed (save ends)</t2>
      <t3>18 + M damage; I &lt; STRONG, dazed (save ends)</t3>
    </effect>
    <effect type="mundane">At the end of each of your turns, a target dazed this way deals holy damage equal to twice your Presence score to each enemy within 2 squares of them.</effect>
  </effects>
</ability>
