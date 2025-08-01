<ability>
  <name>Meteor</name>
  <cost>9 Essence</cost>
  <flavor>You teleport the target into the air and let the ground and the elemental force of fire do the rest.</flavor>
  <keywords>
    <keyword>Earth</keyword>
    <keyword>Fire</keyword>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Void</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature or object</target>
  <metadata>
    <class>elementalist</class>
    <cost>9 Essence</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Essence</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Elementalist/6th-Level Features</file_dpath>
    <item_id>meteor-9-essence</item_id>
    <item_index>01</item_index>
    <item_name>Meteor (9 Essence)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.elementalist.6th-level-feature:meteor-9-essence</scc>
    <scdc>1.1.1:5.1.7.3:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/elementalist/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>You teleport the target up to 4 squares.</t1>
      <t2>You teleport the target up to 6 squares.</t2>
      <t3>You teleport the target up to 8 squares.</t3>
    </effect>
    <effect type="mundane">If the target is teleported to a space where they would fall, they immediately do so, treating the fall as if their Agility score were 0. The target takes fire damage from the fall, and each enemy within 3 squares of where they land takes the same amount of fire damage. The ground within 3 squares of where the target lands is difficult terrain.</effect>
  </effects>
</ability>
