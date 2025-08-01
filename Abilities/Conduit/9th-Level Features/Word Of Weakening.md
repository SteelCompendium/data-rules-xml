<ability>
  <name>Word of Weakening</name>
  <cost>11 Piety</cost>
  <flavor>You utter a divine word that makes a foe brittle.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature or object</target>
  <metadata>
    <class>conduit</class>
    <cost>11 Piety</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Piety</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Conduit/9th-Level Features</file_dpath>
    <item_id>word-of-weakening-11-piety</item_id>
    <item_index>05</item_index>
    <item_name>Word of Weakening (11 Piety)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.conduit.9th-level-feature:word-of-weakening-11-piety</scc>
    <scdc>1.1.1:7.2.8.7:05</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/conduit/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>10 + I corruption damage; A &lt; WEAK, weakened (save ends)</t1>
      <t2>15 + I corruption damage; A &lt; AVERAGE, weakened (save ends)</t2>
      <t3>21 + I corruption damage; A &lt; STRONG, weakened (save ends)</t3>
    </effect>
    <effect type="mundane">While weakened this way, the target has damage weakness 10.</effect>
  </effects>
</ability>
