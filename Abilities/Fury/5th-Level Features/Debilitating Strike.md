<ability>
  <name>Debilitating Strike</name>
  <cost>9 Ferocity</cost>
  <flavor>You need just one blow to sabotage your target.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <metadata>
    <class>fury</class>
    <cost>9 Ferocity</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Ferocity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Fury/5th-Level Features</file_dpath>
    <item_id>debilitating-strike-9-ferocity</item_id>
    <item_index>02</item_index>
    <item_name>Debilitating Strike (9 Ferocity)</item_name>
    <level>5</level>
    <scc>mcdm.heroes.v1:feature.ability.fury.5th-level-feature:debilitating-strike-9-ferocity</scc>
    <scdc>1.1.1:5.2.4.4:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/fury/5th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>10 + M damage; M &lt; WEAK, slowed (save ends)</t1>
      <t2>14 + M damage; M &lt; AVERAGE, slowed (save ends)</t2>
      <t3>20 + M damage; M &lt; STRONG, slowed (save ends)</t3>
    </effect>
    <effect type="mundane">While slowed this way, the target takes 1 damage for every square they move, including from forced movement.</effect>
  </effects>
</ability>
