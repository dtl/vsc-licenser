# Licenser
An extension for adding license headers and LICENSE file in your workspace.
You can find this extension on [Marketplace for VS Code](https://marketplace.visualstudio.com/items?itemName=ymotongpoo.licenser).

## Install

Launch your VS Code, open Quick Open box (Mod+P), and run following command.

```
ext install licenser
```

## Commands and features
This extension provides shortcut to insert license header to source code file and
to create LICENSE file based on the configuration in `settings.json`. This extenstion
not only provides shortcut but also enables auto-insertion of license header on creation
of new file. 

You can call these 2 commands via Command Palette. 
* "licenser: Create LICENSE file"
  * create LICENSE file into your repository.
* "licenser: Insert license header"
  * insert license header to currently opened source code files.

Programming languages supported in this extension are:
* Go
* C++
* C
* JavaScript
* TypeScript
* Java
* C#
* F#
* ShellScript
* Python
* Ruby
* Perl
* HTML
* XML
* CSS
* SCSS (Sass)
* Rust
* Swift
* Objective-C
* Dockerfile
* Makefile
* OCaml
* Erlang
* Groovy
* ini
* bat

Following programing languages will be supported as soon as their language ID
get available.
* LISP
* Haskell

## Configurations
### licenser.license

```
"licenser.license": "AL2"
```

Currently, supported licenses are:

* "AGPLv3": GNU Affero General Public License version 3
* "AL2": Apache License version 2
* "BSD2": BSD 2-clause License
* "BSD3": BSD 3-clause License (New BSD License)
* "GPLv2": GNU General Public License version 2
* "GPLv3": GNU General Public License version 3
* "LGPLv3": GNU Lesser General Public License version 3
* "MIT": MIT License
* "MPLv2": Mozilla Public License version 2

### licenser.author

```
"licenser.author": "Yoshi Yamaguchi"
```

This setting defines the author name that would be inserted into the
license header template.

### licenser.projectName

**This setting should be in Workspace settings**

```
"licenser.projectName": "Awesome project"
```

This setting defines the project name you are working on. This setting is only used in
the template for GPLv2 and GPLv3. Default value would be your workspace root directory name.
Be aware that this setting should be in Workspace setting, not in User setting, since
User setting affects all workspaces which are not relevant to this project name. 

### licenser.useSingleLineStyle

```
"licenser.useSingleLineStyle": true
```

This setting defines your preference of commentt style. If this setting is set as `true`,
licenser uses single line comment style for license header in case that the language has
single line comment style. If it is set as `true` but the language doesn't have single line comment style,
multi line comment will be applied.

## Call to action
### Report issues
Finally the author bought Windows 10 machine, and he can test the app by himself!
For bug reporting, please create a ticket on [GitHub repository](https://github.com/ymotongpoo/vsc-licenser/issues).

### Pull requests
This repository is mainly developed under 'develop' branch, so please make pull requests there, not to 'master' branch.

## Contributers
Thank you for contributions to "licenser".

* aodag
* Cologler
* jimmidyson
* marchrock

## Changelogs
See all changelogs in [CHANGELOG](https://github.com/ymotongpoo/vsc-licenser/blob/master/CHANGELOG.md).
