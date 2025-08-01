<ability>
  <name>Fear of the Gods</name>
  <cost>7 Piety</cost>
  <flavor>Your divine magic makes a creature appear as what your enemies fear most.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Main action</type>
  <distance>5 cube within 10</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>conduit</class>
    <cost>7 Piety</cost>
    <cost_amount>7</cost_amount>
    <cost_resource>Piety</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Conduit/3rd-Level Features</file_dpath>
    <item_id>fear-of-the-gods-7-piety</item_id>
    <item_index>04</item_index>
    <item_name>Fear of the Gods (7 Piety)</item_name>
    <level>3</level>
    <scc>mcdm.heroes.v1:feature.ability.conduit.3rd-level-feature:fear-of-the-gods-7-piety</scc>
    <scdc>1.1.1:7.2.8.6:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/conduit/3rd-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>6 psychic damage; I &lt; WEAK, frightened (save ends)</t1>
      <t2>9 psychic damage; I &lt; AVERAGE, frightened (save ends)</t2>
      <t3>13 psychic damage; I &lt; STRONG, frightened (save ends)</t3>
    </effect>
    <effect type="mundane">Each target is frightened of you or a creature you choose within distance.</effect>
  </effects>
</ability>
