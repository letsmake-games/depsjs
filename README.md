# depsjs

A dependency management tool written in nodejs.

## Requirements
- node version v12.13.0 or better

```
depsjs <cmd> [args]

Commands:
  deps install            installs dependencies as described in the provided
                          config file
  deps add [name] [repo]  adds and installs a new dependency to the project
  deps patch [name]       creates a new patch in the dependency with name using
                          project configuration provided

Options:
  --version  Show version number                                       [boolean]
  --help     Show help                                                 [boolean]

```

