<ability>
  <name>Corruption&apos;s Curse</name>
  <cost>5 Piety</cost>
  <flavor>Cursed by you, your enemy takes more damage from your allies.</flavor>
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
    <cost>5 Piety</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Piety</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Conduit/1st-Level Features</file_dpath>
    <item_id>corruptions-curse-5-piety</item_id>
    <item_index>02</item_index>
    <item_name>Corruption&apos;s Curse (5 Piety)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.conduit.1st-level-feature:corruptions-curse-5-piety</scc>
    <scdc>1.1.1:5.2.3.1:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/conduit/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>3 + I corruption damage; M &lt; WEAK, damage weakness 5 (save ends)</t1>
      <t2>6 + I corruption damage; M &lt; AVERAGE, damage weakness 5 (save ends)</t2>
      <t3>9 + I corruption damage; M &lt; STRONG, damage weakness 5 (save ends)</t3>
    </effect>
  </effects>
</ability>
