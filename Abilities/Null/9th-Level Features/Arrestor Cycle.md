<ability>
  <name>Arrestor Cycle</name>
  <cost>11 Discipline</cost>
  <flavor>You trap your foe in a looping cycle of time, where they relive the last few seconds over and over again.</flavor>
  <keywords>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Free triggered</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <trigger>The triggering creature starts their turn.</trigger>
  <metadata>
    <class>null</class>
    <cost>11 Discipline</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Discipline</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Null/9th-Level Features</file_dpath>
    <item_id>arrestor-cycle-11-discipline</item_id>
    <item_index>03</item_index>
    <item_name>Arrestor Cycle (11 Discipline)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.null.9th-level-feature:arrestor-cycle-11-discipline</scc>
    <scdc>1.1.1:5.2.2.6:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/null/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>I &lt; WEAK, the target loses their turn</t1>
      <t2>I &lt; AVERAGE, the target loses their turn</t2>
      <t3>I &lt; STRONG, the target loses their turn</t3>
    </effect>
    <effect type="mundane">If the target loses their turn, the round continues as if they had acted. A target who doesn&apos;t lose their turn takes psychic damage equal to twice your Intuition score for each main action they take until the end of their next turn.</effect>
  </effects>
</ability>
