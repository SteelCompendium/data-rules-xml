<ability>
  <name>Levity and Gravity</name>
  <cost>5 Clarity</cost>
  <flavor>You raise the target slightly into the air, then smother them against the ground.</flavor>
  <keywords>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Telekinesis</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature or object</target>
  <metadata>
    <class>talent</class>
    <cost>5 Clarity</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/2nd-Level Features</file_dpath>
    <item_id>levity-and-gravity-5-clarity</item_id>
    <item_index>02</item_index>
    <item_name>Levity and Gravity (5 Clarity)</item_name>
    <level>2</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.2nd-level-feature:levity-and-gravity-5-clarity</scc>
    <scdc>1.1.1:5.2.1.4:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/2nd-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>6 + R damage; M &lt; WEAK, prone</t1>
      <t2>10 + R damage; M &lt; AVERAGE, prone</t2>
      <t3>14 + R damage; M &lt; STRONG, prone and can&apos;t stand (save ends)</t3>
    </effect>
    <effect type="mundane" name="Strained">You take half the damage the target takes.</effect>
  </effects>
</ability>
