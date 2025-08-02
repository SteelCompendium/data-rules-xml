<ability>
  <name>Doubt</name>
  <cost>11 Clarity</cost>
  <flavor>You tug at the strings of the foe&apos;s anima and unravel them, allowing someone else to take advantage of their drive.</flavor>
  <keywords>
    <keyword>Animapathy</keyword>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature or object</target>
  <metadata>
    <class>talent</class>
    <cost>11 Clarity</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/8th-Level Features</file_dpath>
    <item_id>doubt-11-clarity</item_id>
    <item_index>04</item_index>
    <item_name>Doubt (11 Clarity)</item_name>
    <level>8</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.8th-level-feature:doubt-11-clarity</scc>
    <scdc>1.1.1:14.2.1.2:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/8th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>10 + P damage; P &lt; WEAK, weakened (save ends)</t1>
      <t2>14 + P damage; P &lt; AVERAGE, weakened (save ends)</t2>
      <t3>20 + P damage; P &lt; STRONG, weakened and slowed (save ends)</t3>
    </effect>
    <effect type="mundane">This ability gains an edge against a target with a soul (see *[Draw Steel: Monsters](https://mcdm.gg/DS-Monsters)*). After you make the power roll, you or one ally within distance have a double edge on the next power roll you make before the end of the encounter.</effect>
    <effect type="mundane" name="Strained">You feel dispirited until you finish a respite. If you obtain a tier 3 outcome on the power roll, you and the target each have damage weakness 5 (save ends).</effect>
  </effects>
</ability>
