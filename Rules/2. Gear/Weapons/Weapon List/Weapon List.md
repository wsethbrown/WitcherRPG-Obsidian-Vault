---

database-plugin: basic

---

```yaml:dbfolder
name: new database
description: new description
columns:
  column1:
    input: text
    key: column1
    accessorKey: column1
    label: Name
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: 1
    isSorted: true
    isSortedDesc: false
    config:
      enable_media_view: true
      media_width: 100
      media_height: 100
      isInline: false
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 2
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
  Type:
    input: select
    accessorKey: Type
    key: Type
    id: Type
    label: Type
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 94
    options:
      - { label: "S/P", backgroundColor: "hsl(260, 95%, 90%)"}
      - { label: "S", backgroundColor: "hsl(210, 95%, 90%)"}
      - { label: "B", backgroundColor: "hsl(302, 95%, 90%)"}
      - { label: "P/B", backgroundColor: "hsl(155, 95%, 90%)"}
      - { label: "S/P/B", backgroundColor: "hsl(92, 95%, 90%)"}
      - { label: "P", backgroundColor: "hsl(112, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  WA:
    input: text
    accessorKey: WA
    key: WA
    id: WA
    label: WA
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 85
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  Avail.:
    input: select
    accessorKey: Avail.
    key: Avail.
    id: Avail.
    label: Avail.
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 122
    options:
      - { label: "E", backgroundColor: "hsl(64, 95%, 90%)"}
      - { label: "C", backgroundColor: "hsl(213, 95%, 90%)"}
      - { label: "P", backgroundColor: "hsl(321, 95%, 90%)"}
      - { label: "R", backgroundColor: "hsl(286, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  DMG:
    input: text
    accessorKey: DMG
    key: DMG
    id: DMG
    label: DMG
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 103
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  Rel.:
    input: text
    accessorKey: Rel.
    key: Rel.
    id: Rel.
    label: Rel.
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 76
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  Hands:
    input: text
    accessorKey: Hands
    key: Hands
    id: Hands
    label: Hands
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 101
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  RNG:
    input: text
    accessorKey: RNG
    key: RNG
    id: RNG
    label: RNG
    position: 10
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 97
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  Effect:
    input: tags
    accessorKey: Effect
    key: Effect
    id: Effect
    label: Effect
    position: 11
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 303
    options:
      - { label: "Bleeding (25%)", backgroundColor: "hsl(75, 95%, 90%)"}
      - { label: "Balanced", backgroundColor: "hsl(133, 95%, 90%)"}
      - { label: "Bleeding (50%)", backgroundColor: "hsl(234, 95%, 90%)"}
      - { label: "Ablating", backgroundColor: "hsl(233, 95%, 90%)"}
      - { label: "Concealment", backgroundColor: "hsl(297, 95%, 90%)"}
      - { label: "Armor Piercing", backgroundColor: "hsl(262, 95%, 90%)"}
      - { label: "Brawling", backgroundColor: "hsl(179, 95%, 90%)"}
      - { label: "Stun (-2)", backgroundColor: "hsl(215, 95%, 90%)"}
      - { label: "Meteorite", backgroundColor: "hsl(313, 95%, 90%)"}
      - { label: "Long Reach", backgroundColor: "hsl(228, 95%, 90%)"}
      - { label: "Focus (1)", backgroundColor: "hsl(247, 95%, 90%)"}
      - { label: "Grappling", backgroundColor: "hsl(330, 95%, 90%)"}
      - { label: "Focus (2)", backgroundColor: "hsl(149, 95%, 90%)"}
      - { label: "Focus (3)", backgroundColor: "hsl(239, 95%, 90%)"}
      - { label: "Greater Focus", backgroundColor: "hsl(252, 95%, 90%)"}
      - { label: "Slow Reload", backgroundColor: "hsl(73, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  Conc.:
    input: select
    accessorKey: Conc.
    key: Conc.
    id: Conc.
    label: Conc.
    position: 12
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 94
    options:
      - { label: "L", backgroundColor: "hsl(161, 95%, 90%)"}
      - { label: "N/A", backgroundColor: "hsl(305, 95%, 90%)"}
      - { label: "S", backgroundColor: "hsl(274, 95%, 90%)"}
      - { label: "T", backgroundColor: "hsl(170, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  EN:
    input: text
    accessorKey: EN
    key: EN
    id: EN
    label: EN
    position: 13
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 110
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  Weight:
    input: text
    accessorKey: Weight
    key: Weight
    id: Weight
    label: Weight
    position: 14
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 109
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  Cost:
    input: text
    accessorKey: Cost
    key: Cost
    id: Cost
    label: Cost
    position: 15
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 97
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  Category:
    input: select
    accessorKey: Category
    key: Category
    id: Category
    label: Category
    position: 16
    skipPersist: false
    isHidden: false
    sortIndex: 2
    isSorted: true
    isSortedDesc: false
    options:
      - { label: "Swords", backgroundColor: "hsl(148, 95%, 90%)"}
      - { label: "Small Blades", backgroundColor: "hsl(100, 95%, 90%)"}
      - { label: "Axes", backgroundColor: "hsl(195, 95%, 90%)"}
      - { label: "Bludgeons", backgroundColor: "hsl(236, 95%, 90%)"}
      - { label: "Pole Arms", backgroundColor: "hsl(95, 95%, 90%)"}
      - { label: "Staves", backgroundColor: "hsl(332, 95%, 90%)"}
      - { label: "Throwing Weapons", backgroundColor: "hsl(15, 95%, 90%)"}
      - { label: "Bows", backgroundColor: "hsl(0, 95%, 90%)"}
      - { label: "Crossbows", backgroundColor: "hsl(44, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
  Description:
    input: text
    accessorKey: Description
    key: Description
    id: Description
    label: Description
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
config:
  remove_field_when_delete_column: false
  cell_size: compact
  sticky_first_column: true
  group_folder_column: Category
  remove_empty_folders: false
  automatically_group_files: true
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  source_data: current_folder
  source_form_result: root
  source_destination_path: /
  frontmatter_quote_wrap: false
  row_templates_folder: /
  current_row_template: 
  pagination_size: 50
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: top
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
filters:
  enabled: false
  conditions:
```