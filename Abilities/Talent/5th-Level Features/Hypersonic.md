<ability>
  <name>Hypersonic</name>
  <cost>9 Clarity</cost>
  <flavor>You move fast enough to turn around and watch your foes feel the aftermath.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Charge</keyword>
    <keyword>Psionic</keyword>
    <keyword>Telekinesis</keyword>
  </keywords>
  <type>Main action</type>
  <distance>5 × 2 line within 1</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>talent</class>
    <cost>9 Clarity</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/5th-Level Features</file_dpath>
    <item_id>hypersonic-9-clarity</item_id>
    <item_index>04</item_index>
    <item_name>Hypersonic (9 Clarity)</item_name>
    <level>5</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.5th-level-feature:hypersonic-9-clarity</scc>
    <scdc>1.1.1:5.2.1.3:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/5th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You teleport to a square on the opposite side of the area before making the power roll.</effect>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>12 sonic damage</t1>
      <t2>18 sonic damage</t2>
      <t3>24 sonic damage</t3>
    </effect>
    <effect type="mundane" name="Strained">If you obtain a tier 2 outcome or better, you are slowed until the end of your turn and each target is slowed until the end of their turn.</effect>
  </effects>
</ability>
