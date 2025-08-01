<ability>
  <name>Upstage</name>
  <cost>3 Drama</cost>
  <flavor>As you bob and weave through the crowd, you can&apos;t help but leave the audience wanting more.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Maneuver</type>
  <distance>Self; see below</distance>
  <target>Self</target>
  <metadata>
    <class>troubadour</class>
    <cost>3 Drama</cost>
    <cost_amount>3</cost_amount>
    <cost_resource>Drama</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Troubadour/1st-Level Features</file_dpath>
    <item_id>upstage-3-drama</item_id>
    <item_index>02</item_index>
    <item_name>Upstage (3 Drama)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.troubadour.1st-level-feature:upstage-3-drama</scc>
    <scdc>1.1.1:9.2.3.1:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/troubadour/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You shift up to your speed. You make one power roll that targets each enemy you move adjacent to during this shift.</effect>
    <effect type="roll">
      <roll>Power Roll + Agility or Presence</roll>
      <t1>Taunted (EoT); A &lt; WEAK, prone</t1>
      <t2>Taunted (EoT); A &lt; AVERAGE, prone</t2>
      <t3>Taunted (EoT); A &lt; STRONG, prone and can&apos;t stand (EoT)</t3>
    </effect>
  </effects>
</ability>
