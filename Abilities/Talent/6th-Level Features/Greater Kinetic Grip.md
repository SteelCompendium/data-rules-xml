<ability>
  <name>Greater Kinetic Grip</name>
  <cost>9 Clarity</cost>
  <flavor>You raise the target into the air without breaking a sweat.</flavor>
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
    <cost>9 Clarity</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/6th-Level Features</file_dpath>
    <item_id>greater-kinetic-grip-9-clarity</item_id>
    <item_index>03</item_index>
    <item_name>Greater Kinetic Grip (9 Clarity)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.6th-level-feature:greater-kinetic-grip-9-clarity</scc>
    <scdc>1.1.1:7.2.1.3:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>Slide 4 + R; M &lt; WEAK, the forced movement is vertical</t1>
      <t2>Slide 8 + R; M &lt; AVERAGE, the forced movement is vertical</t2>
      <t3>Slide 12 + R; prone; M &lt; STRONG, the forced movement is vertical</t3>
    </effect>
    <effect type="mundane" name="Strained">The forced movement ignores stability. You take 2d6 damage and are weakened (save ends).</effect>
  </effects>
</ability>
