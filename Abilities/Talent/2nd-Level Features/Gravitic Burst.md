<ability>
  <name>Gravitic Burst</name>
  <cost>5 Clarity</cost>
  <flavor>Everyone get away from me!</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Psionic</keyword>
    <keyword>Telekinesis</keyword>
  </keywords>
  <type>Main action</type>
  <distance>1 burst</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>talent</class>
    <cost>5 Clarity</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/2nd-Level Features</file_dpath>
    <item_id>gravitic-burst-5-clarity</item_id>
    <item_index>05</item_index>
    <item_name>Gravitic Burst (5 Clarity)</item_name>
    <level>2</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.2nd-level-feature:gravitic-burst-5-clarity</scc>
    <scdc>1.1.1:14.2.1.5:05</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/2nd-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>3 damage; vertical push 2</t1>
      <t2>6 damage; vertical push 4</t2>
      <t3>9 damage; vertical push 6</t3>
    </effect>
    <effect type="mundane" name="Strained">The size of the burst increases by 1, and you are weakened until the end of your turn.</effect>
  </effects>
</ability>
