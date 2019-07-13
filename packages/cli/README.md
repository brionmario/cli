# `cli`

Universal command line interface for easy scaffolding of frontend apps.

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/cli.svg)](https://npmjs.org/package/cli)
[![Downloads/week](https://img.shields.io/npm/dw/cli.svg)](https://npmjs.org/package/cli)
[![License](https://img.shields.io/npm/l/cli.svg)](https://github.com/frontly/cli/blob/master/package.json)

<!-- toc -->

- [Usage](#usage)
- [Commands](#commands)
  <!-- tocstop -->

## Usage

````
<!-- usage -->
```sh-session
$ npm install -g cli
$ frontly COMMAND
running command...
$ frontly (-v|--version|version)
cli/0.1.0 darwin-x64 node-v10.16.0
$ frontly --help [COMMAND]
USAGE
  $ frontly COMMAND
...
````

<!-- usagestop -->

# Commands

<!-- commands -->

- [`frontly hello [FILE]`](#frontly-hello-file)
- [`frontly help [COMMAND]`](#frontly-help-command)

## `frontly hello [FILE]`

describe the command here

```
USAGE
  $ frontly hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ frontly hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/frontly/cli/blob/v0.1.0/src/commands/hello.ts)_

## `frontly help [COMMAND]`

display help for frontly

```
USAGE
  $ frontly help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.0/src/commands/help.ts)_

<!-- commandsstop -->
