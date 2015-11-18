Ubuntu Core 14.04 for DevelBoard Blue
=====================================

---

__NOTE__: This repository contains binary artifacts. To make clones faster and save space we
may reset the history from time to time. *This might break "git pull"*.

---

This repository contains all binary files needed to create an Ubuntu Core 14.04 boot SD card that
runs on DevelBoard Blue. It is meant to be used with the `dboard` tool.

To get started run these commands in a terminal:

```sh
git clone https://github.com/DevelBoard/images-ubuntu-core.git
cd images-ubuntu-core
dboard makesd --mode=rw
```

Then follow the usual flashing process.
