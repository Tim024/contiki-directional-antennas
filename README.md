# Contiki-directional-antenna
This repository is the up-to-date contiki implementing the RDAS presented in the next section. I made sure it is compatible with the latest contiki version. Diff with contiki:
    - modified:   platform/cooja/Makefile.cooja
	- modified:   platform/cooja/contiki-cooja-main.c
	- modified:   tools/cooja/build.xml
	- modified:   tools/cooja/config/cooja_default.config
	- modified:   tools/cooja/java/org/contikios/cooja/MoteInterfaceHandler.java
	- modified:   tools/cooja/java/org/contikios/cooja/contikimote/interfaces/ContikiRadio.java
	- modified:   tools/cooja/java/org/contikios/cooja/interfaces/Radio.java
	- modified:   tools/cooja/java/org/contikios/cooja/motes/AbstractApplicationMoteType.java
	- modified:   tools/cooja/java/org/contikios/cooja/plugins/EventListener.java
	- modified:   tools/cooja/java/org/contikios/cooja/plugins/Visualizer.java
	- modified:   tools/cooja/java/org/contikios/cooja/radiomediums/UDGM.java
	- modified:   tools/mspsim (untracked content)
    - added:
	-     core/dev/dir.c
	-     core/dev/dir.h
	-     examples/rime-tsch/node_directional.c
	-     platform/cooja/dev/dir-arch.c
	-     tools/cooja/java/org/contikios/cooja/interfaces/Direction.java
	-     tools/cooja/java/org/contikios/cooja/interfaces/rad_pattern_EPA.txt
	-     tools/cooja/java/org/contikios/cooja/interfaces/rad_pattern_RPA.txt
	-     tools/cooja/java/org/contikios/cooja/interfaces/rad_pattern_RPA_flattop.txt
	-     tools/cooja/java/org/contikios/cooja/interfaces/rad_pattern_TPA.txt
	-     tools/cooja/java/org/contikios/cooja/interfaces/rad_pattern_dipole.txt
	-     tools/cooja/java/org/contikios/cooja/interfaces/rad_pattern_rege.txt

A working example is present in example/rime-tsch/node_directional.c.


# RDAS

Original Repo: https://github.com/ShamanthNagaraju/RDAS

Original Paper: https://doi.org/10.1109/NCC.2017.8077141

Inspired by: https://github.com/vrege/contiki-ant
