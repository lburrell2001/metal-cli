## metal project delete

Deletes a project

### Synopsis

Example:

metal project delete --id [project_UUID]



```
metal project delete [flags]
```

### Options

```
  -f, --force       Force removal of the project
  -h, --help        help for delete
  -i, --id string   Project ID (METAL_PROJECT_ID)
```

### Options inherited from parent commands

```
      --config string     Path to JSON or YAML configuration file
      --exclude strings   Comma seperated Href references to collapse in results, may be dotted three levels deep
      --include strings   Comma seperated Href references to expand in results, may be dotted three levels deep
  -o, --output string     Output format (*table, json, yaml)
      --search string     Search keyword for use in 'get' actions. Search is not supported by all resources.
      --token string      Metal API Token (METAL_AUTH_TOKEN)
```

### SEE ALSO

* [metal project](metal_project.md)	 - Project operations
