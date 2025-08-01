<ability>
  <name>Phase Strike</name>
  <cost>5 Discipline</cost>
  <flavor>For a moment, your foe slips out of phase with this manifold.</flavor>
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
    <item_id>phase-strike-5-discipline</item_id>
    <item_index>01</item_index>
    <item_name>Phase Strike (5 Discipline)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.null.1st-level-feature:phase-strike-5-discipline</scc>
    <scdc>1.1.1:10.2.6.1:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/null/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>3 + A psychic damage; I &lt; WEAK, the target goes out of phase (save ends)</t1>
      <t2>4 + A psychic damage; I &lt; AVERAGE, the target goes out of phase (save ends)</t2>
      <t3>6 + A psychic damage; I &lt; STRONG, the target goes out of phase (save ends)</t3>
    </effect>
    <effect type="mundane">A target who goes out of phase is slowed, has their stability reduced by 2, and can&apos;t obtain a tier 3 outcome on ability rolls.</effect>
  </effects>
</ability>
