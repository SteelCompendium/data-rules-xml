<ability>
  <metadata>
    <class>combat</class>
    <file_dpath>Abilities/Maneuvers</file_dpath>
    <item_id>grab</item_id>
    <item_index>10</item_index>
    <item_name>Grab</item_name>
    <scc>mcdm.heroes.v1:common\_ability.maneuver:grab</scc>
    <scdc>1.1.1:12.3:10</scdc>
    <source>mcdm.heroes.v1</source>
    <type>common\_ability/maneuver</type>
  </metadata>
  <effects>
    <effect type="mundane">A creature seeking to keep a foe close and locked down can attempt to grab a creature using the following ability.
###### Grab
| **Melee, Weapon** |        **Maneuver** |
| ----------------- | ------------------: |
| **📏 Melee 1**    | **🎯 One creature** |</effect>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>No effect.</t1>
      <t2>You can grab the target, but if you do, the target can make a melee free strike against you before they are grabbed.</t2>
      <t3>The target is grabbed by you.</t3>
    </effect>
    <effect type="mundane">You can usually target only creatures of your size or smaller. If your Might score is 2 or higher, you can target any creature with a size equal to or less than your Might score.
Unless otherwise indicated, a creature can grab only one creature at a time.
See [Conditions](#page-91-2) in [Chapter 5: Classes](#page-83-2) for information on the grabbed condition.</effect>
  </effects>
</ability>
