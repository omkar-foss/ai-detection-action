.. _ai-detection_docs:

ai-detection docs
-----------------

Build docs in markdown, manpages, rest formats

Synopsis
~~~~~~~~


Build docs in markdown, manpages, rest formats

::

  ai-detection docs [flags]

Examples
~~~~~~~~

::

    # simply build markdown docs at default output dir (./docs/cli)
    ai-detection-action docs

    # build rest docs at default output dir
    ai-detection-action docs --format rest

    # build manpages docs at a specific 'documentation' dir
    ai-detection-action docs --format manpages --out ./documentation

Options
~~~~~~~

::

      --format string   markdown|manpages|rest (default "markdown")
  -h, --help            help for docs
      --out string      output directory (default "./docs/cli")

SEE ALSO
~~~~~~~~

* `ai-detection <ai-detection.rst>`_ 	 - Detect AI-generated contributions

