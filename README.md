# Hashicorp Schemas
Hashicorp schemas and unofficial specs for payload validation and autocompletion.  These can be used within IDEs for autocompletion or within web frameworks like json-editor.

For VS Code, configure json schemas in the settings.json file:
```
{
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "window.zoomLevel": -1,
    "explorer.confirmDelete": false,
    "terminal.integrated.fontFamily": "Menlo for Powerline",
    "go.formatTool": "goimports",
    "go.useLanguageServer": true,
    "debug.onTaskErrors": "debugAnyway",
    "json.schemas": [
        {
            "fileMatch": [
                "./job/*.json"
            ],
            "url": "https://github.com/jboero/hashicorp-schemas/raw/master/JSON/nomad/1.11/job.json"
        }
    ],
}
```
