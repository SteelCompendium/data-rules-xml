<ability>
  <name>Optic Blast</name>
  <flavor>Your eyes emit rays of powerful enervating force.</flavor>
  <keywords>
    <keyword>Metamorphosis</keyword>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature or object</target>
  <metadata>
    <class>talent</class>
    <feature_type>trait</feature_type>
    <file_dpath>Talent/1st-Level Features</file_dpath>
    <item_id>optic-blast</item_id>
    <item_index>20</item_index>
    <item_name>Optic Blast</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.talent.1st-level-feature:optic-blast</scc>
    <scdc>1.1.1:7.1.1.1:20</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/talent/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>2 + R damage; M &lt; WEAK, prone</t1>
      <t2>4 + R damage; M &lt; AVERAGE, prone</t2>
      <t3>6 + R damage; M &lt; STRONG, prone</t3>
    </effect>
    <effect type="mundane">When targeting an object with a solid reflective surface or a creature carrying or wearing such an object (such as a mirror, an unpainted metal shield, or shiny metal plate armor), you can target one additional creature or object within 3 squares of the first target.</effect>
    <effect type="mundane" name="Strained">You gain 1 surge that you can use immediately, and you take damage equal to your Reason score that can&apos;t be reduced in any way.</effect>
  </effects>
</ability>
