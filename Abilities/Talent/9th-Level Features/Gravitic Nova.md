<ability>
  <name>Gravitic Nova</name>
  <cost>11 Clarity</cost>
  <flavor>Unbridled psionic energy erupts from your body and flashes outward, hurling your foes back.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Psionic</keyword>
    <keyword>Telekinesis</keyword>
  </keywords>
  <type>Main action</type>
  <distance>3 burst</distance>
  <target>Each enemy and object in the area</target>
  <metadata>
    <class>talent</class>
    <cost>11 Clarity</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/9th-Level Features</file_dpath>
    <item_id>gravitic-nova-11-clarity</item_id>
    <item_index>04</item_index>
    <item_name>Gravitic Nova (11 Clarity)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.9th-level-feature:gravitic-nova-11-clarity</scc>
    <scdc>1.1.1:14.2.1.7:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>6 damage; push 7</t1>
      <t2>9 damage; push 10</t2>
      <t3>13 damage; push 15</t3>
    </effect>
    <effect type="mundane">On a critical hit, the size of the area increases by 3, and this ability deals an extra 10 damage.</effect>
    <effect type="mundane" name="Strained">You are weakened (save ends). If you scored a critical hit with this ability, you die.</effect>
  </effects>
</ability>
