<ability>
  <name>Arcane Purge</name>
  <cost>11 Discipline</cost>
  <flavor>You focus your null field into a pressure point strike that prevents your foe from channeling sorcery.</flavor>
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
    <cost>11 Discipline</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Discipline</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Null/8th-Level Features</file_dpath>
    <item_id>arcane-purge-11-discipline</item_id>
    <item_index>04</item_index>
    <item_name>Arcane Purge (11 Discipline)</item_name>
    <level>8</level>
    <scc>mcdm.heroes.v1:feature.ability.null.8th-level-feature:arcane-purge-11-discipline</scc>
    <scdc>1.1.1:5.2.2.2:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/null/8th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>13 + A damage; M &lt; WEAK, the target is suppressed (save ends)</t1>
      <t2>19 + A damage; M &lt; AVERAGE, the target is suppressed (save ends)</t2>
      <t3>24 + A damage; M &lt; STRONG, the target is suppressed (save ends)</t3>
    </effect>
    <effect type="mundane">While suppressed, a target takes psychic damage equal to twice your Intuition score at the start of their turns, whenever they use a supernatural ability, or whenever they use an ability that costs Malice.</effect>
  </effects>
</ability>
