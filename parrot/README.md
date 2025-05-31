# Parrot OS Default Repositories

Default `sources.list` for Parrot Security OS.

## Configuration and custom setup

The APT package manager uses ```/etc/apt/sources.list``` and any .list file found in the ```/etc/apt/sources.list.d/``` directory.

```/etc/apt/sources.list``` is EMPTY and the default APT configuration is located at ```/etc/apt/sources.list.d/parrot.list```

## Content of /etc/apt/sources.list.d/parrot.list

```plaintext
deb https://deb.parrot.sh/parrot lory main contrib non-free non-free-firmware
deb https://deb.parrot.sh/parrot lory-security main contrib non-free non-free-firmware
deb https://deb.parrot.sh/parrot lory-backports main contrib non-free non-free-firmware
#deb-src https://deb.parrot.sh/parrot lory main contrib non-free non-free-firmware
#deb-src https://deb.parrot.sh/parrot lory-security main contrib non-free non-free-firmware
#deb-src https://deb.parrot.sh/parrot lory-backports main contrib non-free non-free-firmware
```

## Updates/Testing purpose

The 'parrot-updates' repository provides updates before they are made available to 'parrot'. This repo is mostly meant to be used by developers and beta testers to extensively test updates before they are migrated to the main repository.

We suggest to not enable it, as it may introduce untested bugs and make the system unstable. Updates are delivered as fast as possible (within a week), so you are not missing anything important with this disabled (unless you are a dev):

```plaintext
deb https://deb.parrot.sh/parrot lory-updates main contrib non-free non-free-firmware
```
