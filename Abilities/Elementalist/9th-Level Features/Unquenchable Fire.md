<ability>
  <name>Unquenchable Fire</name>
  <cost>11 Essence</cost>
  <flavor>You let fly a fiery missile braided with pure primal energy.</flavor>
  <keywords>
    <keyword>Fire</keyword>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One enemy or object</target>
  <metadata>
    <class>elementalist</class>
    <cost>11 Essence</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Essence</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Elementalist/9th-Level Features</file_dpath>
    <item_id>unquenchable-fire-11-essence</item_id>
    <item_index>04</item_index>
    <item_name>Unquenchable Fire (11 Essence)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.elementalist.9th-level-feature:unquenchable-fire-11-essence</scc>
    <scdc>1.1.1:14.2.9.7:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/elementalist/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>13 + R fire damage; I &lt; WEAK, dazed (save ends)</t1>
      <t2>18 + R fire damage; I &lt; AVERAGE, dazed (save ends)</t2>
      <t3>25 + Rfire damage; I &lt; STRONG, dazed (save ends)</t3>
    </effect>
    <effect type="mundane">This damage ignores immunity.</effect>
  </effects>
</ability>
