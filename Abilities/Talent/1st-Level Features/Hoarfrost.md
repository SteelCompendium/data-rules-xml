<ability>
  <name>Hoarfrost</name>
  <flavor>You blast a foe with a pulse of cold energy.</flavor>
  <keywords>
    <keyword>Cryokinesis</keyword>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>talent</class>
    <feature_type>trait</feature_type>
    <file_dpath>Talent/1st-Level Features</file_dpath>
    <item_id>hoarfrost</item_id>
    <item_index>06</item_index>
    <item_name>Hoarfrost</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.talent.1st-level-feature:hoarfrost</scc>
    <scdc>1.1.1:10.1.1.1:06</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/talent/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>2 + R cold damage; M &lt; WEAK, slowed (EoT)</t1>
      <t2>4 + R cold damage; M &lt; AVERAGE, slowed (EoT)</t2>
      <t3>6 + R cold damage; M &lt; STRONG, slowed (EoT)</t3>
    </effect>
    <effect type="mundane" name="Strained">You are slowed until the end of your next turn. Additionally, a target slowed by this ability is restrained instead.</effect>
  </effects>
</ability>
