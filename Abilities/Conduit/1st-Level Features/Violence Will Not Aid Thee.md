<ability>
  <name>Violence Will Not Aid Thee</name>
  <cost>3 Piety</cost>
  <flavor>After some holy lightning, your enemy will think twice about their next attack.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>conduit</class>
    <cost>3 Piety</cost>
    <cost_amount>3</cost_amount>
    <cost_resource>Piety</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Conduit/1st-Level Features</file_dpath>
    <item_id>violence-will-not-aid-thee-3-piety</item_id>
    <item_index>06</item_index>
    <item_name>Violence Will Not Aid Thee (3 Piety)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.conduit.1st-level-feature:violence-will-not-aid-thee-3-piety</scc>
    <scdc>1.1.1:8.2.8.1:06</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/conduit/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>3 + I lightning damage</t1>
      <t2>6 + I lightning damage</t2>
      <t3>9 + I lightning damage</t3>
    </effect>
    <effect type="mundane">The first time on a turn that the target deals damage to another creature, the target of this ability takes 1d10 lightning damage (save ends).</effect>
  </effects>
</ability>
