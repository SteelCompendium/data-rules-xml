<ability>
  <name>Behold the Face of Justice!</name>
  <cost>5 Wrath</cost>
  <flavor>You attack a foe and your enemies behold a vision of the true nature of your resolve.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>Melee 1 or ranged 5</distance>
  <target>One creature</target>
  <metadata>
    <class>censor</class>
    <cost>5 Wrath</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Wrath</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Censor/1st-Level Features</file_dpath>
    <item_id>behold-the-face-of-justice-5-wrath</item_id>
    <item_index>04</item_index>
    <item_name>Behold the Face of Justice! (5 Wrath)</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.ability.censor.1st-level-feature:behold-the-face-of-justice-5-wrath</scc>
    <scdc>1.1.1:10.2.7.1:04</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/censor/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>3 + M holy damage; if the target has P &lt; WEAK, each enemy within 2 squares of them is frightened of you (save ends)</t1>
      <t2>5 + M holy damage; if the target has P &lt; AVERAGE, each enemy within 2 squares of them is frightened of you (save ends)</t2>
      <t3>8 + M holy damage; if the target has P &lt; STRONG, each enemy within 2 squares of them is frightened of you (save ends)</t3>
    </effect>
    <effect type="mundane">Each enemy frightened this way is pushed up to 2 squares away from the target and takes psychic damage equal to your Presence score.</effect>
  </effects>
</ability>
