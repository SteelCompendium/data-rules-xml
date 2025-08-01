<ability>
  <name>Gods&apos; Machine</name>
  <cost>9 Piety</cost>
  <flavor>You conjure a whirring tank made of blades and metal.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>Special</target>
  <metadata>
    <class>conduit</class>
    <cost>9 Piety</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Piety</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Conduit/6th-Level Features</file_dpath>
    <item_id>gods-machine-9-piety</item_id>
    <item_index>12</item_index>
    <item_name>Gods&apos; Machine (9 Piety)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.conduit.6th-level-feature:gods-machine-9-piety</scc>
    <scdc>1.1.1:7.2.8.3:12</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/conduit/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You conjure a size 2 rolling machine that appears in an unoccupied space within distance. The machine has 50 Stamina and immunity all to poison and psychic damage. It disappears at the end of the encounter, if its Stamina drops to 0, or if you are dying. When the machine first appears, make the following power roll once, targeting each enemy adjacent to it.</effect>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>3 damage</t1>
      <t2>5 damage</t2>
      <t3>8 damage</t3>
    </effect>
    <effect type="mundane">Once on each subsequent turn, you can use a free maneuver to move the machine a number of squares up to your Intuition score then repeat the power roll.</effect>
  </effects>
</ability>
