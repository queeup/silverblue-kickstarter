# My fedora silverblue kickstarter files

- [btrfs-ks.cfg](https://github.com/queeup/silverblue-kickstarter/blob/main/btrfs-ks.cfg)
  - Remount new created btrfs partition with compress level 3 before install and change default btrfs compress level on default fstab file.

- [personal-ks.cfg](https://github.com/queeup/silverblue-kickstarter/blob/main/personal-ks.cfg)
  - My personal install configuration.

Starting an installation via Kickstart:

- Interrupt the boot sequence by hitting a key and editing the first entry.

- Add `inst.ks=https://your.kickstart.url/path/to/ks.cfg` after `quite`

- In this case `inst.ks=https://raw.githubusercontent.com/queeup/silverblue-kickstarter/main/btrfs-ks.cfg`

  or short version:

  `inst.ks=https://tinyurl.com/btrfs-ks`
