<ability>
  <name>It Is Justice You Fear</name>
  <cost>5 Wrath</cost>
  <flavor>I am but a vessel. Your own deeds weigh upon you.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>censor</class>
    <cost>5 Wrath</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Wrath</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Censor/2nd-Level Features</file_dpath>
    <item_id>it-is-justice-you-fear-5-wrath</item_id>
    <item_index>05</item_index>
    <item_name>It Is Justice You Fear (5 Wrath)</item_name>
    <level>2</level>
    <scc>mcdm.heroes.v1:feature.ability.censor.2nd-level-feature:it-is-justice-you-fear-5-wrath</scc>
    <scdc>1.1.1:5.1.5.5:05</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/censor/2nd-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>8 + M holy damage; P &lt; WEAK, frightened (save ends)</t1>
      <t2>12 + M holy damage; P &lt; AVERAGE, frightened (save ends)</t2>
      <t3>15 + M holy damage; P &lt; STRONG, frightened (save ends)</t3>
    </effect>
    <effect type="mundane">If the target is already frightened of you or another creature and this ability would frighten them again, they instead take psychic damage equal to twice your Presence score.</effect>
  </effects>
</ability>
