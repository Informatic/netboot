netboot suite
=============

work in progress.


    data
    ├── images
    │   ├── debian-overlaytest
    │   │   ├── accessmode # file containing either rw or ro
    │   │   ├── base -> ../debian-test/rootfs/
    │   │   ├── overlay
    │   │   └── rootfs
    │   └─── debian-test
    │       └── rootfs
    └── tftproot
        ├── boot # directory
        ├── menu.c32
        ├── pxelinux.0
        ├── pxelinux.cfg
        │   ├── default
        │   └── images.cfg # autogenerated file
        └── vesamenu.c32
