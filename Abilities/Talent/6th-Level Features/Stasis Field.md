<ability>
  <name>Stasis Field</name>
  <cost>9 Clarity</cost>
  <flavor>Keep everything as it was. Ignore everything that will be.</flavor>
  <keywords>
    <keyword>Area</keyword>
    <keyword>Chronopathy</keyword>
    <keyword>Psionic</keyword>
    <keyword>Ranged</keyword>
  </keywords>
  <type>Main Action</type>
  <distance>4 cube within 10</distance>
  <target>Each creature and object in the area</target>
  <metadata>
    <class>talent</class>
    <cost>9 Clarity</cost>
    <cost_amount>9</cost_amount>
    <cost_resource>Clarity</cost_resource>
    <feature_type>ability</feature_type>
    <file_dpath>Talent/6th-Level Features</file_dpath>
    <item_id>stasis-field-9-clarity</item_id>
    <item_index>9</item_index>
    <item_name>Stasis Field (9 Clarity)</item_name>
    <level>6</level>
    <scc>mcdm.heroes.v1:feature.ability.talent.6th-level-feature:stasis-field-9-clarity</scc>
    <scdc>1.1.1:7.2.1.3:09</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/ability/talent/6th-level-feature</type>
  </metadata>
  <effects>
    <effect type="mundane">The area is frozen in time until the start of your next turn. Each object in the area is restrained and can&apos;t fall until the effect ends. Until the effect ends, creatures in the area who are reduced to 0 Stamina or would die stay alive, and objects in the area that are reduced to 0 Stamina remain undestroyed. Make a power roll that targets each enemy in the area.</effect>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>P &lt; WEAK, the target is slowed until the effect ends</t1>
      <t2>P &lt; AVERAGE, the target&apos;s speed is 0 until the effect ends</t2>
      <t3>P &lt; STRONG, the target is restrained until the effect ends</t3>
    </effect>
    <effect type="mundane" name="Strained">Any creature or object force moved in the area takes 2 corruption damage for each square of the area they enter. Creatures and objects restrained in the area can be force moved. You are restrained until the effect ends.</effect>
  </effects>
</ability>
