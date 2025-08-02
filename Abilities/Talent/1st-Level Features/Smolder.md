<ability>
  <name>Smolder</name>
  <cost>3 Clarity</cost>
  <flavor>Smoke flows from your enemy like tears as their skin begins to blacken and flake.</flavor>
  <keywords>
    <keyword>Psionic</keyword>
    <keyword>Pyrokinesis</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>talent</class>
    <cost>3 Clarity</cost>
    <cost_amount>3</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/1st-Level Features</file_dpath>
    <item_id>smolder-3-clarity</item_id>
    <item_index>04</item_index>
    <item_name>Smolder (3 Clarity)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.1st-level-feature:smolder-3-clarity</scc>
    <scdc>1.1.1:14.2.1.1:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">Choose the damage type and the weakness for this ability from one of the following: acid, corruption, or fire. The target takes damage before this ability imposes any weakness.</effect>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>3 + R damage; R &lt; WEAK, the target has weakness 5 (save ends)</t1>
      <t2>6 + R damage; R &lt; AVERAGE, the target has weakness 5 (save ends)</t2>
      <t3>9 + R damage; R &lt; STRONG, the target has weakness equal to 5 + your Reason score (save ends)</t3>
    </effect>
  </effects>
</ability>
