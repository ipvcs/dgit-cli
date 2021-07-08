dgit-cli
========



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/dgit-cli.svg)](https://npmjs.org/package/dgit-cli)
[![Downloads/week](https://img.shields.io/npm/dw/dgit-cli.svg)](https://npmjs.org/package/dgit-cli)
[![License](https://img.shields.io/npm/l/dgit-cli.svg)](https://github.com/fluidi-beep/dgit-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g dgit-cli
$ dgit-cli COMMAND
running command...
$ dgit-cli (-v|--version|version)
dgit-cli/0.0.0 win32-x64 node-v16.4.0
$ dgit-cli --help [COMMAND]
USAGE
  $ dgit-cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`dgit-cli hello [FILE]`](#dgit-cli-hello-file)
* [`dgit-cli help [COMMAND]`](#dgit-cli-help-command)

## `dgit-cli hello [FILE]`

describe the command here

```
USAGE
  $ dgit-cli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ dgit-cli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/fluidi-beep/dgit-cli/blob/v0.0.0/src/commands/hello.ts)_

## `dgit-cli help [COMMAND]`

display help for dgit-cli

```
USAGE
  $ dgit-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_
<!-- commandsstop -->
