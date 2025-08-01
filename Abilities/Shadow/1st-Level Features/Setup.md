<ability>
  <name>Setup</name>
  <cost>5 Insight</cost>
  <flavor>Your friends will thank you.</flavor>
  <keywords>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 5</distance>
  <target>One creature</target>
  <metadata>
    <class>shadow</class>
    <cost>5 Insight</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Insight</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Shadow/1st-Level Features</file_dpath>
    <item_id>setup-5-insight</item_id>
    <item_index>06</item_index>
    <item_name>Setup (5 Insight)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.shadow.1st-level-feature:setup-5-insight</scc>
    <scdc>1.1.1:5.1.1.1:06</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/shadow/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>6 + A damage; R &lt; WEAK, the target has damage weakness 5 (save ends)</t1>
      <t2>9 + A damage; R &lt; AVERAGE, the target has damage weakness 5 (save ends)</t2>
      <t3>13 + A damage; R &lt; STRONG, the target has damage weakness 5 (save ends)</t3>
    </effect>
  </effects>
</ability>
