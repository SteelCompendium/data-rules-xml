<ability>
  <name>Repent!</name>
  <cost>3 Wrath</cost>
  <flavor>You conjure memories of their sins to harry your foes.</flavor>
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
    <cost>3 Wrath</cost>
    <cost_amount>3</cost_amount>
    <cost_resource>Wrath</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Censor/1st-Level Features</file_dpath>
    <item_id>repent-3-wrath</item_id>
    <item_index>01</item_index>
    <item_name>Repent! (3 Wrath)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.censor.1st-level-feature:repent-3-wrath</scc>
    <scdc>1.1.1:13.2.7.1:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/censor/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>5 + P holy damage; I &lt; WEAK, dazed (save ends)</t1>
      <t2>8 + P holy damage; I &lt; AVERAGE, dazed (save ends)</t2>
      <t3>11 + P holy damage; I &lt; STRONG, dazed (save ends)</t3>
    </effect>
  </effects>
</ability>
