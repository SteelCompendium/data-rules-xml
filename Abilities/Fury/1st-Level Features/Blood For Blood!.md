<ability>
  <name>Blood for Blood!</name>
  <cost>5 Ferocity</cost>
  <flavor>See how well they fight after you&apos;ve bled them dry.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature or object</target>
  <metadata>
    <class>fury</class>
    <cost>5 Ferocity</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Ferocity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Fury/1st-Level Features</file_dpath>
    <item_id>blood-for-blood-5-ferocity</item_id>
    <item_index>03</item_index>
    <item_name>Blood for Blood! (5 Ferocity)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.fury.1st-level-feature:blood-for-blood-5-ferocity</scc>
    <scdc>1.1.1:6.2.5.1:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/fury/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>4 + M damage; M &lt; WEAK, bleeding and weakened (save ends)</t1>
      <t2>6 + M damage; M &lt; AVERAGE, bleeding and weakened (save ends)</t2>
      <t3>10 + M damage; M &lt; STRONG, bleeding and weakened (save ends)</t3>
    </effect>
    <effect type="mundane">You can deal 1d6 damage to yourself to deal an extra 1d6 damage to the target.</effect>
  </effects>
</ability>
