DU CMM
===
DU has CMM. This repository provides files to control DU CMM.
These files extend libdrm and du driver.

How to build

1. Store files to Yocto project
Store linux-renesas_4.14.bbappend to the following path.
	/meta-rcar-gen3/recipes-kernel
Store patches to the following path.
	/meta-rcar-gen3/recipes-kernel/linux/linux-renesas/salvator-x

2. building with bitbake

3. Build application with rcar_du_drm.h at du_cmm directory.

