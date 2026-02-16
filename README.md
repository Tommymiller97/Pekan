{
  "$schema": "https://json.schemastore.org/schema-catalog.json",
  "version": 1,
  "schemas": [
    {
      "name": "Upsun config",
      "description": "Upsun configuration file",
      "fileMatch": ["**/.upsun/*.yml", "**/.upsun/*.yaml"],
      "url": "https://raw.githubusercontent.com/platformsh/platformify/refs/heads/main/validator/schema/upsun.json"
    },
    {
      "name": "Platform.sh application",
      "description": "Platform.sh application configuration file",
      "fileMatch": [
        ".platform.app.yml",
        ".platform.app.yaml",
        "**/.platform.app.yml"
      ],
      "url": "https://raw.githubusercontent.com/platformsh/platformify/refs/heads/main/validator/schema/platformsh.application.json"
    },
    {
      "name": "Platform.sh routes",
      "description": "Platform.sh routes configuration file",
      "fileMatch": ["**/.platform/routes.yml", "**/.platform/routes.yaml"],
      "url": "https://raw.githubusercontent.com/platformsh/platformify/refs/heads/main/validator/schema/platformsh.routes.json"
    },
    {
      "name": "Platform.sh services",
      "description": "Platform.sh services configuration file",
      "fileMatch"
