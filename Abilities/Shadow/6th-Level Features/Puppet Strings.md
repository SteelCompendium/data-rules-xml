<ability>
  <name>Puppet Strings</name>
  <cost>9 Insight</cost>
  <flavor>You prick little needles on the tips of your fingers into the nerves of your enemies and cause them to lose control.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>Two enemies</target>
  <metadata>
    <class>shadow</class>
    <cost>9 Insight</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Insight</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Shadow/6th-Level Features</file_dpath>
    <item_id>puppet-strings-9-insight</item_id>
    <item_index>04</item_index>
    <item_name>Puppet Strings (9 Insight)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.shadow.6th-level-feature:puppet-strings-9-insight</scc>
    <scdc>1.1.1:10.2.2.3:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/shadow/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Agility</roll>
      <t1>2 damage; if the target has R &lt; WEAK, before the damage is resolved, they make a free strike.</t1>
      <t2>5 damage; if the target has R &lt; AVERAGE, before the damage is resolved, they use a main action ability of your choice.</t2>
      <t3>7 damage; if the target has R &lt; STRONG, before the damage is resolved, they can shift up to their speed and use a main action ability of your choice.</t3>
    </effect>
    <effect type="mundane">You choose the new targets for the original target&apos;s free strike or ability. Additionally, if you are hidden or disguised, using this ability doesn&apos;t cause you to be revealed.</effect>
  </effects>
</ability>
