coder-cli
=========



[![Version](https://img.shields.io/npm/v/coder-cli.svg)](https://npmjs.org/package/coder-cli)
[![CircleCI](https://circleci.com/gh/caiya/coder-cli/tree/master.svg?style=shield)](https://circleci.com/gh/caiya/coder-cli/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/caiya/coder-cli?branch=master&svg=true)](https://ci.appveyor.com/project/caiya/coder-cli/branch/master)
[![Codecov](https://codecov.io/gh/caiya/coder-cli/branch/master/graph/badge.svg)](https://codecov.io/gh/caiya/coder-cli)
[![Downloads/week](https://img.shields.io/npm/dw/coder-cli.svg)](https://npmjs.org/package/coder-cli)
[![License](https://img.shields.io/npm/l/coder-cli.svg)](https://github.com/caiya/coder-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g coder-cli
$ coder-cli COMMAND
running command...
$ coder-cli (-v|--version|version)
coder-cli/0.0.0 win32-x64 node-v8.9.3
$ coder-cli --help [COMMAND]
USAGE
  $ coder-cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [coder-cli hello [FILE]](#coder-cli-hello-file)
* [coder-cli help [COMMAND]](#coder-cli-help-command)

## coder-cli hello [FILE]

describe the command here

```
USAGE
  $ coder-cli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ coder-cli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/caiya/coder-cli/blob/v0.0.0/src/commands/hello.ts)_

## coder-cli help [COMMAND]

display help for coder-cli

```
USAGE
  $ coder-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v1.2.4/src/commands/help.ts)_
<!-- commandsstop -->
