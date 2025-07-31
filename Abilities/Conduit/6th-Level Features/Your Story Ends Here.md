<ability>
  <name>Your Story Ends Here</name>
  <cost>9 Piety</cost>
  <flavor>You bend the fate of a foe, willing them to die.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>conduit</class>
    <cost>9 Piety</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Piety</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Conduit/6th-Level Features</file_dpath>
    <item_id>your-story-ends-here-9-piety</item_id>
    <item_index>9</item_index>
    <item_name>Your Story Ends Here (9 Piety)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.conduit.6th-level-feature:your-story-ends-here-9-piety</scc>
    <scdc>1.1.1:5.1.2.3:09</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/conduit/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Intuition</roll>
      <t1>9 + I corruption damage; R &lt; WEAK, weakened (save ends)</t1>
      <t2>14 + I corruption damage; R &lt; AVERAGE, weakened (save ends)</t2>
      <t3>19 + I corruption damage; R &lt; STRONG, weakened (save ends)</t3>
    </effect>
    <effect type="mundane">If this damage kills the target, you and each ally within distance can spend a Recovery.</effect>
  </effects>
</ability>
