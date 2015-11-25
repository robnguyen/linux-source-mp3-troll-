# linux-source-mp3-troll- <br />
->Using a Linux distribution of version 3.19 <br />
->Kernel source modification <br />
->GOAL: <br />
    -> Open up an mp3 file <br /> 
    -> chance to play a troll mp3 file (more times it opens up, higher the chance to troll) <br />

-> To apply patch <br />
  -> Replace fs/open.c in Linux source with selected version of open.c <br />
  -> In Linux source directory, run: <br />
      -> 'make bzImage' <br />
      -> 'make modules' <br />
      -> 'make modules_install' <br />
      -> 'make install' <br />
  -> Run 'shutdown -r now' to reboot machine on OpenStack <br />
  -> In the bootloader, select the most recent install image <br />
