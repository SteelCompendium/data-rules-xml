<ability>
  <name>Eviscerate</name>
  <cost>3 Insight</cost>
  <flavor>You leave your foe bleeding out after a devastating attack</flavor>
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
    <cost>3 Insight</cost>
    <cost_amount>3</cost_amount>
    <cost_resource>Insight</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Shadow/1st-Level Features</file_dpath>
    <item_id>eviscerate-3-insight</item_id>
    <item_index>01</item_index>
    <item_name>Eviscerate (3 Insight)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.shadow.1st-level-feature:eviscerate-3-insight</scc>
    <scdc>1.1.1:8.2.2.1:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/shadow/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>4 + A damage; R &lt; WEAK, bleeding (save ends)</t1>
      <t2>6 + A damage; R &lt; AVERAGE, bleeding (save ends)</t2>
      <t3>10 + A damage; R &lt; STRONG, bleeding (save ends)</t3>
    </effect>
  </effects>
</ability>
