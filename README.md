# linux-rock-daw

**OS**
- Endeavour OS
- Pipewire, Jack
- Focusrite Scarlett 18i8 2nd Gen

**DAW**
- Cockos Reaper 7

**Pipewire GUI**
- pacman -S gpwgraph
- connect interface inputs/ouputs to Reaper

**Scarlett GUI**
- yay -S alsa-scarlett-gui
- create /etc/modprobe.d/scarlett.conf
- https://github.com/geoffreybennett/alsa-scarlett-gui/blob/master/INSTALL.md

**Jack Latency**
- QjackCtl

**Plugin recommendations**
- LSP Plugin suite


**Instrument recommendations**
- SFizz Sampler (https://archlinux.org/packages/extra/x86_64/sfizz-lv2/)
- X42 AVL-drums (multi output)

**SFZ-Libraries**
- Standard Bass v2
- https://www.kvraudio.com/forum/viewtopic.php?t=517060
- Black & Blue Bass
- https://shop.karoryfer.com/pages/free-black-and-blue-basses


**Neural Amp Modeler**
- https://github.com/mikeoliphant/neural-amp-modeler-lv2
- Profiles: tonehunt.org

**WINE**
- sudo pacman -S wine-staging
- install yabridge
- install winetricks

**NATIVE INSTRUMENTS**
- open winetricks, set flag windows 10
- download legacy native access installer v 1.14
- install NA
- download files, install fails
- extract iso content with 7zip: 7z x ./xxx.iso
- install sample library

**Sources**
- linuxdaw.org
- tonehunt.org
