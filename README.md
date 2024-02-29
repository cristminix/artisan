## Welcome to Web Artisan v0.0.0

### Available actions:

  ```
  createReactComponent  <name> <target_dir>
  createModelEntity  <table_name> <target_dir> [--schema] [--out-model-dir] [--out-entity-dir]
  createModelAPIRoute  <table_name> <target_dir> [json_path]
  createModelAPIRouteV2  <table_name> <target_dir> [json_path]
  listModelAPIRoutes  [json_path]
  createModuleAction  <actionName> <arguments> <desc> [json_path]
  sideMenu  [list|add|rm] [menu_key] [title] [path] [icon] [--json_path=side_menu.json]
  createSchemaDef  <table_name> <pk> <columns> <types> [nullables] [lengths] [validations] [--schema=model_entities.json]
  html2React  <input> <output> [-draft]
  createModelFormComponent  <table_name> <target_dir> <json_path>
  createModelGridComponent  <table_name> <target_dir> <json_path>
  extractPrelineExample  <input> <target_dir> [-draft]
  injectImportComponent  <source_component_path> <destination_component_path>
  
  ```

Powered by Malink Corporation Inc. 2023