<ability>
  <name>Your Allies Cannot Save You!</name>
  <flavor>Your magic strike turns your foe&apos;s guilt into a burst of holy power.</flavor>
  <keywords>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>Melee 1</distance>
  <target>One creature or object</target>
  <metadata>
    <class>censor</class>
    <feature_type>trait</feature_type>
    <file_dpath>Censor/1st-Level Features</file_dpath>
    <item_id>your-allies-cannot-save-you</item_id>
    <item_index>16</item_index>
    <item_name>Your Allies Cannot Save You!</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.censor.1st-level-feature:your-allies-cannot-save-you</scc>
    <scdc>1.1.1:8.1.7.1:16</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/censor/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>3 + M holy damage</t1>
      <t2>5 + M holy damage</t2>
      <t3>8 + M holy damage</t3>
    </effect>
    <effect type="mundane">Each enemy adjacent to the target is pushed away from the target up to a number of squares equal to your Presence score.</effect>
  </effects>
</ability>
