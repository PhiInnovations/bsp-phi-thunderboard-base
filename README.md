Thunderboard's Yocto BSP
===============================

This BSP is based on Freescale's Community Yocto BSP, adapted to build
Thunderboard board.

Supported boards
----------------

In order to know the supported boards, please, see the release notes at

   http://freescale.github.io/doc/release-notes/1.5/

Quick Start Guide
-----------------

Once you have downloaded the source of all projects, you will have to
call:

$: . ./setup-environment <build directory>

After this step, you will be with everything need for build an image.

Contributing
------------

To contribute to the development of this BSP and/or submit patches for
new boards please send the patches against the respective project as
informated bellow:

The following layers are included on this release:

 * poky: base build system and metadata
   Path: sources/poky
   GIT: git://git.yoctoproject.org/poky
   Mailing list: https://lists.yoctoproject.org/listinfo/yocto

