<ability>
  <name>Soul Burn</name>
  <cost>7 Clarity</cost>
  <flavor>You blast their soul out of their body, leaving it to helplessly float back to a weakened husk.</flavor>
  <keywords>
    <keyword>Animapathy</keyword>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>One creature</target>
  <metadata>
    <class>talent</class>
    <cost>7 Clarity</cost>
    <cost_amount>7</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/3rd-Level Features</file_dpath>
    <item_id>soul-burn-7-clarity</item_id>
    <item_index>02</item_index>
    <item_name>Soul Burn (7 Clarity)</item_name>
    <level>3</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.3rd-level-feature:soul-burn-7-clarity</scc>
    <scdc>1.1.1:9.2.1.6:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/3rd-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>6 + P damage; P &lt; WEAK, dazed (save ends)</t1>
      <t2>10 + P damage; P &lt; AVERAGE, dazed (save ends)</t2>
      <t3>14 + P damage; P &lt; STRONG, dazed (save ends)</t3>
    </effect>
    <effect type="mundane">The target takes a bane on Presence tests until the end of the encounter.</effect>
    <effect type="mundane" name="Strained">The potency of this ability increases by 1. You take 2d6 damage and gain 3 surges that you can use immediately.</effect>
  </effects>
</ability>
