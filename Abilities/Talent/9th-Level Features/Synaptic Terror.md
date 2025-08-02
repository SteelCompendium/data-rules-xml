<ability>
  <name>Synaptic Terror</name>
  <cost>11 Clarity</cost>
  <flavor>You project a terrifying image into the brains of your foes, and their fear psionically invigorates your allies.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Psionic</keyword>
    <keyword>Telepathy</keyword>
  </keywords>
  <type>Main action</type>
  <distance>3 burst</distance>
  <target>Each ally and enemy in the area</target>
  <metadata>
    <class>talent</class>
    <cost>11 Clarity</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/9th-Level Features</file_dpath>
    <item_id>synaptic-terror-11-clarity</item_id>
    <item_index>01</item_index>
    <item_name>Synaptic Terror (11 Clarity)</item_name>
    <level>9</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.9th-level-feature:synaptic-terror-11-clarity</scc>
    <scdc>1.1.1:14.2.1.7:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/9th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">You and each target ally can&apos;t obtain lower than a tier 2 outcome on power rolls until the start of your next turn. Each target enemy is affected by the ability&apos;s power roll.</effect>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>R &lt; WEAK, frightened (save ends)</t1>
      <t2>R &lt; AVERAGE, frightened (save ends)</t2>
      <t3>R &lt; STRONG, frightened (save ends)</t3>
    </effect>
    <effect type="mundane" name="Strained">You can&apos;t use this ability if doing so would cause you to have negative clarity.</effect>
  </effects>
</ability>
