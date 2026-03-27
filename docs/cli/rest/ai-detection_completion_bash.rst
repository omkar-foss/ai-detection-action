.. _ai-detection_completion_bash:

ai-detection completion bash
----------------------------

Generate the autocompletion script for bash

Synopsis
~~~~~~~~


Generate the autocompletion script for the bash shell.

This script depends on the 'bash-completion' package.
If it is not installed already, you can install it via your OS's package manager.

To load completions in your current shell session:

	source <(ai-detection completion bash)

To load completions for every new session, execute once:

#### Linux:

	ai-detection completion bash > /etc/bash_completion.d/ai-detection

#### macOS:

	ai-detection completion bash > $(brew --prefix)/etc/bash_completion.d/ai-detection

You will need to start a new shell for this setup to take effect.


::

  ai-detection completion bash

Options
~~~~~~~

::

  -h, --help              help for bash
      --no-descriptions   disable completion descriptions

SEE ALSO
~~~~~~~~

* `ai-detection completion <ai-detection_completion.rst>`_ 	 - Generate the autocompletion script for the specified shell

