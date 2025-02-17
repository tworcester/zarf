## zarf completion bash

Generate the autocompletion script for bash

### Synopsis

Generate the autocompletion script for the bash shell.

This script depends on the 'bash-completion' package.
If it is not installed already, you can install it via your OS's package manager.

To load completions in your current shell session:

	source <(zarf completion bash)

To load completions for every new session, execute once:

#### Linux:

	zarf completion bash > /etc/bash_completion.d/zarf

#### macOS:

	zarf completion bash > $(brew --prefix)/etc/bash_completion.d/zarf

You will need to start a new shell for this setup to take effect.


```
zarf completion bash
```

### Options

```
  -h, --help              help for bash
      --no-descriptions   disable completion descriptions
```

### Options inherited from parent commands

```
  -a, --architecture string   Architecture for OCI images
  -l, --log-level string      Log level when running Zarf. Valid options are: warn, info, debug, trace
      --no-progress           Disable fancy UI progress bars, spinners, logos, etc.
```

### SEE ALSO

* [zarf completion](zarf_completion.md)	 - Generate the autocompletion script for the specified shell

