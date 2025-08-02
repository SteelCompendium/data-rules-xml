<ability>
  <name>Kinetic Pulse</name>
  <flavor>The force of your mind hurls enemies backward.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Psionic</keyword>
    <keyword>Telepathy</keyword>
  </keywords>
  <type>Main action</type>
  <distance>1 burst</distance>
  <target>Each enemy in the area</target>
  <metadata>
    <class>talent</class>
    <feature_type>trait</feature_type>
    <file_dpath>Talent/1st-Level Features</file_dpath>
    <item_id>kinetic-pulse</item_id>
    <item_index>17</item_index>
    <item_name>Kinetic Pulse</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.talent.1st-level-feature:kinetic-pulse</scc>
    <scdc>1.1.1:13.1.1.1:17</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/talent/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>2 psychic damage</t1>
      <t2>5 psychic damage; push 1</t2>
      <t3>7 psychic damage; push 2</t3>
    </effect>
    <effect type="mundane" name="Strained">The size of the burst increases by 2, and you are bleeding until the start of your next turn.</effect>
  </effects>
</ability>
