<ability>
  <name>Sticky Bomb</name>
  <cost>5 Insight</cost>
  <flavor>Explosives are best when they&apos;re attached to an enemy.</flavor>
  <keywords>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>shadow</class>
    <cost>5 Insight</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Insight</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Shadow/2nd-Level Features</file_dpath>
    <item_id>sticky-bomb-5-insight</item_id>
    <item_index>02</item_index>
    <item_name>Sticky Bomb (5 Insight)</item_name>
    <level>2</level>
    <scc>mcdm.heroes.v1:feature.ability.shadow.2nd-level-feature:sticky-bomb-5-insight</scc>
    <scdc>1.1.1:5.2.3.5:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/shadow/2nd-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You attach a small bomb to a creature. If you are hidden from the creature, they don&apos;t notice the bomb and you remain hidden. The creature otherwise notices the bomb and can disarm and remove it as a main action. If they don&apos;t, at the end of your next turn, the bomb detonates. When the bomb detonates, you make a power roll targeting each enemy within 2 squares of it.</effect>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>4 + A fire damage</t1>
      <t2>7 + A fire damage</t2>
      <t3>11 + A fire damage</t3>
    </effect>
  </effects>
</ability>
