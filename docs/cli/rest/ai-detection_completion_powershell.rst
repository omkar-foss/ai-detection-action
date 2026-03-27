.. _ai-detection_completion_powershell:

ai-detection completion powershell
----------------------------------

Generate the autocompletion script for powershell

Synopsis
~~~~~~~~


Generate the autocompletion script for powershell.

To load completions in your current shell session:

	ai-detection completion powershell | Out-String | Invoke-Expression

To load completions for every new session, add the output of the above command
to your powershell profile.


::

  ai-detection completion powershell [flags]

Options
~~~~~~~

::

  -h, --help              help for powershell
      --no-descriptions   disable completion descriptions

SEE ALSO
~~~~~~~~

* `ai-detection completion <ai-detection_completion.rst>`_ 	 - Generate the autocompletion script for the specified shell

