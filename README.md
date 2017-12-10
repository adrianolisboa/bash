## Bash Configurations

Some bash functions and configurations used daily on my shell interactions.
It's based on [mavcunha/bash](https://github.com/mavcunha/bash) and adapted to my own use.

### How to load the functions and aliases?

In order to keep the files in another place other than my home directory I load
all scripts with `load_bash`, note that `BASH_LOAD_ROOT` is a variable that needs
to be called this way since it's used in other places.

To use add to your home __.bash_profile__ this:

		BASH_LOAD_ROOT=/path/to/where/bash/project/is
		. ${BASH_LOAD_ROOT}/load_bash

Than `load_bash` takes care of loading all scripts, aliases and etc. Mind that
every directory defined in  `load_bash` will be sourced recursively.
