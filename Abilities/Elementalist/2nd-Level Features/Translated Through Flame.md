<ability>
  <name>Translated Through Flame</name>
  <cost>5 Essence</cost>
  <flavor>Your ally disappears, then reappears in a burst of fire.</flavor>
  <keywords>
    <keyword>Fire</keyword>
    <keyword>Magic</keyword>
    <keyword>Ranged</keyword>
    <keyword>Void</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Ranged 10</distance>
  <target>Self or one ally</target>
  <metadata>
    <class>elementalist</class>
    <cost>5 Essence</cost>
    <cost_amount>5</cost_amount>
    <cost_resource>Essence</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Elementalist/2nd-Level Features</file_dpath>
    <item_id>translated-through-flame-5-essence</item_id>
    <item_index>01</item_index>
    <item_name>Translated Through Flame (5 Essence)</item_name>
    <level>2</level>
    <scc>mcdm.heroes.v1:feature.ability.elementalist.2nd-level-feature:translated-through-flame-5-essence</scc>
    <scdc>1.1.1:10.2.9.5:01</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/elementalist/2nd-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">The target is teleported to another space within distance. Make a power roll that affects each enemy adjacent to the target&apos;s new space.</effect>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>3 fire damage</t1>
      <t2>5 fire damage</t2>
      <t3>8 fire damage</t3>
    </effect>
    <effect type="mundane">###### Volcano&apos;s Embrace (5 Essence)
*Wrap them up in fire and melting stone.*
| **Earth, Fire, Magic, Ranged, Strike** |     **Main action** |
| -------------------------------------- | ------------------: |
| **📏 Ranged 10**                       | **🎯 One creature** |</effect>
    <effect type="roll">
      <roll>Power Roll + Reason</roll>
      <t1>5 + R fire damage; A &lt; WEAK, restrained (save ends)</t1>
      <t2>9 + R fire damage; A &lt; AVERAGE, restrained (save ends)</t2>
      <t3>12 + R fire damage; A &lt; STRONG, restrained (save ends)</t3>
    </effect>
  </effects>
</ability>
