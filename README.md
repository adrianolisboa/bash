[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/adrianolisboa)

## Bash Configurations

Some bash functions and configurations used daily on my shell interactions.

### How to load it?

To use add to your __.bash_profile__ this:

		BASH_LOAD_ROOT=/path/to/where/bash/project/is
		. ${BASH_LOAD_ROOT}/load_bash

Than `load_bash` takes care of loading all functions, aliases and etc. Every directory defined in  `load_bash` will be sourced recursively.

### Credits

This scripts and aliases are based on [mavcunha/bash](https://github.com/mavcunha/bash) and adapted to my own needs.
