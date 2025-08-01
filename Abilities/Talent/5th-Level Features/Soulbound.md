<ability>
  <name>Soulbound</name>
  <cost>9 Clarity</cost>
  <flavor>You fire a piercing bolt of psychic energy that lances through two foes and leaves a faint intangible thread between them.</flavor>
  <keywords>
    <keyword>Animapathy</keyword>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>Two enemies</target>
  <metadata>
    <class>talent</class>
    <cost>9 Clarity</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/5th-Level Features</file_dpath>
    <item_id>soulbound-9-clarity</item_id>
    <item_index>03</item_index>
    <item_name>Soulbound (9 Clarity)</item_name>
    <level>5</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.5th-level-feature:soulbound-9-clarity</scc>
    <scdc>1.1.1:5.2.1.3:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/5th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>8 damage; A &lt; WEAK, the target is stitched to the other target (save ends)</t1>
      <t2>13 damage; A &lt; AVERAGE, the target is stitched to the other target (save ends)</t2>
      <t3>17 damage; A &lt; STRONG, the target is stitched to the other target (save ends)</t3>
    </effect>
    <effect type="mundane">If any target becomes stitched to the other, both targets are stitched together. While stitched together, a target takes a bane on power rolls while not adjacent to a creature they&apos;re stitched to. Whenever a stitched target takes damage that wasn&apos;t dealt by or also taken by another stitched target, each other stitched target takes half the damage the initial target took.</effect>
    <effect type="mundane" name="Strained">You target yourself and three enemies instead.</effect>
  </effects>
</ability>
