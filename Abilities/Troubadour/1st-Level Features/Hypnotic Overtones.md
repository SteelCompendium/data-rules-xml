<ability>
  <name>Hypnotic Overtones</name>
  <cost>3 Drama</cost>
  <flavor>You produce an entrancing note that twists the senses in a spectacular fashion.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Magic</keyword>
  </keywords>
  <type>Main action</type>
  <distance>2 burst</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>troubadour</class>
    <cost>3 Drama</cost>
    <cost_amount>3</cost_amount>
    <cost_resource>Drama</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Troubadour/1st-Level Features</file_dpath>
    <item_id>hypnotic-overtones-3-drama</item_id>
    <item_index>06</item_index>
    <item_name>Hypnotic Overtones (3 Drama)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.troubadour.1st-level-feature:hypnotic-overtones-3-drama</scc>
    <scdc>1.1.1:5.2.3.1:06</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/troubadour/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>Slide 1; I &lt; WEAK, dazed (save ends)</t1>
      <t2>Slide 1; I &lt; AVERAGE, dazed (save ends)</t2>
      <t3>Slide 2; I &lt; STRONG, dazed (save ends)</t3>
    </effect>
    <effect type="mundane" cost="Spend 2+ Drama">The size of the burst increases by 1 for every 2 drama spent.</effect>
  </effects>
</ability>
