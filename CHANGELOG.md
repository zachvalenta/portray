Install the latest
===================

To install the latest version of portray simply run:

`pip3 install portray`

OR

`poetry add portray`

OR

`pipenv install portray`

see the [Installation QuickStart](https://timothycrosley.github.io/portray/docs/quick_start/1.-installation/) for more instructions.

Changelog
=========

## 1.1.0 - August 29
Minor Feature release w/ Bug Fixes

- Added support for specifying modules directly from the CLI and API.
- Added auto module detect for simple setup.py files.
- Improved CLI subcommand documentation.
- Implemented [Issue 12](https://github.com/timothycrosley/portray/issues/12) - Clarify what a "project" is in documentation.
- Fixed [Issue 2](https://github.com/timothycrosley/portray/issues/2) - UnicodeEncodeError except when running portray.
- Fixed [Issue 10](https://github.com/timothycrosley/portray/issues/10) - Class methods rendered incorrectly.
- Fixed [Issue 17](https://github.com/timothycrosley/portray/issues/17) - Portray silently requires README.md file.

## 1.0.5 - August 26 PM
Bug fix release

- Fixed [Issue 6](https://github.com/timothycrosley/portray/issues/6) - Failed to open web-browser on startup.
- Fixed [Issue 5](https://github.com/timothycrosley/portray/issues/5) - Some links are missing a trailing slash.
- Fixed [Issue 4](https://github.com/timothycrosley/portray/issues/4) - Class references generate large code block.

Big thanks to Marcel Hellkamp ([@defnull](https://github.com/defnull)) for fixing these issues.

## 1.0.0 - August 26 AM
Initial API stable release of portray
