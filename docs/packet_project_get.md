## packet project get

Retrieves all available projects or a single project

### Synopsis

Example:

Retrieve all projects:
packet project get
  
Retrieve a specific project:
packet project get -i [project_UUID]

	

```
packet project get [flags]
```

### Options

```
  -h, --help                Help for get
  -j, --json                JSON output
  -i, --project-id string   UUID of the project
  -y, --yaml                YAML output
```

### Options inherited from parent commands

```
      --config string   Path to JSON or YAML configuration file (default "/Users/jasmingacic/.packet-cli.json")
```

### SEE ALSO

* [packet project](packet_project.md)	 - Project operations

###### Auto generated by spf13/cobra on 2-Jul-2018