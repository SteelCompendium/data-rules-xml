<ability>
  <name>You Talk Too Much</name>
  <cost>9 Insight</cost>
  <flavor>Silence is a virtue. A knife pinning their mouth shut is the next best thing.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1 or ranged 5</distance>
  <target>One creature</target>
  <metadata>
    <class>shadow</class>
    <cost>9 Insight</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Insight</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Shadow/5th-Level Features</file_dpath>
    <item_id>you-talk-too-much-9-insight</item_id>
    <item_index>03</item_index>
    <item_name>You Talk Too Much (9 Insight)</item_name>
    <level>5</level>
    <scc>mcdm.heroes.v1:feature.ability.shadow.5th-level-feature:you-talk-too-much-9-insight</scc>
    <scdc>1.1.1:5.1.1.4:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/shadow/5th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>10 + A damage; P &lt; WEAK, dazed (save ends)</t1>
      <t2>15 + A damage; P &lt; AVERAGE, dazed (save ends)</t2>
      <t3>21 + A damage; P &lt; STRONG, dazed (save ends)</t3>
    </effect>
    <effect type="mundane">The target can&apos;t communicate with anyone until the end of the encounter.</effect>
  </effects>
</ability>
