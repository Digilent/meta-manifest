Digilent platform manifest for ZYBO
====================================
This manifest fetchs the required to Yocto project layers to build ZYBO
linux_bd hardward project.

Download the Source
===================
Currently the manifest fetches:
 * poky layer
 * meta-oe layer
 * meta-xilinx layer (with Zybo linux_bd support)
 * ZYBO hardware design

Initializing Repository
-----------------------

Initiate core trees:

    $ repo init -u https://github.com/Digilent/meta-manifest.git -b jethro

Sync the repository:

    $ repo sync

