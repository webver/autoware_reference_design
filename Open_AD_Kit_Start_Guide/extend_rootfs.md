# Extend rootfs partition

## Overview

The rootfs partition is created with 5.2GB, but the size is too short to run docker container.
So we have to extend rootfs partition, or create new partition and assign the whole docker folder to the new partition.

Here is the instruction how to extend rootfs partition

## Extend rootfs

1. Run `gparted`.

   You may get the following warning when you run `gparted`.

   Press `Fix`.

   ![Warning](images/extend_rootfs/gparted01.png)

   Contents of storage after we flashed yocto image to M.2 SSD.
   ![Contents of storage](images/extend_rootfs/gparted02.png)

1. Unmout partitions.

   To manipulate partitions, you need to unmout `root` and `data` partition.

   Right click `root` partition, then click `Unmount`.
   ![Unmout root](images/extend_rootfs/gparted03.png)

   Unmount `data` partition as well.

1. Move `data` partition to the end of storage.

   Right click `data` partition, then click `Resize/Move`.
   ![Move data](images/extend_rootfs/gparted04.png)

   Drag the square to the right end.

   ![Drag data](images/extend_rootfs/gparted05.png)
   ![Data moved](images/extend_rootfs/gparted06.png)

   Then, click `Resize/Move`.

   ![Data moved](images/extend_rootfs/gparted07.png)

   Click `OK`.

   ![Data moved](images/extend_rootfs/gparted08.png)

1. Extend rootfs partiton to the end of disk.

   Right click `root` partition, then click `Resize/Move`.
   ![Move data](images/extend_rootfs/gparted09.png)

   Extend the square to the right end.

   ![Extend root](images/extend_rootfs/gparted10.png)
   ![Root extended](images/extend_rootfs/gparted11.png)

   Then, click `Resize/Move`.

   ![Extend square](images/extend_rootfs/gparted12.png)

1. Apply changes.

   Click check mark icon.

   ![Apply changes](images/extend_rootfs/gparted13.png)

   Click `Apply`.

   ![Apply changes](images/extend_rootfs/gparted14.png)

   You can get rootfs as follows.

   ![Apply changes](images/extend_rootfs/gparted15.png)
