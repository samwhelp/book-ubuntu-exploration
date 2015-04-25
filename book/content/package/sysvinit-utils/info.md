# sysvinit-utils info


## 套件資訊

執行

```
$ apt-cache show sysvinit-utils
```

顯示

```
Package: sysvinit-utils
Priority: required
Section: admin
Installed-Size: 242
Maintainer: Ubuntu Core Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Original-Maintainer: Debian sysvinit maintainers <pkg-sysvinit-devel@lists.alioth.debian.org>
Architecture: amd64
Source: sysvinit
Version: 2.88dsf-41ubuntu6.1
Replaces: last, sysvinit (<= 2.86.ds1-65)
Depends: libc6 (>= 2.15), libselinux1 (>= 1.32), sysv-rc (>= 2.88dsf-24) | file-rc (>= 0.8.16)
Recommends: upstart (>= 0.6.3-4)
Suggests: bootlogd, sash
Conflicts: chkconfig (<< 11.0-79.1-2), last, sysvconfig
Breaks: upstart (<< 1.5-0ubuntu5)
Filename: pool/main/s/sysvinit/sysvinit-utils_2.88dsf-41ubuntu6.1_amd64.deb
Size: 52914
MD5sum: 1fbc13ee3bb335b388c322b6ef2b3a08
SHA1: aba049ca786f114d8895264446a7b0ddfb84a9af
SHA256: 0e3c8892a2fce4326438d29b9303cb8392dd0ab95ed8e0489fa67fe13b58e19b
Description-en: System-V-like utilities
 This package contains the important System-V-like utilities.
 .
 Specifically, this package includes:
 killall5, last, lastb, mesg, pidof, service, sulogin
Description-md5: 1d2bc4c9c32104729144c7578ecd30bd
Multi-Arch: foreign
Homepage: http://savannah.nongnu.org/projects/sysvinit
Bugs: https://bugs.launchpad.net/ubuntu/+filebug
Origin: Ubuntu
Supported: 5y
Task: minimal

Package: sysvinit-utils
Priority: required
Section: admin
Installed-Size: 242
Maintainer: Ubuntu Core Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Original-Maintainer: Debian sysvinit maintainers <pkg-sysvinit-devel@lists.alioth.debian.org>
Architecture: amd64
Source: sysvinit
Version: 2.88dsf-41ubuntu6
Replaces: last, sysvinit (<= 2.86.ds1-65)
Depends: libc6 (>= 2.15), libselinux1 (>= 1.32), sysv-rc (>= 2.88dsf-24) | file-rc (>= 0.8.16)
Recommends: upstart (>= 0.6.3-4)
Suggests: bootlogd, sash
Conflicts: chkconfig (<< 11.0-79.1-2), last, sysvconfig
Breaks: upstart (<< 1.5-0ubuntu5)
Filename: pool/main/s/sysvinit/sysvinit-utils_2.88dsf-41ubuntu6_amd64.deb
Size: 53126
MD5sum: 473f1fc59249d46cd0c95708edb5f922
SHA1: c44430d04a04ba82189d5da08f452865bf9789aa
SHA256: effa15d814f14ffec9b8a7c0ee9f823779aa124deef1ec4b5495a4b437ac4d1b
Description-en: System-V-like utilities
 This package contains the important System-V-like utilities.
 .
 Specifically, this package includes:
 killall5, last, lastb, mesg, pidof, service, sulogin
Description-md5: 1d2bc4c9c32104729144c7578ecd30bd
Multi-Arch: foreign
Homepage: http://savannah.nongnu.org/projects/sysvinit
Bugs: https://bugs.launchpad.net/ubuntu/+filebug
Origin: Ubuntu
Supported: 5y
Task: minimal

```

執行

```
$ apt-cache showpkg sysvinit-utils
```

顯示

```
Package: sysvinit-utils
Versions:
2.88dsf-41ubuntu6.1 (/var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty-updates_main_binary-amd64_Packages) (/var/lib/dpkg/status)
 Description Language:
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_binary-amd64_Packages
                  MD5: 1d2bc4c9c32104729144c7578ecd30bd
 Description Language: en
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_i18n_Translation-en
                  MD5: 1d2bc4c9c32104729144c7578ecd30bd

2.88dsf-41ubuntu6 (/var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_binary-amd64_Packages)
 Description Language:
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_binary-amd64_Packages
                  MD5: 1d2bc4c9c32104729144c7578ecd30bd
 Description Language: en
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_i18n_Translation-en
                  MD5: 1d2bc4c9c32104729144c7578ecd30bd


Reverse Depends:
  bootlogd:i386,sysvinit-utils 2.88dsf-17
  bootlogd:i386,sysvinit-utils 2.88dsf-17
  sysvinit-utils:i386,sysvinit-utils
  bootlogd,sysvinit-utils 2.88dsf-17
  bootlogd,sysvinit-utils 2.88dsf-17
  upstart,sysvinit-utils
  sysv-rc,sysvinit-utils 2.86.ds1-62
  initscripts,sysvinit-utils 2.86.ds1-64
  bootlogd:i386,sysvinit-utils 2.88dsf-17
  bootlogd:i386,sysvinit-utils 2.88dsf-17
  sysvinit-utils:i386,sysvinit-utils
  bootlogd,sysvinit-utils 2.88dsf-17
  bootlogd,sysvinit-utils 2.88dsf-17
  upstart,sysvinit-utils
  sysv-rc,sysvinit-utils 2.86.ds1-62
  initscripts,sysvinit-utils 2.86.ds1-64
Dependencies:
2.88dsf-41ubuntu6.1 - libc6 (2 2.15) libselinux1 (2 1.32) sysv-rc (18 2.88dsf-24) file-rc (2 0.8.16) bootlogd (0 (null)) sash (0 (null)) upstart (2 0.6.3-4) chkconfig (3 11.0-79.1-2) chkconfig:i386 (3 11.0-79.1-2) last (0 (null)) last:i386 (0 (null)) sysvconfig (0 (null)) sysvconfig:i386 (0 (null)) upstart (3 1.5-0ubuntu5) upstart:i386 (3 1.5-0ubuntu5) last (0 (null)) last:i386 (0 (null)) sysvinit (1 2.86.ds1-65) sysvinit:i386 (1 2.86.ds1-65) sysvinit-utils:i386 (0 (null))
2.88dsf-41ubuntu6 - libc6 (2 2.15) libselinux1 (2 1.32) sysv-rc (18 2.88dsf-24) file-rc (2 0.8.16) bootlogd (0 (null)) sash (0 (null)) upstart (2 0.6.3-4) chkconfig (3 11.0-79.1-2) chkconfig:i386 (3 11.0-79.1-2) last (0 (null)) last:i386 (0 (null)) sysvconfig (0 (null)) sysvconfig:i386 (0 (null)) upstart (3 1.5-0ubuntu5) upstart:i386 (3 1.5-0ubuntu5) last (0 (null)) last:i386 (0 (null)) sysvinit (1 2.86.ds1-65) sysvinit:i386 (1 2.86.ds1-65) sysvinit-utils:i386 (0 (null))
Provides:
2.88dsf-41ubuntu6.1 - sysvinit-utils:i386
2.88dsf-41ubuntu6 - sysvinit-utils:i386
Reverse Provides:
sysvinit-utils:i386 2.88dsf-41ubuntu6.1
sysvinit-utils:i386 2.88dsf-41ubuntu6

```

執行

```
$ apt-cache showsrc sysvinit-utils
```

顯示

```
Package: sysvinit
Binary: sysvinit-utils, sysv-rc, initscripts, bootlogd
Version: 2.88dsf-41ubuntu6
Priority: required
Section: admin
Maintainer: Ubuntu Core Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Original-Maintainer: Debian sysvinit maintainers <pkg-sysvinit-devel@lists.alioth.debian.org>
Build-Depends: debhelper (>= 9.20120410), po-debconf, quilt (>= 0.40), libselinux1-dev (>= 1.14) [linux-any], libsepol1-dev [linux-any]
Architecture: any all
Standards-Version: 3.9.3
Format: 3.0 (quilt)
Directory: pool/main/s/sysvinit
Files:
 ef452b6e7e374a575ca1d2122ff4cf2d 2396 sysvinit_2.88dsf-41ubuntu6.dsc
 e1329961d7c6d8aa7dae7af3d748c507 125330 sysvinit_2.88dsf.orig.tar.gz
 79f5d5936bc431ba90c8b1f60692fbfa 203483 sysvinit_2.88dsf-41ubuntu6.debian.tar.gz
Uploaders:  Petter Reinholdtsen <pere@debian.org>, Henrique de Moraes Holschuh <hmh@debian.org>, Kel Modderman <kel@otaku42.de>, Roger Leigh <rleigh@debian.org>
Homepage: http://savannah.nongnu.org/projects/sysvinit
Vcs-Browser: http://anonscm.debian.org/gitweb/?p=collab-maint/sysvinit
Vcs-Git: git://git.debian.org/collab-maint/sysvinit
Package-List:
 bootlogd deb admin optional
 initscripts deb admin required
 sysv-rc deb admin required
 sysvinit-utils deb admin required
Checksums-Sha1:
 4b00ad5034d34b3ce783c4d744c4494e5515828f 2396 sysvinit_2.88dsf-41ubuntu6.dsc
 0dc988f90f093db892d0c6f7b2820edf5a6e298e 125330 sysvinit_2.88dsf.orig.tar.gz
 ef686d773f8cb7c34463c6832c9811a5a37c449b 203483 sysvinit_2.88dsf-41ubuntu6.debian.tar.gz
Checksums-Sha256:
 dc6fdd6431062ee9920bada8592ec030a9a8b0cf426c426fc853a0bde65761b5 2396 sysvinit_2.88dsf-41ubuntu6.dsc
 b016f937958d2809a020d407e1287bdc09abf1d44efaa96530e2ea57f544f4e8 125330 sysvinit_2.88dsf.orig.tar.gz
 7d1e203c2ca0006fe3e581f5012cb6a414a513dffda58ad451d42615ffdfe829 203483 sysvinit_2.88dsf-41ubuntu6.debian.tar.gz

Package: sysvinit
Binary: sysvinit-utils, sysv-rc, initscripts, bootlogd
Version: 2.88dsf-41ubuntu6.1
Priority: required
Section: admin
Maintainer: Ubuntu Core Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Original-Maintainer: Debian sysvinit maintainers <pkg-sysvinit-devel@lists.alioth.debian.org>
Build-Depends: debhelper (>= 9.20120410), po-debconf, quilt (>= 0.40), libselinux1-dev (>= 1.14) [linux-any], libsepol1-dev [linux-any]
Architecture: any all
Standards-Version: 3.9.3
Format: 3.0 (quilt)
Directory: pool/main/s/sysvinit
Files:
 4cb15cb48a5683d956db5c4ae1a322b2 2406 sysvinit_2.88dsf-41ubuntu6.1.dsc
 e1329961d7c6d8aa7dae7af3d748c507 125330 sysvinit_2.88dsf.orig.tar.gz
 521ae0671b958dec1b35e98a3b1ba3f5 202836 sysvinit_2.88dsf-41ubuntu6.1.debian.tar.gz
Uploaders:  Petter Reinholdtsen <pere@debian.org>, Henrique de Moraes Holschuh <hmh@debian.org>, Kel Modderman <kel@otaku42.de>, Roger Leigh <rleigh@debian.org>
Homepage: http://savannah.nongnu.org/projects/sysvinit
Vcs-Browser: http://anonscm.debian.org/gitweb/?p=collab-maint/sysvinit
Vcs-Git: git://git.debian.org/collab-maint/sysvinit
Package-List:
 bootlogd deb admin optional
 initscripts deb admin required
 sysv-rc deb admin required
 sysvinit-utils deb admin required
Checksums-Sha1:
 213ac53f76a3ee511ea7fdff4dd7da7fbbc01fe5 2406 sysvinit_2.88dsf-41ubuntu6.1.dsc
 0dc988f90f093db892d0c6f7b2820edf5a6e298e 125330 sysvinit_2.88dsf.orig.tar.gz
 50d0432e1f59d44fd6e0262b921ccbbb8fa64f0d 202836 sysvinit_2.88dsf-41ubuntu6.1.debian.tar.gz
Checksums-Sha256:
 99510197fb25a637e7466303002b56ae1705105fa82b476614f415eee8326746 2406 sysvinit_2.88dsf-41ubuntu6.1.dsc
 b016f937958d2809a020d407e1287bdc09abf1d44efaa96530e2ea57f544f4e8 125330 sysvinit_2.88dsf.orig.tar.gz
 0024946c73c97b092dff005250abf678f2c844ba3374cc11493974f5ef8f45ea 202836 sysvinit_2.88dsf-41ubuntu6.1.debian.tar.gz


```

執行

```
$ dpkg -s sysvinit-utils
```

顯示

```
Package: sysvinit-utils
Status: install ok installed
Priority: required
Section: admin
Installed-Size: 242
Maintainer: Ubuntu Core Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Architecture: amd64
Multi-Arch: foreign
Source: sysvinit
Version: 2.88dsf-41ubuntu6.1
Replaces: last, sysvinit (<= 2.86.ds1-65)
Depends: libc6 (>= 2.15), libselinux1 (>= 1.32), sysv-rc (>= 2.88dsf-24) | file-rc (>= 0.8.16)
Recommends: upstart (>= 0.6.3-4)
Suggests: bootlogd, sash
Breaks: upstart (<< 1.5-0ubuntu5)
Conflicts: chkconfig (<< 11.0-79.1-2), last, sysvconfig
Conffiles:
 /etc/init/startpar-bridge.conf d220afa75514468471c42469967341d2
Description: System-V-like utilities
 This package contains the important System-V-like utilities.
 .
 Specifically, this package includes:
 killall5, last, lastb, mesg, pidof, service, sulogin
Homepage: http://savannah.nongnu.org/projects/sysvinit
Original-Maintainer: Debian sysvinit maintainers <pkg-sysvinit-devel@lists.alioth.debian.org>
```

執行

```
$ dpkg -l sysvinit-utils
```

顯示

```
Desired=Unknown/Install/Remove/Purge/Hold
| Status=Not/Inst/Conf-files/Unpacked/halF-conf/Half-inst/trig-aWait/Trig-pend
|/ Err?=(none)/Reinst-required (Status,Err: uppercase=bad)
||/ Name                         Version             Architecture        Description
+++-============================-===================-===================-==============================================================
ii  sysvinit-utils               2.88dsf-41ubuntu6.1 amd64               System-V-like utilities

```


## 準備工作環境

```
mkdir  ~/Downloads/sysvinit-utils -p
cd ~/Downloads/sysvinit-utils
mkdir download source
```

## 探索「Package: [sysvinit-utils](http://packages.ubuntu.com/trusty/sysvinit-utils)」

切換到「~/Downloads/sysvinit-utils/download」

``` sh
$ cd ~/Downloads/sysvinit-utils/download
```

下載「Package: sysvinit-utils」。

``` sh
$ apt-get download sysvinit-utils
```

解開「package sysvinit-utils」

``` sh
dpkg -x sysvinit-utils_2.88dsf-41ubuntu6.1_amd64.deb sysvinit-utils
dpkg -e sysvinit-utils_2.88dsf-41ubuntu6.1_amd64.deb
# ar xv sysvinit-utils_2.88dsf-41ubuntu6.1_amd64.deb
```

檢視套件檔案

``` sh
$ tree sysvinit-utils
```

顯示

```
sysvinit-utils
├── bin
│   └── pidof -> /sbin/killall5
├── etc
│   └── init
│       └── startpar-bridge.conf
├── sbin
│   ├── fstab-decode
│   ├── killall5
│   ├── startpar
│   ├── startpar-upstart-inject
│   └── sulogin
└── usr
    ├── bin
    │   ├── last
    │   ├── lastb -> last
    │   ├── mesg
    │   └── service -> ../sbin/service
    ├── sbin
    │   └── service
    └── share
        ├── doc
        │   └── sysvinit-utils
        │       ├── changelog.Debian.gz
        │       ├── copyright
        │       └── NEWS.Debian.gz
        └── man
            ├── man1
            │   ├── last.1.gz
            │   ├── lastb.1.gz -> last.1.gz
            │   └── mesg.1.gz
            └── man8
                ├── fstab-decode.8.gz
                ├── killall5.8.gz
                ├── pidof.8.gz
                ├── service.8.gz
                ├── startpar.8.gz
                └── sulogin.8.gz

13 directories, 24 files

```

執行

```
$ tree DEBIAN
```

顯示

```
DEBIAN
├── conffiles
├── control
└── md5sums

0 directories, 3 files


```


## 探索「Source Package: [sysvinit](packages.ubuntu.com/source/trusty/sysvinit)」

切換到「~/Downloads/sysvinit-utils/source」

``` sh
$ cd ~/Downloads/sysvinit-utils/source
```

下載「Source Package: sysvinit」。

``` sh
$ apt-get source sysvinit-utils
```

檢視原始碼套件檔案。

```
$ tree sysvinit-2.88dsf
```

顯示

```
sysvinit-2.88dsf
├── contrib
│   ├── alexander.viro
│   ├── notify-pam-dead.patch
│   ├── start-stop-daemon.c
│   ├── start-stop-daemon.README
│   ├── TODO
│   └── zefram-patches
├── COPYING
├── COPYRIGHT
├── debian
│   ├── bootlogd.install
│   ├── bootlogd.lintian-overrides
│   ├── bootlogd.postinst
│   ├── bootlogd.postrm
│   ├── changelog
│   ├── compat
│   ├── control
│   ├── copyright.in
│   ├── deps-mount
│   ├── fscklog.sh
│   ├── git-tag
│   ├── initscripts.conffiles
│   ├── initscripts.copyright
│   ├── initscripts.install
│   ├── initscripts.lintian-overrides
│   ├── initscripts.maintscript
│   ├── initscripts.postinst
│   ├── initscripts.postrm
│   ├── initscripts.preinst
│   ├── NOTES
│   ├── patches
│   │   ├── 10_doc_manuals.dpatch
│   │   ├── 11_lfs_cflags.patch
│   │   ├── 11_man_fstab_decode_typo
│   │   ├── 11_man_halt8.patch
│   │   ├── 20_init_freebsd_vswtc.patch
│   │   ├── 30_killall5_hurd.patch
│   │   ├── 40_multiarch_libcrypt.patch
│   │   ├── 63_init_keep_utf8_ttyflag.patch
│   │   ├── 64_init_selinux_enabled.patch
│   │   ├── 69_startpar.patch
│   │   ├── 70_not_suse.patch
│   │   ├── 71_signalfd.patch
│   │   ├── 72_path_max.patch
│   │   ├── 73_lfs_cflags.patch
│   │   ├── 74_man_startpar_iorate.patch
│   │   ├── 75_man_startpar_see_also.patch
│   │   ├── 76_startpar_ldflags.patch
│   │   ├── 77_startpar_skip_reason.patch
│   │   ├── 79_startpar_kfreebsd_mlockall.patch
│   │   ├── 91_sulogin_lockedpw.dpatch
│   │   ├── 92_kfreebsd_ifdown.patch
│   │   ├── 92_sulogin_support_static_sh.patch
│   │   ├── 93_run_initctl.patch
│   │   ├── 94_kfreebsd_xterm.patch
│   │   ├── series
│   │   └── upstart_support.patch
│   ├── po
│   │   ├── ca.po
│   │   ├── cs.po
│   │   ├── da.po
│   │   ├── de.po
│   │   ├── es.po
│   │   ├── fi.po
│   │   ├── fr.po
│   │   ├── gl.po
│   │   ├── it.po
│   │   ├── ja.po
│   │   ├── nb.po
│   │   ├── nl.po
│   │   ├── pl.po
│   │   ├── POTFILES.in
│   │   ├── pt_BR.po
│   │   ├── pt.po
│   │   ├── ru.po
│   │   ├── sk.po
│   │   ├── sv.po
│   │   ├── templates.pot
│   │   ├── vi.po
│   │   └── zh_CN.po
│   ├── README.source
│   ├── rules
│   ├── service
│   │   ├── service
│   │   └── service.8
│   ├── share
│   │   ├── inittab
│   │   ├── inittab.gnu
│   │   ├── inittab.kfreebsd-gnu
│   │   ├── inittab.knetbsd-gnu
│   │   ├── inittab.s390-linux-gnu
│   │   ├── inittab.s390x-linux-gnu
│   │   └── update-rc.d
│   ├── source
│   │   └── format
│   ├── src
│   │   ├── bootlogd
│   │   │   ├── etc
│   │   │   │   └── init.d
│   │   │   │       ├── bootlogd
│   │   │   │       ├── stop-bootlogd
│   │   │   │       └── stop-bootlogd-single
│   │   │   └── Makefile
│   │   ├── initscripts
│   │   │   ├── doc
│   │   │   │   └── README.Debian
│   │   │   ├── etc
│   │   │   │   ├── default
│   │   │   │   │   ├── devpts
│   │   │   │   │   ├── halt
│   │   │   │   │   └── rcS
│   │   │   │   └── init.d
│   │   │   │       ├── halt
│   │   │   │       ├── killprocs
│   │   │   │       ├── ondemand
│   │   │   │       ├── rc.local
│   │   │   │       ├── reboot
│   │   │   │       ├── sendsigs
│   │   │   │       ├── single
│   │   │   │       ├── skeleton
│   │   │   │       ├── umountfs
│   │   │   │       ├── umountnfs.sh
│   │   │   │       ├── umountroot
│   │   │   │       └── urandom
│   │   │   ├── lib
│   │   │   │   └── init
│   │   │   │       └── vars.sh
│   │   │   ├── Makefile
│   │   │   ├── man
│   │   │   │   ├── fsck.nfs.8
│   │   │   │   ├── halt.5
│   │   │   │   └── rcS.5
│   │   │   └── sbin
│   │   │       └── fsck.nfs
│   │   └── sysv-rc
│   │       ├── doc
│   │       │   ├── README.Debian
│   │       │   ├── README.invoke-rc.d
│   │       │   ├── README.policy-rc.d
│   │       │   └── README.runlevels
│   │       ├── etc
│   │       │   ├── init.d
│   │       │   │   ├── rc
│   │       │   │   ├── rcS
│   │       │   │   └── README
│   │       │   ├── rc0.d
│   │       │   │   └── README
│   │       │   ├── rc1.d
│   │       │   │   └── README
│   │       │   ├── rc6.d
│   │       │   │   └── README
│   │       │   └── rcS.d
│   │       │       └── README
│   │       ├── Makefile
│   │       ├── man8
│   │       │   ├── es
│   │       │   │   └── update-rc.d.8
│   │       │   ├── fr.UTF-8
│   │       │   │   └── update-rc.d.8
│   │       │   ├── invoke-rc.d.8
│   │       │   ├── ja
│   │       │   │   └── update-rc.d.8
│   │       │   └── update-rc.d.8
│   │       ├── rc2-5.d-README
│   │       ├── saveconfig
│   │       └── sbin
│   │           ├── invoke-rc.d
│   │           └── update-rc.d
│   ├── sysvinit.dirs
│   ├── sysvinit.install
│   ├── sysvinit.links
│   ├── sysvinit.lintian-overrides
│   ├── sysvinit.NEWS
│   ├── sysvinit-utils.install
│   ├── sysvinit-utils.links
│   ├── sysvinit-utils.manpages
│   ├── sysvinit-utils.NEWS
│   ├── sysvinit-utils.startpar-bridge.upstart
│   ├── sysvinit-watch
│   ├── sysv-rc.copyright
│   ├── sysv-rc.lintian-overrides
│   ├── sysv-rc.postinst
│   ├── sysv-rc.postrm
│   ├── sysv-rc.preinst
│   ├── sysv-rc.prerm
│   ├── sysv-rc.templates
│   └── watch
├── doc
│   ├── bootlogd.README
│   ├── Changelog
│   ├── Install
│   ├── Propaganda
│   └── sysvinit-2.86.lsm
├── Makefile
├── man
│   ├── bootlogd.8
│   ├── bootlogd.8.todo
│   ├── fstab-decode.8
│   ├── halt.8
│   ├── init.8
│   ├── initscript.5
│   ├── inittab.5
│   ├── killall5.8
│   ├── last.1
│   ├── lastb.1
│   ├── mesg.1
│   ├── mountpoint.1
│   ├── pidof.8
│   ├── poweroff.8
│   ├── reboot.8
│   ├── runlevel.8
│   ├── shutdown.8
│   ├── sulogin.8
│   ├── telinit.8
│   ├── utmpdump.1
│   └── wall.1
├── obsolete
│   ├── bootlogd.init
│   ├── powerd.8
│   ├── powerd.c
│   ├── powerd.cfg
│   ├── powerd.README
│   ├── README.RIGHT.NOW
│   └── utmpdump.c.OLD
├── README
├── src
│   ├── bootlogd.c
│   ├── dowall.c
│   ├── fstab-decode.c
│   ├── halt.c
│   ├── hddown.c
│   ├── ifdown.c
│   ├── init.c
│   ├── init.h
│   ├── initreq.h
│   ├── initscript.sample
│   ├── killall5.c
│   ├── last.c
│   ├── Makefile
│   ├── mesg.c
│   ├── mountpoint.c
│   ├── oldutmp.h
│   ├── paths.h
│   ├── reboot.h
│   ├── runlevel.c
│   ├── set.h
│   ├── shutdown.c
│   ├── sulogin.c
│   ├── utmp.c
│   ├── utmpdump.c
│   └── wall.c
└── startpar
    ├── COPYING
    ├── makeboot.c
    ├── makeboot.h
    ├── Makefile
    ├── proc.c
    ├── proc.h
    ├── startpar.8
    ├── startpar.c
    ├── startpar.h
    ├── startpar-upstart-inject.8
    └── startpar-upstart-inject.c

38 directories, 225 files
```
