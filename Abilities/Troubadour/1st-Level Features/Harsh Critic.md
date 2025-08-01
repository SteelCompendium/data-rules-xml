<ability>
  <name>Harsh Critic</name>
  <cost>3 Drama</cost>
  <flavor>Just one bad review will ruin their day.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>Melee 1 or ranged 10</distance>
  <target>One creature or object</target>
  <metadata>
    <class>troubadour</class>
    <cost>3 Drama</cost>
    <cost_amount>3</cost_amount>
    <cost_resource>Drama</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Troubadour/1st-Level Features</file_dpath>
    <item_id>harsh-critic-3-drama</item_id>
    <item_index>8</item_index>
    <item_name>Harsh Critic (3 Drama)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.troubadour.1st-level-feature:harsh-critic-3-drama</scc>
    <scdc>1.1.1:9.2.3.1:08</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/troubadour/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>7 + P sonic damage</t1>
      <t2>10 + P sonic damage</t2>
      <t3>13 + P sonic damage</t3>
    </effect>
    <effect type="mundane">The first time the target uses an ability before the start of your next turn, any effects from the ability&apos;s tier outcomes other than damage are negated for all targets. Ability effects that always happen regardless of the power roll work as usual.</effect>
  </effects>
</ability>
