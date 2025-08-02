<ability>
  <name>Erase</name>
  <cost>7 Essence</cost>
  <flavor>With a flick of the wrist, you phase creatures out of existence.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Void</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>Special</target>
  <metadata>
    <class>elementalist</class>
    <cost>7 Essence</cost>
    <cost_amount>7</cost_amount>
    <cost_resource>Essence</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Elementalist/3rd-Level Features</file_dpath>
    <item_id>erase-7-essence</item_id>
    <item_index>01</item_index>
    <item_name>Erase (7 Essence)</item_name>
    <level>3</level>
    <scc>mcdm.heroes.v1:feature.ability.elementalist.3rd-level-feature:erase-7-essence</scc>
    <scdc>1.1.1:14.2.9.6:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/elementalist/3rd-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane" name="Special">The number of creatures you target with this ability is determined by your power roll.</effect>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>One creature</t1>
      <t2>Two creatures</t2>
      <t3>Three creatures</t3>
    </effect>
    <effect type="mundane">Each target begins to fade from existence (save ends). On their first turn while fading from existence, a target takes a bane on power rolls. At the end of their first turn, they have a double bane on power rolls. At the end of their second turn, they fade from existence for 1 hour, after which they reappear in their original space or the nearest unoccupied space.</effect>
  </effects>
</ability>
