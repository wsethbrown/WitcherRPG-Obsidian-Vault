---

database-plugin: basic

---

```yaml:dbfolder
name: Armor List
description: Lists all the armor in the game
columns:
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
    position: 1
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Description:
    input: text
    accessorKey: Description
    key: Description
    id: Description
    label: Description
    position: 12
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
      footer_type: none
      persist_changes: false
  Effects:
    input: tags
    accessorKey: Effects
    key: Effects
    id: Effects
    label: Effects
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Restricted Vision", backgroundColor: "hsl(56, 95%, 90%)"}
      - { label: "Full Cover", backgroundColor: "hsl(152, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Avail-:
    input: select
    accessorKey: Avail
    label: Avail.
    key: Avail
    id: avail.
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "C", backgroundColor: "hsl(128, 95%, 90%)"}
      - { label: "P", backgroundColor: "hsl(27, 95%, 90%)"}
      - { label: "E", backgroundColor: "hsl(49, 95%, 90%)"}
      - { label: "R", backgroundColor: "hsl(309, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Name:
    input: text
    accessorKey: Name
    label: Name
    key: Name
    id: name
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 233
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  SP:
    input: number
    accessorKey: SP
    label: SP
    key: SP
    id: sp
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    isSorted: false
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  AE:
    input: number
    accessorKey: AE
    label: AE
    key: AE
    id: ae
    position: 5
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
      footer_type: none
      persist_changes: false
  EV:
    input: number
    accessorKey: EV
    label: EV
    key: EV
    id: ev
    position: 7
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
      footer_type: none
      persist_changes: false
  Weight:
    input: number
    accessorKey: Weight
    label: Weight
    key: Weight
    id: weight
    position: 8
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
      footer_type: none
      persist_changes: false
  Category:
    input: select
    accessorKey: Category
    label: Category
    key: Category
    id: category
    position: 10
    skipPersist: false
    isHidden: false
    sortIndex: -1
    isSorted: false
    isSortedDesc: true
    options:
      - { label: "Heavy Armor", backgroundColor: "hsl(53, 95%, 90%)"}
      - { label: "Light Armor", backgroundColor: "hsl(267, 95%, 90%)"}
      - { label: "Medium Armor", backgroundColor: "hsl(275, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Location:
    input: select
    accessorKey: Location
    label: Location
    key: Location
    id: armor_location
    position: 11
    skipPersist: false
    isHidden: false
    sortIndex: 0
    isSorted: true
    isSortedDesc: false
    options:
      - { label: "Head", backgroundColor: "hsl(228, 95%, 90%)"}
      - { label: "Torso", backgroundColor: "hsl(93, 95%, 90%)"}
      - { label: "Legs", backgroundColor: "hsl(286, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Cost:
    input: number
    accessorKey: Cost
    label: Cost
    key: Cost
    id: price
    position: 9
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
      footer_type: none
      persist_changes: false
config:
  remove_field_when_delete_column: false
  cell_size: compact
  sticky_first_column: true
  group_folder_column: Location
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
  font_size: 16
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```