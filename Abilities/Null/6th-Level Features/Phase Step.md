<ability>
  <name>Phase Step</name>
  <cost>9 Discipline</cost>
  <flavor>You weaken your connection to this manifold, allowing you to move through and damage enemies.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Psionic</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Self; see below</distance>
  <target>Self</target>
  <metadata>
    <class>null</class>
    <cost>9 Discipline</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Discipline</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Null/6th-Level Features</file_dpath>
    <item_id>phase-step-9-discipline</item_id>
    <item_index>06</item_index>
    <item_name>Phase Step (9 Discipline)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.null.6th-level-feature:phase-step-9-discipline</scc>
    <scdc>1.1.1:5.2.6.3:06</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/null/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You can shift up to your speed, and squares occupied by enemies or objects are not difficult terrain for this shift. You make one power roll that targets each enemy you moved through during this shift.</effect>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>6 damage; M &lt; WEAK, dazed</t1>
      <t2>8 damage; M &lt; AVERAGE, dazed</t2>
      <t3>12 damage; M &lt; STRONG, dazed</t3>
    </effect>
  </effects>
</ability>
