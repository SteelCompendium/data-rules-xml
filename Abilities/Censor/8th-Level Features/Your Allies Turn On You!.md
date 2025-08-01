<ability>
  <name>Your Allies Turn on You!</name>
  <cost>11 Wrath</cost>
  <flavor>You turn your enemies&apos; ire to the target.</flavor>
  <keywords>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>censor</class>
    <cost>11 Wrath</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Wrath</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Censor/8th-Level Features</file_dpath>
    <item_id>your-allies-turn-on-you-11-wrath</item_id>
    <item_index>01</item_index>
    <item_name>Your Allies Turn on You! (11 Wrath)</item_name>
    <level>8</level>
    <scc>mcdm.heroes.v1:feature.ability.censor.8th-level-feature:your-allies-turn-on-you-11-wrath</scc>
    <scdc>1.1.1:5.2.7.2:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/censor/8th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>5 + P damage; I &lt; WEAK, slowed (save ends)</t1>
      <t2>9 + P damage; I &lt; AVERAGE, slowed (save ends)</t2>
      <t3>12 + P damage; I &lt; STRONG, slowed (save ends)</t3>
    </effect>
    <effect type="mundane">While the target is slowed this way, each ally who starts their turn within 5 squares of them must use a free maneuver to make a free strike against the target. Additionally, while the target is slowed this way, each ally within 5 squares of them who can make a triggered free strike against a different creature must make the free strike against the target instead.</effect>
  </effects>
</ability>
