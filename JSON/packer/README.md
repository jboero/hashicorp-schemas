# Hashicorp Schemas - Packer
Hashicorp schemas and unofficial specs for payload validation and autocompletion.  You can use this within VS Code like the example below.  Just ensure you define the "$schema" property in a new JSON file.

Note that some objects have a "requires" property which helpfully tells you when some missing attributes are required.  Unfortunately in VS Code autocompletion the validation on new objects fails as they don't contain the required properties.  Sometimes you won't find the object in your "type" autocompletion list.  Just type it anyway and Code will figure out the schema after you do.

```
{
    "$schema": "https://github.com/jboero/hashicorp-schemas/raw/master/JSON/packer/1.5/manifest.json",
    [CTRL-SPACE]
}
```
![VS Code Packer Demo](/content/packer.gif)
