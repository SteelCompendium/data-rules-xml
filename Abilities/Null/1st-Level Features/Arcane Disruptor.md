<ability>
  <name>Arcane Disruptor</name>
  <cost>5 Discipline</cost>
  <flavor>Your blow reorders a foe&apos;s body, causing pain if they attempt to channel sorcery.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Psionic</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <metadata>
    <class>null</class>
    <cost>5 Discipline</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Discipline</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Null/1st-Level Features</file_dpath>
    <item_id>arcane-disruptor-5-discipline</item_id>
    <item_index>06</item_index>
    <item_name>Arcane Disruptor (5 Discipline)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.null.1st-level-feature:arcane-disruptor-5-discipline</scc>
    <scdc>1.1.1:8.2.6.1:06</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/null/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>8 + A psychic damage; M &lt; WEAK, weakened (save ends)</t1>
      <t2>12 + A psychic damage; M &lt; AVERAGE, weakened (save ends)</t2>
      <t3>16 + A psychic damage; M &lt; STRONG, weakened (save ends)</t3>
    </effect>
    <effect type="mundane">While weakened this way, the target takes damage equal to your Intuition score whenever they use a supernatural ability that costs Malice.</effect>
  </effects>
</ability>
