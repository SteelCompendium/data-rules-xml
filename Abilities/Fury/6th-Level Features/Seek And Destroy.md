<ability>
  <name>Seek and Destroy</name>
  <cost>9 Ferocity</cost>
  <flavor>You break through the enemy lines to make an example.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <metadata>
    <class>fury</class>
    <cost>9 Ferocity</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Ferocity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Fury/6th-Level Features</file_dpath>
    <item_id>seek-and-destroy-9-ferocity</item_id>
    <item_index>06</item_index>
    <item_name>Seek and Destroy (9 Ferocity)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.fury.6th-level-feature:seek-and-destroy-9-ferocity</scc>
    <scdc>1.1.1:14.2.5.3:06</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/fury/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You shift up to your speed.</effect>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>4 + M damage; P &lt; WEAK, frightened (save ends)</t1>
      <t2>6 + M damage; P &lt; AVERAGE, frightened (save ends)</t2>
      <t3>10 + M damage; P &lt; STRONG, frightened (save ends)</t3>
    </effect>
    <effect type="mundane">If a target who is not a leader or solo creature is winded by this strike, they are reduced to 0 Stamina and you choose an enemy within 5 squares of you. If that enemy has P &lt; AVERAGE, they are frightened of you (save ends).</effect>
  </effects>
</ability>
