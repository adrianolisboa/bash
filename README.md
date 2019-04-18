[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/adrianolisboa)

## Bash Configurations

My OSX setup, some bash functions and configurations used daily on my shell interactions.

### How to Load It?

To use add to your __.bash_profile__ this:

		BASH_LOAD_ROOT=/path/to/where/bash/project/is
		. ${BASH_LOAD_ROOT}/load

Than `load` takes care of loading all functions, aliases and etc. Every directory defined in  `load` will be sourced recursively.

## OSX Setup

Just `cd` into osx-setup folder and run `./setup.sh`

### Credits

This scripts and aliases are based on [mavcunha/bash](https://github.com/mavcunha/bash) and adapted to my own needs.
