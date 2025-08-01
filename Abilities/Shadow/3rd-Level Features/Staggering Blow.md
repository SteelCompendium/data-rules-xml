<ability>
  <name>Staggering Blow</name>
  <cost>7 Insight</cost>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1 or ranged 5</distance>
  <target>One creature</target>
  <metadata>
    <class>shadow</class>
    <cost>7 Insight</cost>
    <cost_amount>7</cost_amount>
    <cost_resource>Insight</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Shadow/3rd-Level Features</file_dpath>
    <item_id>staggering-blow-7-insight</item_id>
    <item_index>01</item_index>
    <item_name>Staggering Blow (7 Insight)</item_name>
    <level>3</level>
    <scc>mcdm.heroes.v1:feature.ability.shadow.3rd-level-feature:staggering-blow-7-insight</scc>
    <scdc>1.1.1:5.1.1.6:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/shadow/3rd-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>7 + A damage; M &lt; WEAK, slowed (save ends)</t1>
      <t2>11 + A damage; M &lt; AVERAGE, prone and can&apos;t stand (save ends)</t2>
      <t3>16 + A damage; M &lt; STRONG, prone and can&apos;t stand (save ends)</t3>
    </effect>
  </effects>
</ability>
