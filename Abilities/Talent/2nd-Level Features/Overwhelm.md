<ability>
  <name>Overwhelm</name>
  <cost>5 Clarity</cost>
  <flavor>You overload their senses, turning all their subconscious thoughts into conscious ones.</flavor>
  <keywords>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Telepathy</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>talent</class>
    <cost>5 Clarity</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/2nd-Level Features</file_dpath>
    <item_id>overwhelm-5-clarity</item_id>
    <item_index>01</item_index>
    <item_name>Overwhelm (5 Clarity)</item_name>
    <level>2</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.2nd-level-feature:overwhelm-5-clarity</scc>
    <scdc>1.1.1:6.2.1.5:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/2nd-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>6 + R psychic damage; I &lt; WEAK, slowed (save ends)</t1>
      <t2>10 + R psychic damage; I &lt; AVERAGE, weakened (save ends)</t2>
      <t3>14 + R psychic damage; I &lt; STRONG, dazed (save ends)</t3>
    </effect>
    <effect type="mundane" name="Strained">You start crying, and you can&apos;t use triggered actions or make free strikes until the end of the target&apos;s next turn.</effect>
  </effects>
</ability>
