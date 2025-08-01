<ability>
  <metadata>
    <class>combat</class>
    <file_dpath>Abilities</file_dpath>
    <item_id>escape-grab</item_id>
    <item_index>8</item_index>
    <item_name>Escape Grab</item_name>
    <scc>mcdm.heroes.v1:common\_ability.maneuver:escape-grab</scc>
    <scdc>1.1.1:7.3:08</scdc>
    <source>mcdm.heroes.v1</source>
    <type>common\_ability/maneuver</type>
  </metadata>
  <effects>
    <effect type="mundane">A creature who is grabbed by another creature, an object, or an effect (see [Grab](#page-287-5) below) can attempt to escape by using the following ability.
###### Escape Grab
| **-**       | **Maneuver** |
| ----------- | -----------: |
| **📏 Self** |  **🎯 Self** |</effect>
    <effect type="roll">
      <roll>Power Roll + Might or Agility</roll>
      <t1>No effect.</t1>
      <t2>You can escape the grab, but if you do, a creature who has you grabbed can make a melee free strike against you before you are no longer grabbed.</t2>
      <t3>You are no longer grabbed.</t3>
    </effect>
    <effect type="mundane">You take a bane on this maneuver if your size is smaller than the size of the creature, object, or effect that has you grabbed.
See [Conditions](#page-91-2) in [Chapter 5: Classes](#page-83-2) for information on the grabbed condition.</effect>
  </effects>
</ability>
