<ability>
  <name>Into the Shadows</name>
  <cost>9 Insight</cost>
  <flavor>You sweep your foe off their feet and plunge them into absolute darkness.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature or object</target>
  <metadata>
    <class>shadow</class>
    <cost>9 Insight</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Insight</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Shadow/5th-Level Features</file_dpath>
    <item_id>into-the-shadows-9-insight</item_id>
    <item_index>02</item_index>
    <item_name>Into the Shadows (9 Insight)</item_name>
    <level>5</level>
    <scc>mcdm.heroes.v1:feature.ability.shadow.5th-level-feature:into-the-shadows-9-insight</scc>
    <scdc>1.1.1:10.2.2.4:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/shadow/5th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You and the target are removed from the encounter map until the start of your next turn. You reappear in the spaces you left or the nearest unoccupied spaces. Make a power roll upon your return.</effect>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>8 + A corruption damage</t1>
      <t2>13 + A corruption damage</t2>
      <t3>17 + A corruption damage</t3>
    </effect>
  </effects>
</ability>
