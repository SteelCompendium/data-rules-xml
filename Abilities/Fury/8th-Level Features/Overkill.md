<ability>
  <name>Overkill</name>
  <cost>11 Ferocity</cost>
  <flavor>You strike so no damage is wasted.</flavor>
  <keywords>
    <keyword>Magic</keyword>
    <keyword>Melee</keyword>
    <keyword>Strike</keyword>
    <keyword>Weapon</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1</distance>
  <target>One creature</target>
  <metadata>
    <class>fury</class>
    <cost>11 Ferocity</cost>
    <cost_amount>11</cost_amount>
    <cost_resource>Ferocity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Fury/8th-Level Features</file_dpath>
    <item_id>overkill-11-ferocity</item_id>
    <item_index>02</item_index>
    <item_name>Overkill (11 Ferocity)</item_name>
    <level>8</level>
    <scc>mcdm.heroes.v1:feature.ability.fury.8th-level-feature:overkill-11-ferocity</scc>
    <scdc>1.1.1:14.2.5.2:02</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/fury/8th-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Might</roll>
      <t1>6 + M damage</t1>
      <t2>10 + M damage</t2>
      <t3>14 + M damage</t3>
    </effect>
    <effect type="mundane">If the target is a minion or is winded but isn&apos;t a leader or solo creature, they are reduced to 0 Stamina before this ability&apos;s damage is dealt. If the target is killed by this damage, you can deal any damage over what was required to kill them to another creature within 5 squares of the target.</effect>
  </effects>
</ability>
