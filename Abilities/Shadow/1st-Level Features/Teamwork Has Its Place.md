<ability>
  <name>Teamwork Has Its Place</name>
  <flavor>You attack an enemy as an ally exposes their weakness.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1 or ranged 5</distance>
  <target>One creature or object</target>
  <metadata>
    <class>shadow</class>
    <feature_type>trait</feature_type>
    <file_dpath>Shadow/1st-Level Features</file_dpath>
    <item_id>teamwork-has-its-place</item_id>
    <item_index>11</item_index>
    <item_name>Teamwork Has Its Place</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.shadow.1st-level-feature:teamwork-has-its-place</scc>
    <scdc>1.1.1:5.2.1.1:11</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/shadow/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>3 + A damage</t1>
      <t2>6 + A damage</t2>
      <t3>9 + A damage</t3>
    </effect>
    <effect type="mundane">If any ally is adjacent to the target, you gain 1 surge before making the power roll.</effect>
  </effects>
</ability>
