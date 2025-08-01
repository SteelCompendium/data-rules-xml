<ability>
  <name>Infernal Gavotte</name>
  <cost>7 Drama</cost>
  <flavor>A spicy performance lights a fire under your allies&apos; feet.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>3 burst</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>troubadour</class>
    <cost>7 Drama</cost>
    <cost_amount>7</cost_amount>
    <cost_resource>Drama</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Troubadour/3rd-Level Features</file_dpath>
    <item_id>infernal-gavotte-7-drama</item_id>
    <item_index>03</item_index>
    <item_name>Infernal Gavotte (7 Drama)</item_name>
    <level>3</level>
    <scc>mcdm.heroes.v1:feature.ability.troubadour.3rd-level-feature:infernal-gavotte-7-drama</scc>
    <scdc>1.1.1:10.2.3.6:03</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/troubadour/3rd-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>5 fire damage; A &lt; WEAK, weakened (save ends)</t1>
      <t2>7 fire damage; A &lt; AVERAGE, weakened (save ends)</t2>
      <t3>10 fire damage; A &lt; STRONG, weakened (save ends)</t3>
    </effect>
    <effect type="mundane">Each ally in the area can shift up to 2 squares.</effect>
  </effects>
</ability>
