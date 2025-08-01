<ability>
  <name>Divine Dragon</name>
  <cost>11 Piety</cost>
  <flavor>From nothing but divine will, you create a powerful ally.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>Special</target>
  <metadata>
    <class>conduit</class>
    <cost>11 Piety</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Piety</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Conduit/9th-Level Features</file_dpath>
    <item_id>divine-dragon-11-piety</item_id>
    <item_index>12</item_index>
    <item_name>Divine Dragon (11 Piety)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.conduit.9th-level-feature:divine-dragon-11-piety</scc>
    <scdc>1.1.1:6.2.8.7:12</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/conduit/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You conjure a size 4 dragon that appears in an unoccupied space within distance. The dragon has speed 6 and can fly, stability 4, 100 Stamina, immunity all to fire damage, and uses your characteristics. The dragon disappears at the end of the encounter, if their Stamina drops to 0, or if you are dying. On subsequent turns, you can use a main action to command the dragon to breathe magic fire in a 3 cube within 1 square of them. Make the following power roll targeting each enemy in the area.</effect>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>5 fire damage</t1>
      <t2>9 fire damage</t2>
      <t3>12 fire damage</t3>
    </effect>
    <effect type="mundane">Additionally, you can use a maneuver to move the dragon up to their speed, or to make a melee weapon strike with their claw against an adjacent creature or object. The dragon can also make this strike as a free strike.</effect>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>3 + I damage</t1>
      <t2>5 + I damage</t2>
      <t3>8 + I damage</t3>
    </effect>
  </effects>
</ability>
