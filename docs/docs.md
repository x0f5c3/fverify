# fverify

## Usage
> This cli template shows the date and time in the terminal

fverify

## Flags
|Flag|Usage|
|----|-----|
|`--debug`|enable debug messages|
|`--disable-update-checks`|disables update checks|
|`--raw`|print unstyled raw output (set it if output is written to a file)|

## Commands
|Command|Usage|
|-------|-----|
|`fverify completion`|Generate the autocompletion script for the specified shell|
|`fverify date`|Prints the current date.|
|`fverify help`|Help about any command|
|`fverify time`|Prints the current time|
# ... completion
`fverify completion`

## Usage
> Generate the autocompletion script for the specified shell

fverify completion

## Description

```
Generate the autocompletion script for fverify for the specified shell.
See each sub-command's help for details on how to use the generated script.

```

## Commands
|Command|Usage|
|-------|-----|
|`fverify completion bash`|Generate the autocompletion script for bash|
|`fverify completion fish`|Generate the autocompletion script for fish|
|`fverify completion powershell`|Generate the autocompletion script for powershell|
|`fverify completion zsh`|Generate the autocompletion script for zsh|
# ... completion bash
`fverify completion bash`

## Usage
> Generate the autocompletion script for bash

fverify completion bash

## Description

```
Generate the autocompletion script for the bash shell.

This script depends on the 'bash-completion' package.
If it is not installed already, you can install it via your OS's package manager.

To load completions in your current shell session:

	source <(fverify completion bash)

To load completions for every new session, execute once:

#### Linux:

	fverify completion bash > /etc/bash_completion.d/fverify

#### macOS:

	fverify completion bash > $(brew --prefix)/etc/bash_completion.d/fverify

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion fish
`fverify completion fish`

## Usage
> Generate the autocompletion script for fish

fverify completion fish

## Description

```
Generate the autocompletion script for the fish shell.

To load completions in your current shell session:

	fverify completion fish | source

To load completions for every new session, execute once:

	fverify completion fish > ~/.config/fish/completions/fverify.fish

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion powershell
`fverify completion powershell`

## Usage
> Generate the autocompletion script for powershell

fverify completion powershell

## Description

```
Generate the autocompletion script for powershell.

To load completions in your current shell session:

	fverify completion powershell | Out-String | Invoke-Expression

To load completions for every new session, add the output of the above command
to your powershell profile.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion zsh
`fverify completion zsh`

## Usage
> Generate the autocompletion script for zsh

fverify completion zsh

## Description

```
Generate the autocompletion script for the zsh shell.

If shell completion is not already enabled in your environment you will need
to enable it.  You can execute the following once:

	echo "autoload -U compinit; compinit" >> ~/.zshrc

To load completions in your current shell session:

	source <(fverify completion zsh)

To load completions for every new session, execute once:

#### Linux:

	fverify completion zsh > "${fpath[1]}/_fverify"

#### macOS:

	fverify completion zsh > $(brew --prefix)/share/zsh/site-functions/_fverify

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... date
`fverify date`

## Usage
> Prints the current date.

fverify date

## Flags
|Flag|Usage|
|----|-----|
|`-f, --format string`|specify a custom date format (default "02 Jan 06")|
# ... help
`fverify help`

## Usage
> Help about any command

fverify help [command]

## Description

```
Help provides help for any command in the application.
Simply type fverify help [path to command] for full details.
```
# ... time
`fverify time`

## Usage
> Prints the current time

fverify time

## Description

```
You can print a live clock with the '--live' flag!
```

## Flags
|Flag|Usage|
|----|-----|
|`-l, --live`|live output|


---
> **Documentation automatically generated with [PTerm](https://github.com/pterm/cli-template) on 05 November 2023**
