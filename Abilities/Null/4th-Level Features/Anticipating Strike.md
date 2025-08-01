<ability>
  <name>Anticipating Strike</name>
  <cost>9 Discipline</cost>
  <flavor>You suddenly strike an enemy, then grab them in a psionically enhanced grip.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Psionic</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Free trigger</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <trigger>The target moves or uses a main action.</trigger>
  <metadata>
    <class>null</class>
    <cost>9 Discipline</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Discipline</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Null/4th-Level Features</file_dpath>
    <item_id>anticipating-strike-9-discipline</item_id>
    <item_index>01</item_index>
    <item_name>Anticipating Strike (9 Discipline)</item_name>
    <level>4</level>
    <scc>mcdm.heroes.v1:feature.ability.null.4th-level-feature:anticipating-strike-9-discipline</scc>
    <scdc>1.1.1:5.2.2.8:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/null/4th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>7 + A damage; I &lt; WEAK, restrained (save ends)</t1>
      <t2>10 + A damage; I &lt; AVERAGE, restrained (save ends)</t2>
      <t3>13 + A damage; I &lt; STRONG, restrained (save ends)</t3>
    </effect>
    <effect type="mundane">This strike resolves before the triggering movement or main action.</effect>
  </effects>
</ability>
