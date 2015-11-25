# linux-source-mp3-troll-
->Using a Linux distribution of version 3.19
->Kernel source modification
->GOAL: 
    -> Open up an mp3 file 
    -> chance to play a troll mp3 file (more times it opens up, higher the chance to troll)

-> To apply patch
  -> Replace fs/open.c in Linux source with selected version of open.c
  -> In Linux source directory, run:
      -> 'make bzImage'
      -> 'make modules'
      -> 'make modules_install'
      -> 'make install'
  -> Run 'shutdown -r now' to reboot machine on OpenStack
  -> In the bootloader, select the most recent install image
