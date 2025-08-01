<ability>
  <name>Penance</name>
  <cost>9 Piety</cost>
  <flavor>&quot;If you won&apos;t kneel, the gods will make you.&quot;</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Main action</type>
  <distance>4 cube within 10</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>conduit</class>
    <cost>9 Piety</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Piety</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Conduit/5th-Level Features</file_dpath>
    <item_id>penance-9-piety</item_id>
    <item_index>02</item_index>
    <item_name>Penance (9 Piety)</item_name>
    <level>5</level>
    <scc>mcdm.heroes.v1:feature.ability.conduit.5th-level-feature:penance-9-piety</scc>
    <scdc>1.1.1:6.2.8.4:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/conduit/5th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>4 corruption damage; I &lt; WEAK, prone and can&apos;t stand (save ends)</t1>
      <t2>7 corruption damage; I &lt; AVERAGE, prone and can&apos;t stand (save ends)</t2>
      <t3>11 corruption damage; I &lt; STRONG, prone and can&apos;t stand (save ends)</t3>
    </effect>
  </effects>
</ability>
