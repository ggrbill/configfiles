configfiles
=======

This repository was created with
[configmanager](https://github.com/tarcisioe/configmanager)

Every branch except for master is extremely unreliable: they are
created for specific cases and may be rebased at any moment
against master.

If you clone this repository, it is recommended that you use it
to base your own configurations on, instead of always updating
from it. I might at any moment make changes you won't like.

Using these configurations
--------------------------

To install the configurations, enter the cloned repository and run:

*Note: this will overwrite any configuration files mapped by this
repository*

```bash
bash link.sh
bash migrate.sh
```

Using single files
------------------

To use a single configuration file or directory, use `use.sh`

```bash
bash use.sh goto.bash
bash use.sh bash_aliases
```

*Note: goto.bash must be sourced into .bashrc file*