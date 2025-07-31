<ability>
  <name>Terror Manifest</name>
  <cost>11 Wrath</cost>
  <flavor>&quot;I know what you fear.&quot;</flavor>
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
    <cost>11 Wrath</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Wrath</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Censor/9th-Level Features</file_dpath>
    <item_id>terror-manifest-11-wrath</item_id>
    <item_index>01</item_index>
    <item_name>Terror Manifest (11 Wrath)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.censor.9th-level-feature:terror-manifest-11-wrath</scc>
    <scdc>1.1.1:5.2.7.7:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/censor/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>7 + P psychic damage; P &lt; WEAK, frightened (save ends)</t1>
      <t2>10 + P psychic damage; P &lt; AVERAGE, frightened (save ends)</t2>
      <t3>13 + P psychic damage; P &lt; STRONG, frightened (save ends)</t3>
    </effect>
    <effect type="mundane">While frightened this way, if a target who is a leader or solo creature is winded, they take an extra 25 psychic damage. If a target frightened this way is not a leader or solo creature and is winded, they are reduced to 0 Stamina.</effect>
  </effects>
</ability>
