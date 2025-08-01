<ability>
  <name>Witty Banter</name>
  <flavor>A lyrical (and physical) jab insults an enemy and inspires an ally.</flavor>
  <keywords>
    <keyword>Maigc</keyword>
    <keyword>Melee</keyword>
    <keyword>Ranged</keyword>
    <keyword>Strike</keyword>
  </keywords>
  <type>Main action</type>
  <distance>Melee 1 or ranged 5</distance>
  <target>One creature</target>
  <metadata>
    <class>troubadour</class>
    <feature_type>trait</feature_type>
    <file_dpath>Troubadour/1st-Level Features</file_dpath>
    <item_id>witty-banter</item_id>
    <item_index>14</item_index>
    <item_name>Witty Banter</item_name>
    <level>1</level>
    <scc>mcdm.heroes.v1:feature.trait.troubadour.1st-level-feature:witty-banter</scc>
    <scdc>1.1.1:9.1.3.1:14</scdc>
    <source>mcdm.heroes.v1</source>
    <type>feature/trait/troubadour/1st-level-feature</type>
  </metadata>
  <effects>
    <effect type="roll">
      <roll>Power Roll + Presence</roll>
      <t1>4 + P psychic damage</t1>
      <t2>5 + P psychic damage</t2>
      <t3>7 + P psychic damage</t3>
    </effect>
    <effect type="mundane">One ally within 10 squares of you can end one effect on them that is ended by a saving throw or that ends at the end of their turn.</effect>
    <effect type="mundane" cost="Spend 1 Drama">The chosen ally can spend a Recovery.</effect>
  </effects>
</ability>
