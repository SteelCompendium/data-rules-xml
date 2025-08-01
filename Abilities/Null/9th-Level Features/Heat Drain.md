<ability>
  <name>Heat Drain</name>
  <cost>11 Discipline</cost>
  <flavor>You drain all the heat from the target.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Psionic</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Maneuver</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <metadata>
    <class>null</class>
    <cost>11 Discipline</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Discipline</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Null/9th-Level Features</file_dpath>
    <item_id>heat-drain-11-discipline</item_id>
    <item_index>05</item_index>
    <item_name>Heat Drain (11 Discipline)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.null.9th-level-feature:heat-drain-11-discipline</scc>
    <scdc>1.1.1:13.2.6.6:05</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/null/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>8 + I cold damage; M &lt; WEAK, restrained (save ends)</t1>
      <t2>11 + I cold damage; M &lt; AVERAGE, restrained (save ends)</t2>
      <t3>15 + I cold damage; M &lt; STRONG, restrained (save ends)</t3>
    </effect>
    <effect type="mundane">While restrained this way, the target takes cold damage equal to your Intuition score at the start of each of your turns. Additionally, whenever the target damages another creature while restrained this way, any potency associated with the damage is reduced by 2.</effect>
  </effects>
</ability>
