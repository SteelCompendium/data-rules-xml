<ability>
  <name>Mind Game</name>
  <cost>5 Focus</cost>
  <flavor>Your attack demoralizes your foe. Your allies begin to think you can win.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1 or ranged 5</distance>
  <target>One creature or object</target>
  <metadata>
    <class>tactician</class>
    <cost>5 Focus</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Focus</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Tactician/1st-Level Features</file_dpath>
    <item_id>mind-game-5-focus</item_id>
    <item_index>8</item_index>
    <item_name>Mind Game (5 Focus)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.tactician.1st-level-feature:mind-game-5-focus</scc>
    <scdc>1.1.1:13.2.4.1:08</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/tactician/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You mark the target.</effect>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>4\\+\\ M damage; R &lt; WEAK, weakened (save ends)</t1>
      <t2>6 + M damage; R &lt; AVERAGE, weakened (save ends)</t2>
      <t3>10\\+\\ M damage; R &lt; STRONG, weakened (save ends)</t3>
    </effect>
    <effect type="mundane">Before the start of your next turn, the first time any ally deals damage to any target marked by you, that ally can spend a Recovery.</effect>
  </effects>
</ability>
