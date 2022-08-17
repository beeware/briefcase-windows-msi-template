Briefcase Windows MSI Template
==============================

**NOTE: This template has been deprecated. Briefcase 0.3.9 deprecated the
``msi`` backend in favor of `app
<https://github.com/beeware/briefcase-windows-app-template>`__ and `Visual Studio
<https://github.com/beeware/briefcase-windows-VisualStudio-template>`__
backends.**

A `Cookiecutter <https://github.com/cookiecutter/cookiecutter/>`__ template for
building Python apps that will run under Windows, packaged as an MSI installer.

The easiest way to use this project is to not use it at all - at least, not
directly. `Briefcase <https://github.com/beeware/briefcase/>`__ is a tool that
uses this template, rolling it out using data extracted from a
``pyproject.toml`` configuration file.

The master branch of this repository has no content; there is an independent
branch for each supported version of Python. The following Python versions are
supported:

* `Python 3.7 <https://github.com/beeware/briefcase-windows-msi-template/tree/3.7>`__
* `Python 3.8 <https://github.com/beeware/briefcase-windows-msi-template/tree/3.8>`__
* `Python 3.9 <https://github.com/beeware/briefcase-windows-msi-template/tree/3.9>`__
* `Python 3.10 <https://github.com/beeware/briefcase-windows-msi-template/tree/3.10>`__

Suggestions for template changes should be made against the `dev branch
<https://github.com/beeware/briefcase-windows-msi-template/tree/dev>`__; these
will then be backported into the supported Python releases. The dev branch will
track the most recent supported version of Python (currently, Python 3.10).

See the individual branches for usage instructions.

The following versions were supported in the past, but are no longer maintained:

* `Python 3.5 <https://github.com/beeware/briefcase-windows-msi-template/tree/3.5>`__ (EOL October 2020)
* `Python 3.6 <https://github.com/beeware/briefcase-windows-msi-template/tree/3.6>`__ (EOL December 2021)
