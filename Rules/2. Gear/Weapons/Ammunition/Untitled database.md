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
    position: 2
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
  Type:
    input: select
    accessorKey: Type
    key: Type
    id: Type
    label: Type
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "P", backgroundColor: "hsl(264, 95%, 90%)"}
      - { label: "B", backgroundColor: "hsl(333, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Avail.:
    input: select
    accessorKey: Avail.
    key: Avail.
    id: Avail.
    label: Avail.
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "E", backgroundColor: "hsl(181, 95%, 90%)"}
      - { label: "C", backgroundColor: "hsl(351, 95%, 90%)"}
      - { label: "R", backgroundColor: "hsl(64, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Rel.:
    input: text
    accessorKey: Rel.
    key: Rel.
    id: Rel.
    label: Rel.
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
  Effect:
    input: tags
    accessorKey: Effect
    key: Effect
    id: Effect
    label: Effect
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Non-Lethal", backgroundColor: "hsl(164, 95%, 90%)"}
      - { label: "Bleeding (100%)", backgroundColor: "hsl(308, 95%, 90%)"}
      - { label: "Armor Piercing", backgroundColor: "hsl(284, 95%, 90%)"}
      - { label: "Ablating", backgroundColor: "hsl(355, 95%, 90%)"}
      - { label: "See Side Bar", backgroundColor: "hsl(211, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Conc.:
    input: select
    accessorKey: Conc.
    key: Conc.
    id: Conc.
    label: Conc.
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "L", backgroundColor: "hsl(36, 95%, 90%)"}
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
    input: text
    accessorKey: Weight
    key: Weight
    id: Weight
    label: Weight
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
  Cost:
    input: text
    accessorKey: Cost
    key: Cost
    id: Cost
    label: Cost
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
  cell_size: normal
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
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
  pagination_size: 10
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