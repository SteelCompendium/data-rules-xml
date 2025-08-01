<ability>
  <name>Acceleration Field</name>
  <cost>11 Clarity</cost>
  <flavor>You forcibly stuff more moments into a critical point in time, knowing full well you might need to steal some of your own.</flavor>
  <keywords>
    <keyword>Chronopathy</keyword>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 5</distance>
  <target>Three allies</target>
  <metadata>
    <class>talent</class>
    <cost>11 Clarity</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/9th-Level Features</file_dpath>
    <item_id>acceleration-field-11-clarity</item_id>
    <item_index>02</item_index>
    <item_name>Acceleration Field (11 Clarity)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.9th-level-feature:acceleration-field-11-clarity</scc>
    <scdc>1.1.1:5.2.1.7:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">Each target can use any main action available to them as a free triggered action, but they lose their main action on their next turn.</effect>
    <effect type="mundane" name="Strained">Make a power roll that targets you and each enemy within distance.</effect>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>4 corruption damage; slowed (save ends)</t1>
      <t2>6 corruption damage; slowed (save ends)</t2>
      <t3>10 corruption damage; slowed (save ends)</t3>
    </effect>
  </effects>
</ability>
