# bash info


## 套件資訊

執行

```
$ apt-cache show bash
```

顯示

```
Package: bash
Essential: yes
Priority: required
Section: shells
Installed-Size: 1488
Maintainer: Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Original-Maintainer: Matthias Klose <doko@debian.org>
Architecture: amd64
Version: 4.3-7ubuntu1.5
Replaces: bash-completion (<< 20060301-0), bash-doc (<= 2.05-1)
Depends: base-files (>= 2.1.12), debianutils (>= 2.15)
Pre-Depends: dash (>= 0.5.5.1-2.2), libc6 (>= 2.15), libtinfo5
Recommends: bash-completion (>= 20060301-0)
Suggests: bash-doc
Conflicts: bash-completion (<< 20060301-0)
Filename: pool/main/b/bash/bash_4.3-7ubuntu1.5_amd64.deb
Size: 575658
MD5sum: a4ac17c05ad0163941b9f131160e1dd4
SHA1: 87ce91afb047539bf0f5d09a4191bf92a29031f3
SHA256: c93db280ac87c5281b1d77a7e74eb6ee547259b5c8b9b29ede28ed7ef5f7daa1
Description-en: GNU Bourne Again SHell
 Bash is an sh-compatible command language interpreter that executes
 commands read from the standard input or from a file.  Bash also
 incorporates useful features from the Korn and C shells (ksh and csh).
 .
 Bash is ultimately intended to be a conformant implementation of the
 IEEE POSIX Shell and Tools specification (IEEE Working Group 1003.2).
 .
 The Programmable Completion Code, by Ian Macdonald, is now found in
 the bash-completion package.
Description-md5: 3522aa7b4374048d6450e348a5bb45d9
Multi-Arch: foreign
Homepage: http://tiswww.case.edu/php/chet/bash/bashtop.html
Bugs: https://bugs.launchpad.net/ubuntu/+filebug
Origin: Ubuntu
Supported: 5y
Task: minimal

Package: bash
Essential: yes
Priority: required
Section: shells
Installed-Size: 1480
Maintainer: Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Original-Maintainer: Matthias Klose <doko@debian.org>
Architecture: amd64
Version: 4.3-6ubuntu1
Replaces: bash-completion (<< 20060301-0), bash-doc (<= 2.05-1)
Depends: base-files (>= 2.1.12), debianutils (>= 2.15)
Pre-Depends: dash (>= 0.5.5.1-2.2), libc6 (>= 2.15), libtinfo5
Recommends: bash-completion (>= 20060301-0)
Suggests: bash-doc
Conflicts: bash-completion (<< 20060301-0)
Filename: pool/main/b/bash/bash_4.3-6ubuntu1_amd64.deb
Size: 574464
MD5sum: 4829101773fd90ae0574fa83e474603a
SHA1: e83093dab2e82db5e8c72944585c17dc976dc0f5
SHA256: 9ebbf2a9c4dbffa7b20f22c9c17de0ea3b8d79619d2bbb740c1bc483514642e7
Description-en: GNU Bourne Again SHell
 Bash is an sh-compatible command language interpreter that executes
 commands read from the standard input or from a file.  Bash also
 incorporates useful features from the Korn and C shells (ksh and csh).
 .
 Bash is ultimately intended to be a conformant implementation of the
 IEEE POSIX Shell and Tools specification (IEEE Working Group 1003.2).
 .
 The Programmable Completion Code, by Ian Macdonald, is now found in
 the bash-completion package.
Description-md5: 3522aa7b4374048d6450e348a5bb45d9
Multi-Arch: foreign
Homepage: http://tiswww.case.edu/php/chet/bash/bashtop.html
Bugs: https://bugs.launchpad.net/ubuntu/+filebug
Origin: Ubuntu
Supported: 5y
Task: minimal

```

執行

```
$ apt-cache showpkg bash
```

顯示

```
Package: bash
Versions:
4.3-7ubuntu1.5 (/var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty-updates_main_binary-amd64_Packages) (/var/lib/apt/lists/security.ubuntu.com_ubuntu_dists_trusty-security_main_binary-amd64_Packages) (/var/lib/dpkg/status)
 Description Language:
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_binary-amd64_Packages
                  MD5: 3522aa7b4374048d6450e348a5bb45d9
 Description Language: en
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_i18n_Translation-en
                  MD5: 3522aa7b4374048d6450e348a5bb45d9

4.3-6ubuntu1 (/var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_binary-amd64_Packages)
 Description Language:
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_binary-amd64_Packages
                  MD5: 3522aa7b4374048d6450e348a5bb45d9
 Description Language: en
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_i18n_Translation-en
                  MD5: 3522aa7b4374048d6450e348a5bb45d9


Reverse Depends:
  sublime-text,bash
  bash:i386,bash
  gdm,bash 4.3
  chromium-browser,bash 4
  bash-builtins,bash 4.3-7ubuntu1.5
  lightdm,bash 4.3
  bash-doc,bash 4.3-2
  bash:i386,bash
  uck,bash 3.0
  txt2regex,bash 2.04
  s3dvt,bash 2.0
  rdup,bash 3.0.0
  prey,bash 4
  podget,bash 3.0
  origami,bash 3.2
  netscript-2.4-upstart,bash 2.03
  netscript-2.4,bash 2.03
  monotone,bash 4.0
  mason,bash 2.04-1
  lrzip,bash 3
  libbash,bash 3
  inxi,bash 3.0
  gt5,bash 2.5
  git-ftp,bash 4.2
  foomatic-filters,bash 2.05
  firehol,bash 4.2
  fiaif,bash 2.04
  fadecut,bash 3.2-4
  diffmon,bash 2.0
  devscripts-el,bash 2.05a
  common-lisp-controller,bash 2.04-9
  colortest,bash 3
  biabam,bash 2
  bashdb,bash 4.0
  bashburn,bash 3.0
  bash-builtins,bash 4.3-6ubuntu1
  backupninja,bash 2.05b-26
  autojump,bash
  armagetronad-dedicated,bash 3
  foomatic-db-engine,bash 2.05
  emacs-goodies-el,bash 2.05a
  dpatch,bash 3.0-6
  bash-doc,bash 4.3-2
  bash-completion,bash
  bash-completion,bash 3.2
Dependencies:
4.3-7ubuntu1.5 - base-files (2 2.1.12) debianutils (2 2.15) dash (2 0.5.5.1-2.2) libc6 (2 2.15) libtinfo5 (0 (null)) bash-doc (0 (null)) bash-completion (2 20060301-0) bash-completion (3 20060301-0) bash-completion:i386 (3 20060301-0) bash-completion (3 20060301-0) bash-completion:i386 (3 20060301-0) bash-doc (1 2.05-1) bash-doc:i386 (1 2.05-1) bash:i386 (0 (null))
4.3-6ubuntu1 - base-files (2 2.1.12) debianutils (2 2.15) dash (2 0.5.5.1-2.2) libc6 (2 2.15) libtinfo5 (0 (null)) bash-doc (0 (null)) bash-completion (2 20060301-0) bash-completion (3 20060301-0) bash-completion:i386 (3 20060301-0) bash-completion (3 20060301-0) bash-completion:i386 (3 20060301-0) bash-doc (1 2.05-1) bash-doc:i386 (1 2.05-1) bash:i386 (0 (null))
Provides:
4.3-7ubuntu1.5 - bash:i386
4.3-6ubuntu1 - bash:i386
Reverse Provides:
bash:i386 4.3-7ubuntu1.5
bash:i386 4.3-6ubuntu1
```

執行

```
$ apt-cache showsrc bash
```

顯示

```
Package: bash
Binary: bash, bash-static, bash-builtins, bash-doc
Version: 4.3-6ubuntu1
Priority: required
Section: shells
Maintainer: Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Original-Maintainer: Matthias Klose <doko@debian.org>
Build-Depends: autoconf, autotools-dev, bison, libncurses5-dev, texinfo, texi2html, debhelper (>= 5), locales, gettext, sharutils, time, xz-utils, dpkg-dev (>= 1.16.1)
Build-Depends-Indep: texlive-latex-base, ghostscript, texlive-fonts-recommended
Architecture: any all
Standards-Version: 3.9.5
Format: 3.0 (quilt)
Directory: pool/main/b/bash
Files:
 db3438288c7f5474b8c05971d9996ab5 1611 bash_4.3-6ubuntu1.dsc
 557827017514aaa0d1e3888da7567cfc 7516231 bash_4.3.orig.tar.gz
 1899193f4a7124f3bda706faf3d378cf 77807 bash_4.3-6ubuntu1.debian.tar.gz
Homepage: http://tiswww.case.edu/php/chet/bash/bashtop.html
Vcs-Browser: https://code.launchpad.net/~doko/+junk/pkg-bash-debian
Vcs-Bzr: http://bazaar.launchpad.net/~doko/+junk/pkg-bash-debian
Package-List:
 bash deb shells required
 bash-builtins deb utils optional
 bash-doc deb doc optional
 bash-static deb shells optional
Checksums-Sha1:
 799dee00ef507ca8d22dba84cd1d1c7213809208 1611 bash_4.3-6ubuntu1.dsc
 a44778703fa80ba13baa9134f9086ad09cc5147a 7516231 bash_4.3.orig.tar.gz
 e30d0fad70f099640ec5211e0ea57583b7a93cf3 77807 bash_4.3-6ubuntu1.debian.tar.gz
Checksums-Sha256:
 3b760c2fb2af9237eda7bc5f7a256cda10f8ec83c1eb0caea48a39080ddb7676 1611 bash_4.3-6ubuntu1.dsc
 b2fe79ddf9e7abdb4695e3070afa866d2a94a58d1cc9d731585330c753815491 7516231 bash_4.3.orig.tar.gz
 778340416f2ac5497a90cf0ee50ec4475d2d7cfbbea7f7a5fdc811bfae260367 77807 bash_4.3-6ubuntu1.debian.tar.gz

Package: bash
Binary: bash, bash-static, bash-builtins, bash-doc
Version: 4.3-7ubuntu1.5
Priority: required
Section: shells
Maintainer: Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Original-Maintainer: Matthias Klose <doko@debian.org>
Build-Depends: autoconf, autotools-dev, bison, libncurses5-dev, texinfo, texi2html, debhelper (>= 5), locales, gettext, sharutils, time, xz-utils, dpkg-dev (>= 1.16.1)
Build-Depends-Indep: texlive-latex-base, ghostscript, texlive-fonts-recommended
Architecture: any all
Standards-Version: 3.9.5
Format: 3.0 (quilt)
Directory: pool/main/b/bash
Files:
 c7939fa5aeb88cb4c655288b4039b245 2259 bash_4.3-7ubuntu1.5.dsc
 557827017514aaa0d1e3888da7567cfc 7516231 bash_4.3.orig.tar.gz
 5c4514abb413f9d151ad60e9ab56265f 97906 bash_4.3-7ubuntu1.5.debian.tar.gz
Homepage: http://tiswww.case.edu/php/chet/bash/bashtop.html
Vcs-Browser: https://code.launchpad.net/~doko/+junk/pkg-bash-debian
Vcs-Bzr: http://bazaar.launchpad.net/~doko/+junk/pkg-bash-debian
Package-List:
 bash deb shells required
 bash-builtins deb utils optional
 bash-doc deb doc optional
 bash-static deb shells optional
Checksums-Sha1:
 e3a186df4bf09d1bb89f949ebce1ffe53b604775 2259 bash_4.3-7ubuntu1.5.dsc
 a44778703fa80ba13baa9134f9086ad09cc5147a 7516231 bash_4.3.orig.tar.gz
 04775cbc2028a35c90cb141b42f66fdecd4fecc3 97906 bash_4.3-7ubuntu1.5.debian.tar.gz
Checksums-Sha256:
 c24e9ea41fa706ff657de58f9232d6db823bff7e56b2d55062f458bcdcb20914 2259 bash_4.3-7ubuntu1.5.dsc
 b2fe79ddf9e7abdb4695e3070afa866d2a94a58d1cc9d731585330c753815491 7516231 bash_4.3.orig.tar.gz
 6cd025d14f7ad1accef69602acebdadb79b4b0a332c97da200be61978920c7d6 97906 bash_4.3-7ubuntu1.5.debian.tar.gz

Package: bash
Binary: bash, bash-static, bash-builtins, bash-doc
Version: 4.3-7ubuntu1.5
Priority: required
Section: shells
Maintainer: Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Original-Maintainer: Matthias Klose <doko@debian.org>
Build-Depends: autoconf, autotools-dev, bison, libncurses5-dev, texinfo, texi2html, debhelper (>= 5), locales, gettext, sharutils, time, xz-utils, dpkg-dev (>= 1.16.1)
Build-Depends-Indep: texlive-latex-base, ghostscript, texlive-fonts-recommended
Architecture: any all
Standards-Version: 3.9.5
Format: 3.0 (quilt)
Directory: pool/main/b/bash
Files:
 c7939fa5aeb88cb4c655288b4039b245 2259 bash_4.3-7ubuntu1.5.dsc
 557827017514aaa0d1e3888da7567cfc 7516231 bash_4.3.orig.tar.gz
 5c4514abb413f9d151ad60e9ab56265f 97906 bash_4.3-7ubuntu1.5.debian.tar.gz
Homepage: http://tiswww.case.edu/php/chet/bash/bashtop.html
Vcs-Browser: https://code.launchpad.net/~doko/+junk/pkg-bash-debian
Vcs-Bzr: http://bazaar.launchpad.net/~doko/+junk/pkg-bash-debian
Package-List:
 bash deb shells required
 bash-builtins deb utils optional
 bash-doc deb doc optional
 bash-static deb shells optional
Checksums-Sha1:
 e3a186df4bf09d1bb89f949ebce1ffe53b604775 2259 bash_4.3-7ubuntu1.5.dsc
 a44778703fa80ba13baa9134f9086ad09cc5147a 7516231 bash_4.3.orig.tar.gz
 04775cbc2028a35c90cb141b42f66fdecd4fecc3 97906 bash_4.3-7ubuntu1.5.debian.tar.gz
Checksums-Sha256:
 c24e9ea41fa706ff657de58f9232d6db823bff7e56b2d55062f458bcdcb20914 2259 bash_4.3-7ubuntu1.5.dsc
 b2fe79ddf9e7abdb4695e3070afa866d2a94a58d1cc9d731585330c753815491 7516231 bash_4.3.orig.tar.gz
 6cd025d14f7ad1accef69602acebdadb79b4b0a332c97da200be61978920c7d6 97906 bash_4.3-7ubuntu1.5.debian.tar.gz


```

執行

```
$ dpkg -s bash
```

顯示

```
Package: bash
Essential: yes
Status: install ok installed
Priority: required
Section: shells
Installed-Size: 1488
Maintainer: Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Architecture: amd64
Multi-Arch: foreign
Version: 4.3-7ubuntu1.5
Replaces: bash-completion (<< 20060301-0), bash-doc (<= 2.05-1)
Depends: base-files (>= 2.1.12), debianutils (>= 2.15)
Pre-Depends: dash (>= 0.5.5.1-2.2), libc6 (>= 2.15), libtinfo5
Recommends: bash-completion (>= 20060301-0)
Suggests: bash-doc
Conflicts: bash-completion (<< 20060301-0)
Conffiles:
 /etc/bash.bashrc a93b8650846fd2bb653d03bd706f1f47
 /etc/skel/.profile ecb6d3479ac3823f1da7f314d871989b
 /etc/skel/.bash_logout 22bfb8c1dd94b5f3813a2b25da67463f
 /etc/skel/.bashrc f110abe5b3cfd324c2e5128eb4733879
Description: GNU Bourne Again SHell
 Bash is an sh-compatible command language interpreter that executes
 commands read from the standard input or from a file.  Bash also
 incorporates useful features from the Korn and C shells (ksh and csh).
 .
 Bash is ultimately intended to be a conformant implementation of the
 IEEE POSIX Shell and Tools specification (IEEE Working Group 1003.2).
 .
 The Programmable Completion Code, by Ian Macdonald, is now found in
 the bash-completion package.
Homepage: http://tiswww.case.edu/php/chet/bash/bashtop.html
Original-Maintainer: Matthias Klose <doko@debian.org>

```

執行

```
$ dpkg -l bash
```

顯示

```
Desired=Unknown/Install/Remove/Purge/Hold
| Status=Not/Inst/Conf-files/Unpacked/halF-conf/Half-inst/trig-aWait/Trig-pend
|/ Err?=(none)/Reinst-required (Status,Err: uppercase=bad)
||/ Name                         Version             Architecture        Description
+++-============================-===================-===================-==============================================================
ii  bash                         4.3-7ubuntu1.5      amd64               GNU Bourne Again SHell


```


## 準備工作環境

```
mkdir  ~/Downloads/bash -p
cd ~/Downloads/bash
mkdir download source
```

## 探索「Package: [bash](http://packages.ubuntu.com/trusty/bash)」

切換到「~/Downloads/bash/download」

``` sh
$ cd ~/Downloads/bash/download
```

下載「Package: bash」。

``` sh
$ apt-get download bash
```

解開「package bash」

``` sh
dpkg -x bash_4.3-7ubuntu1.5_amd64.deb bash
dpkg -e bash_4.3-7ubuntu1.5_amd64.deb
# ar xv bash_4.3-7ubuntu1.5_amd64.deb
```

檢視套件檔案

``` sh
$ tree bash
```

顯示

```
bash
├── bin
│   ├── bash
│   └── rbash -> bash
├── etc
│   ├── bash.bashrc
│   └── skel
└── usr
    ├── bin
    │   ├── bashbug
    │   └── clear_console
    └── share
        ├── doc
        │   └── bash
        │       ├── changelog.Debian.gz
        │       ├── COMPAT.gz
        │       ├── copyright
        │       ├── inputrc.arrows
        │       ├── INTRO.gz
        │       ├── NEWS.gz
        │       ├── POSIX.gz
        │       ├── RBASH
        │       ├── README
        │       ├── README.abs-guide
        │       ├── README.commands.gz
        │       └── README.Debian.gz
        ├── info
        ├── lintian
        │   └── overrides
        │       └── bash
        ├── man
        │   ├── man1
        │   │   ├── bash.1.gz
        │   │   ├── bashbug.1.gz
        │   │   ├── clear_console.1.gz
        │   │   └── rbash.1.gz
        │   └── man7
        │       └── bash-builtins.7.gz
        └── menu
            └── bash

15 directories, 24 files

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
├── md5sums
├── postinst
├── postrm
├── preinst
└── prerm

0 directories, 7 files


```


## 探索「Source Package: [bash](http://packages.ubuntu.com/source/trusty/bash)」

切換到「~/Downloads/bash/source」

``` sh
$ cd ~/Downloads/bash/source
```

下載「Source Package: bash」。

``` sh
$ apt-get source bash
```

檢視原始碼套件檔案。

```
$ tree bash-4.3
```

顯示

```
bash-4.3
├── ABOUT-NLS
├── aclocal.m4
├── alias.c
├── alias.h
├── array.c
├── arrayfunc.c
├── arrayfunc.h
├── array.h
├── assoc.c
├── assoc.h
├── AUTHORS
├── bashansi.h
├── bashhist.c
├── bashhist.h
├── bashintl.h
├── bashjmp.h
├── bashline.c
├── bashline.h
├── bashtypes.h
├── bracecomp.c
├── braces.c
├── builtins
│   ├── alias.def
│   ├── bashgetopt.c
│   ├── bashgetopt.h
│   ├── bind.def
│   ├── break.def
│   ├── builtin.def
│   ├── caller.def
│   ├── cd.def
│   ├── colon.def
│   ├── command.def
│   ├── common.c
│   ├── common.h
│   ├── complete.def
│   ├── declare.def
│   ├── echo.def
│   ├── enable.def
│   ├── eval.def
│   ├── evalfile.c
│   ├── evalstring.c
│   ├── exec.def
│   ├── exit.def
│   ├── fc.def
│   ├── fg_bg.def
│   ├── gen-helpfiles.c
│   ├── getopt.c
│   ├── getopt.h
│   ├── getopts.def
│   ├── hash.def
│   ├── help.def
│   ├── history.def
│   ├── inlib.def
│   ├── jobs.def
│   ├── kill.def
│   ├── let.def
│   ├── Makefile.in
│   ├── mapfile.def
│   ├── mkbuiltins.c
│   ├── printf.def
│   ├── psize.c
│   ├── psize.sh
│   ├── pushd.def
│   ├── read.def
│   ├── reserved.def
│   ├── return.def
│   ├── setattr.def
│   ├── set.def
│   ├── shift.def
│   ├── shopt.def
│   ├── source.def
│   ├── suspend.def
│   ├── test.def
│   ├── times.def
│   ├── trap.def
│   ├── type.def
│   ├── ulimit.def
│   ├── umask.def
│   └── wait.def
├── builtins.h
├── ChangeLog -> CWRU/changelog
├── CHANGES
├── command.h
├── COMPAT
├── config-bot.h
├── config.h.in
├── config-top.h
├── configure
├── configure.ac
├── conftypes.h
├── copy_cmd.c
├── COPYING
├── cross-build
│   ├── cygwin32.cache
│   ├── opennt.cache
│   └── x86-beos.cache
├── CWRU
│   ├── changelog
│   ├── misc
│   │   ├── bison
│   │   ├── errlist.c
│   │   ├── hpux10-dlfcn.h
│   │   ├── open-files.c
│   │   ├── sigs.c
│   │   └── sigstat.c
│   ├── PLATFORMS
│   ├── README
│   └── sh-redir-hack
├── debian
│   ├── bashbug.1
│   ├── bash-builtins.7
│   ├── bash-doc.doc-base.bash
│   ├── bash-doc.doc-base.bashref
│   ├── bash.menu
│   ├── bash.overrides
│   ├── bash.postinst
│   ├── bash.postrm
│   ├── bash.preinst.c
│   ├── bash.preinst.h
│   ├── bash.preinst-lib.c
│   ├── bash.prerm
│   ├── bash-static.overrides
│   ├── bash-static.postinst
│   ├── bash-static.postrm
│   ├── changelog
│   ├── clear_console.1
│   ├── clear_console.c
│   ├── compat
│   ├── control
│   ├── copyright
│   ├── etc.bash.bashrc
│   ├── etc.inputrc
│   ├── etc.profile
│   ├── FAQ
│   ├── inputrc.arrows
│   ├── locale-gen
│   ├── patches
│   │   ├── bash43-001.diff
│   │   ├── bash43-002.diff
│   │   ├── bash43-003.diff
│   │   ├── bash43-004.diff
│   │   ├── bash43-005.diff
│   │   ├── bash43-006.diff
│   │   ├── bash43-007.diff
│   │   ├── bash43-008.diff
│   │   ├── bash43-009.diff
│   │   ├── bash43-010.diff
│   │   ├── bash43-011.diff
│   │   ├── bash-aliases-repeat.diff
│   │   ├── bashbug-editor.diff
│   │   ├── bash-default-editor.diff
│   │   ├── bash-minimal.dpatch
│   │   ├── bash-subst-param-length.diff
│   │   ├── bzero.diff
│   │   ├── CVE-2014-6271.diff
│   │   ├── CVE-2014-6277.diff
│   │   ├── CVE-2014-6278.diff
│   │   ├── CVE-2014-7169.diff
│   │   ├── CVE-2014-718x.diff
│   │   ├── deb-bash-config.diff
│   │   ├── deb-examples.diff
│   │   ├── exec-redirections-doc.diff
│   │   ├── input-err.diff
│   │   ├── man-arithmetic.diff
│   │   ├── man-bash.diff
│   │   ├── man-bashlogout.diff
│   │   ├── man-bashrc.diff
│   │   ├── man-builtin.dpatch
│   │   ├── man-fignore.diff
│   │   ├── man-nocaseglob.diff
│   │   ├── man-test2.diff
│   │   ├── man-test.diff
│   │   ├── man-vx-opts.dpatch
│   │   ├── no-brk-caching.diff
│   │   ├── pgrp-pipe.diff
│   │   ├── privmode.diff
│   │   ├── random.dpatch
│   │   ├── rbash-manpage.diff
│   │   ├── rl-del-backspace-policy.dpatch
│   │   ├── rl-examples-bdb.dpatch
│   │   ├── rl-header.dpatch
│   │   ├── rl-setenv.dpatch
│   │   ├── series
│   │   ├── use-system-texi2html.diff
│   │   └── variables-affix.diff
│   ├── README
│   ├── README.abs-guide
│   ├── README.bash_completion
│   ├── README.commands
│   ├── rules
│   ├── run-my-gprof
│   ├── skel.bash_logout
│   ├── skel.bashrc
│   ├── skel.profile
│   ├── source
│   │   ├── format
│   │   └── lintian-overrides
│   └── watch
├── dispose_cmd.c
├── dispose_cmd.h
├── doc
│   ├── bash.0
│   ├── bash.1
│   ├── bashbug.0
│   ├── bashbug.1
│   ├── bashbug.ps
│   ├── bash.html
│   ├── bash.pdf
│   ├── bash.ps
│   ├── bashref.dvi
│   ├── bashref.html
│   ├── bashref.info
│   ├── bashref.pdf
│   ├── bashref.ps
│   ├── bashref.texi
│   ├── builtins.0
│   ├── builtins.1
│   ├── builtins.ps
│   ├── fdl.texi
│   ├── fdl.txt
│   ├── htmlpost.sh
│   ├── infopost.sh
│   ├── INTRO
│   ├── Makefile.in
│   ├── rbash.0
│   ├── rbash.1
│   ├── rbash.ps
│   ├── README
│   ├── texinfo.tex
│   └── version.texi
├── error.c
├── error.h
├── eval.c
├── examples
│   ├── complete
│   │   ├── bashcc-1.0.1.tar.gz
│   │   ├── bash_completion
│   │   ├── cdfunc
│   │   └── complete-examples
│   ├── functions
│   │   ├── array-stuff
│   │   ├── array-to-string
│   │   ├── autoload
│   │   ├── autoload.v2
│   │   ├── autoload.v3
│   │   ├── basename
│   │   ├── csh-compat
│   │   ├── dirname
│   │   ├── exitstat
│   │   ├── external
│   │   ├── fact
│   │   ├── fstty
│   │   ├── func
│   │   ├── inetaddr
│   │   ├── inpath
│   │   ├── isnum2
│   │   ├── isvalidip
│   │   ├── ksh-cd
│   │   ├── ksh-compat-test
│   │   ├── kshenv
│   │   ├── login
│   │   ├── notify.bash
│   │   ├── seq
│   │   ├── seq2
│   │   ├── shcat
│   │   ├── shcat2
│   │   ├── sort-pos-params
│   │   ├── substr
│   │   ├── substr2
│   │   ├── whatis
│   │   ├── whence
│   │   └── which
│   ├── INDEX.html
│   ├── INDEX.txt
│   ├── loadables
│   │   ├── basename.c
│   │   ├── cat.c
│   │   ├── dirname.c
│   │   ├── finfo.c
│   │   ├── head.c
│   │   ├── hello.c
│   │   ├── id.c
│   │   ├── ln.c
│   │   ├── logname.c
│   │   ├── Makefile.in
│   │   ├── mkdir.c
│   │   ├── mypid.c
│   │   ├── necho.c
│   │   ├── pathchk.c
│   │   ├── perl
│   │   │   ├── bperl.c
│   │   │   ├── iperl.c
│   │   │   ├── Makefile.in
│   │   │   └── README
│   │   ├── print.c
│   │   ├── printenv.c
│   │   ├── push.c
│   │   ├── README
│   │   ├── realpath.c
│   │   ├── rmdir.c
│   │   ├── sleep.c
│   │   ├── strftime.c
│   │   ├── sync.c
│   │   ├── tee.c
│   │   ├── template.c
│   │   ├── truefalse.c
│   │   ├── tty.c
│   │   ├── uname.c
│   │   ├── unlink.c
│   │   └── whoami.c
│   ├── misc
│   │   ├── aliasconv.bash
│   │   ├── aliasconv.sh
│   │   └── cshtobash
│   ├── scripts
│   │   ├── cat.sh
│   │   ├── center
│   │   ├── inpath
│   │   ├── shprompt
│   │   ├── spin.bash
│   │   ├── xterm_title
│   │   └── zprintf
│   └── startup-files
│       ├── Bash_aliases
│       ├── bash-profile
│       ├── Bash_profile
│       ├── bashrc
│       ├── Bashrc.bfox
│       └── README
├── execute_cmd.c
├── execute_cmd.h
├── expr.c
├── externs.h
├── findcmd.c
├── findcmd.h
├── flags.c
├── flags.h
├── general.c
├── general.h
├── hashcmd.c
├── hashcmd.h
├── hashlib.c
├── hashlib.h
├── include
│   ├── ansi_stdlib.h
│   ├── chartypes.h
│   ├── filecntl.h
│   ├── gettext.h
│   ├── maxpath.h
│   ├── memalloc.h
│   ├── ocache.h
│   ├── posixdir.h
│   ├── posixjmp.h
│   ├── posixselect.h
│   ├── posixstat.h
│   ├── posixtime.h
│   ├── posixwait.h
│   ├── shmbchar.h
│   ├── shmbutil.h
│   ├── shtty.h
│   ├── stat-time.h
│   ├── stdc.h
│   ├── systimes.h
│   ├── typemax.h
│   └── unionwait.h
├── input.c
├── input.h
├── INSTALL
├── jobs.c
├── jobs.h
├── lib
│   ├── glob
│   │   ├── collsyms.h
│   │   ├── doc
│   │   │   ├── glob.texi
│   │   │   └── Makefile
│   │   ├── glob.c
│   │   ├── glob.h
│   │   ├── glob_loop.c
│   │   ├── gmisc.c
│   │   ├── Makefile.in
│   │   ├── ndir.h
│   │   ├── smatch.c
│   │   ├── sm_loop.c
│   │   ├── strmatch.c
│   │   ├── strmatch.h
│   │   └── xmbsrtowcs.c
│   ├── intl
│   │   ├── bindtextdom.c
│   │   ├── ChangeLog
│   │   ├── config.charset
│   │   ├── dcgettext.c
│   │   ├── dcigettext.c
│   │   ├── dcngettext.c
│   │   ├── dgettext.c
│   │   ├── dngettext.c
│   │   ├── eval-plural.h
│   │   ├── explodename.c
│   │   ├── finddomain.c
│   │   ├── gettext.c
│   │   ├── gettextP.h
│   │   ├── gmo.h
│   │   ├── hash-string.h
│   │   ├── intl-compat.c
│   │   ├── l10nflist.c
│   │   ├── libgnuintl.h.in
│   │   ├── loadinfo.h
│   │   ├── loadmsgcat.c
│   │   ├── localcharset.c
│   │   ├── localcharset.h
│   │   ├── locale.alias
│   │   ├── localealias.c
│   │   ├── localename.c
│   │   ├── log.c
│   │   ├── Makefile.in
│   │   ├── ngettext.c
│   │   ├── os2compat.c
│   │   ├── os2compat.h
│   │   ├── osdep.c
│   │   ├── plural.c
│   │   ├── plural-exp.c
│   │   ├── plural-exp.h
│   │   ├── plural.y
│   │   ├── ref-add.sin
│   │   ├── ref-del.sin
│   │   ├── relocatable.c
│   │   ├── relocatable.h
│   │   ├── textdomain.c
│   │   └── VERSION
│   ├── malloc
│   │   ├── alloca.c
│   │   ├── getpagesize.h
│   │   ├── i386-alloca.s
│   │   ├── imalloc.h
│   │   ├── Makefile.in
│   │   ├── malloc.c
│   │   ├── mstats.h
│   │   ├── shmalloc.h
│   │   ├── stats.c
│   │   ├── stub.c
│   │   ├── table.c
│   │   ├── table.h
│   │   ├── trace.c
│   │   ├── watch.c
│   │   ├── watch.h
│   │   ├── x386-alloca.s
│   │   ├── xleaktrace
│   │   └── xmalloc.c
│   ├── readline
│   │   ├── ansi_stdlib.h
│   │   ├── bind.c
│   │   ├── callback.c
│   │   ├── ChangeLog
│   │   ├── chardefs.h
│   │   ├── colors.c
│   │   ├── colors.h
│   │   ├── compat.c
│   │   ├── complete.c
│   │   ├── COPYING
│   │   ├── display.c
│   │   ├── doc
│   │   │   ├── fdl.texi
│   │   │   ├── history.texi
│   │   │   ├── hstech.texi
│   │   │   ├── hsuser.texi
│   │   │   ├── Makefile
│   │   │   ├── rlman.texi
│   │   │   ├── rltech.texi
│   │   │   ├── rluserman.texi
│   │   │   ├── rluser.texi
│   │   │   └── version.texi
│   │   ├── emacs_keymap.c
│   │   ├── examples
│   │   │   ├── excallback.c
│   │   │   ├── fileman.c
│   │   │   ├── histexamp.c
│   │   │   ├── Inputrc
│   │   │   ├── Makefile
│   │   │   ├── manexamp.c
│   │   │   ├── rl.c
│   │   │   ├── rl-callbacktest.c
│   │   │   ├── rlcat.c
│   │   │   └── rltest.c
│   │   ├── funmap.c
│   │   ├── histexpand.c
│   │   ├── histfile.c
│   │   ├── histlib.h
│   │   ├── history.c
│   │   ├── history.h
│   │   ├── histsearch.c
│   │   ├── input.c
│   │   ├── isearch.c
│   │   ├── keymaps.c
│   │   ├── keymaps.h
│   │   ├── kill.c
│   │   ├── macro.c
│   │   ├── Makefile.in
│   │   ├── mbutil.c
│   │   ├── misc.c
│   │   ├── nls.c
│   │   ├── parens.c
│   │   ├── parse-colors.c
│   │   ├── parse-colors.h
│   │   ├── posixdir.h
│   │   ├── posixjmp.h
│   │   ├── posixselect.h
│   │   ├── posixstat.h
│   │   ├── readline.c
│   │   ├── readline.h
│   │   ├── README
│   │   ├── rlconf.h
│   │   ├── rldefs.h
│   │   ├── rlmbutil.h
│   │   ├── rlprivate.h
│   │   ├── rlshell.h
│   │   ├── rlstdc.h
│   │   ├── rltty.c
│   │   ├── rltty.h
│   │   ├── rltypedefs.h
│   │   ├── rlwinsize.h
│   │   ├── savestring.c
│   │   ├── search.c
│   │   ├── shell.c
│   │   ├── signals.c
│   │   ├── STANDALONE
│   │   ├── tcap.h
│   │   ├── terminal.c
│   │   ├── text.c
│   │   ├── tilde.c
│   │   ├── tilde.h
│   │   ├── undo.c
│   │   ├── util.c
│   │   ├── vi_keymap.c
│   │   ├── vi_mode.c
│   │   ├── xfree.c
│   │   ├── xmalloc.c
│   │   └── xmalloc.h
│   ├── sh
│   │   ├── casemod.c
│   │   ├── clktck.c
│   │   ├── clock.c
│   │   ├── dprintf.c
│   │   ├── eaccess.c
│   │   ├── fmtullong.c
│   │   ├── fmtulong.c
│   │   ├── fmtumax.c
│   │   ├── fnxform.c
│   │   ├── fpurge.c
│   │   ├── getcwd.c
│   │   ├── getenv.c
│   │   ├── inet_aton.c
│   │   ├── input_avail.c
│   │   ├── itos.c
│   │   ├── mailstat.c
│   │   ├── Makefile.in
│   │   ├── makepath.c
│   │   ├── mbscasecmp.c
│   │   ├── mbschr.c
│   │   ├── mbscmp.c
│   │   ├── memset.c
│   │   ├── mktime.c
│   │   ├── netconn.c
│   │   ├── netopen.c
│   │   ├── oslib.c
│   │   ├── pathcanon.c
│   │   ├── pathphys.c
│   │   ├── rename.c
│   │   ├── setlinebuf.c
│   │   ├── shmatch.c
│   │   ├── shmbchar.c
│   │   ├── shquote.c
│   │   ├── shtty.c
│   │   ├── snprintf.c
│   │   ├── spell.c
│   │   ├── strcasecmp.c
│   │   ├── strcasestr.c
│   │   ├── strchrnul.c
│   │   ├── strdup.c
│   │   ├── strerror.c
│   │   ├── strftime.c
│   │   ├── stringlist.c
│   │   ├── stringvec.c
│   │   ├── strnlen.c
│   │   ├── strpbrk.c
│   │   ├── strstr.c
│   │   ├── strtod.c
│   │   ├── strtoimax.c
│   │   ├── strtol.c
│   │   ├── strtoll.c
│   │   ├── strtoul.c
│   │   ├── strtoull.c
│   │   ├── strtoumax.c
│   │   ├── strtrans.c
│   │   ├── times.c
│   │   ├── timeval.c
│   │   ├── tmpfile.c
│   │   ├── uconvert.c
│   │   ├── ufuncs.c
│   │   ├── unicode.c
│   │   ├── vprint.c
│   │   ├── wcsdup.c
│   │   ├── wcsnwidth.c
│   │   ├── wcswidth.c
│   │   ├── winsize.c
│   │   ├── zcatfd.c
│   │   ├── zgetline.c
│   │   ├── zmapfd.c
│   │   ├── zread.c
│   │   └── zwrite.c
│   ├── termcap
│   │   ├── ltcap.h
│   │   ├── Makefile.in
│   │   ├── termcap.c
│   │   ├── termcap.h
│   │   ├── tparam.c
│   │   └── version.c
│   └── tilde
│       ├── Makefile.in
│       ├── README
│       ├── shell.c
│       ├── tilde.c
│       └── tilde.h
├── list.c
├── locale.c
├── m4
│   ├── stat-time.m4
│   └── timespec.m4
├── mailcheck.c
├── mailcheck.h
├── make_cmd.c
├── make_cmd.h
├── Makefile.in
├── MANIFEST
├── mksyntax.c
├── NEWS
├── nojobs.c
├── NOTES
├── parser-built
├── parser.h
├── parse.y
├── patchlevel.h
├── pathexp.c
├── pathexp.h
├── pathnames.h.in
├── pcomplete.c
├── pcomplete.h
├── pcomplib.c
├── po
│   ├── af.gmo
│   ├── af.po
│   ├── bash.pot
│   ├── bg.gmo
│   ├── bg.po
│   ├── boldquot.sed
│   ├── ca.gmo
│   ├── ca.po
│   ├── cs.gmo
│   ├── cs.po
│   ├── da.gmo
│   ├── da.po
│   ├── de.gmo
│   ├── de.po
│   ├── el.gmo
│   ├── el.po
│   ├── en@boldquot.gmo
│   ├── en@boldquot.header
│   ├── en@boldquot.po
│   ├── en@quot.gmo
│   ├── en@quot.header
│   ├── en@quot.po
│   ├── eo.gmo
│   ├── eo.po
│   ├── es.gmo
│   ├── es.po
│   ├── et.gmo
│   ├── et.po
│   ├── fi.gmo
│   ├── fi.po
│   ├── fr.gmo
│   ├── fr.po
│   ├── ga.gmo
│   ├── ga.po
│   ├── gl.gmo
│   ├── gl.po
│   ├── hr.gmo
│   ├── hr.po
│   ├── hu.gmo
│   ├── hu.po
│   ├── id.gmo
│   ├── id.po
│   ├── insert-header.sin
│   ├── it.gmo
│   ├── it.po
│   ├── ja.gmo
│   ├── ja.po
│   ├── LINGUAS
│   ├── lt.gmo
│   ├── lt.po
│   ├── Makefile.in.in
│   ├── Makevars
│   ├── nl.gmo
│   ├── nl.po
│   ├── pl.gmo
│   ├── pl.po
│   ├── POTFILES.in
│   ├── pt_BR.gmo
│   ├── pt_BR.po
│   ├── quot.sed
│   ├── README
│   ├── remove-potcdate.sin
│   ├── ro.gmo
│   ├── ro.po
│   ├── ru.gmo
│   ├── Rules-builtins
│   ├── Rules-quot
│   ├── ru.po
│   ├── sk.gmo
│   ├── sk.po
│   ├── sl.gmo
│   ├── sl.po
│   ├── sr.gmo
│   ├── sr.po
│   ├── sv.gmo
│   ├── sv.po
│   ├── tr.gmo
│   ├── tr.po
│   ├── uk.gmo
│   ├── uk.po
│   ├── vi.gmo
│   ├── vi.po
│   ├── zh_CN.gmo
│   ├── zh_CN.po
│   ├── zh_TW.gmo
│   └── zh_TW.po
├── POSIX
├── print_cmd.c
├── quit.h
├── RBASH
├── README
├── redir.c
├── redir.h
├── shell.c
├── shell.h
├── sig.c
├── sig.h
├── siglist.c
├── siglist.h
├── stringlib.c
├── subst.c
├── subst.h
├── support
│   ├── bashbug.sh
│   ├── bashversion.c
│   ├── bash.xbm
│   ├── checkbashisms
│   ├── config.guess
│   ├── config.rpath
│   ├── config.sub
│   ├── fixlinks
│   ├── install.sh
│   ├── Makefile.in
│   ├── man2html.c
│   ├── missing
│   ├── mkclone
│   ├── mkconffiles
│   ├── mkdirs
│   ├── mkinstalldirs
│   ├── mksignames.c
│   ├── mkversion.sh
│   ├── printenv.c
│   ├── printenv.sh
│   ├── recho.c
│   ├── rlvers.sh
│   ├── shobj-conf
│   ├── signames.c
│   ├── SYMLINKS
│   ├── texi2dvi
│   ├── texi2html
│   ├── xcase.c
│   ├── xenix-link.sh
│   └── zecho.c
├── syntax.h
├── test.c
├── test.h
├── tests
│   ├── alias1.sub
│   ├── alias.right
│   ├── alias.tests
│   ├── appendop1.sub
│   ├── appendop2.sub
│   ├── appendop.right
│   ├── appendop.tests
│   ├── arith1.sub
│   ├── arith2.sub
│   ├── arith3.sub
│   ├── arith4.sub
│   ├── arith5.sub
│   ├── arith6.sub
│   ├── arith-for.right
│   ├── arith-for.tests
│   ├── arith.right
│   ├── arith.tests
│   ├── array10.sub
│   ├── array11.sub
│   ├── array12.sub
│   ├── array13.sub
│   ├── array14.sub
│   ├── array15.sub
│   ├── array16.sub
│   ├── array1.sub
│   ├── array2.right
│   ├── array2.sub
│   ├── array3.sub
│   ├── array4.sub
│   ├── array5.sub
│   ├── array6.sub
│   ├── array7.sub
│   ├── array8.sub
│   ├── array9.sub
│   ├── array-at-star
│   ├── array.right
│   ├── array.tests
│   ├── assoc1.sub
│   ├── assoc2.sub
│   ├── assoc3.sub
│   ├── assoc4.sub
│   ├── assoc5.sub
│   ├── assoc6.sub
│   ├── assoc7.sub
│   ├── assoc.right
│   ├── assoc.tests
│   ├── braces.right
│   ├── braces.tests
│   ├── builtins1.sub
│   ├── builtins2.sub
│   ├── builtins3.sub
│   ├── builtins4.sub
│   ├── builtins.right
│   ├── builtins.tests
│   ├── case1.sub
│   ├── casemod.right
│   ├── casemod.tests
│   ├── case.right
│   ├── case.tests
│   ├── comsub1.sub
│   ├── comsub-eof0.sub
│   ├── comsub-eof1.sub
│   ├── comsub-eof2.sub
│   ├── comsub-eof3.sub
│   ├── comsub-eof4.sub
│   ├── comsub-eof5.sub
│   ├── comsub-eof.right
│   ├── comsub-eof.tests
│   ├── comsub-posix1.sub
│   ├── comsub-posix2.sub
│   ├── comsub-posix3.sub
│   ├── comsub-posix.right
│   ├── comsub-posix.tests
│   ├── comsub.right
│   ├── comsub.tests
│   ├── cond-regexp1.sub
│   ├── cond-regexp2.sub
│   ├── cond-regexp3.sub
│   ├── cond.right
│   ├── cond.tests
│   ├── coproc.right
│   ├── coproc.tests
│   ├── COPYRIGHT
│   ├── cprint.right
│   ├── cprint.tests
│   ├── dbg-support2.right
│   ├── dbg-support2.tests
│   ├── dbg-support3.sub
│   ├── dbg-support.right
│   ├── dbg-support.sub
│   ├── dbg-support.tests
│   ├── dollar-at1.sub
│   ├── dollar-at2.sub
│   ├── dollar-at3.sub
│   ├── dollar-at4.sub
│   ├── dollar-at5.sub
│   ├── dollar-at6.sub
│   ├── dollar-at-star
│   ├── dollar-at-star1.sub
│   ├── dollar.right
│   ├── dollar-star1.sub
│   ├── dollar-star2.sub
│   ├── dollar-star3.sub
│   ├── dollar-star4.sub
│   ├── dollar-star5.sub
│   ├── dollar-star6.sub
│   ├── dollar-star7.sub
│   ├── dstack2.right
│   ├── dstack2.tests
│   ├── dstack.right
│   ├── dstack.tests
│   ├── errors1.sub
│   ├── errors2.sub
│   ├── errors3.sub
│   ├── errors.right
│   ├── errors.tests
│   ├── exec1.sub
│   ├── exec2.sub
│   ├── exec3.sub
│   ├── exec4.sub
│   ├── exec5.sub
│   ├── exec6.sub
│   ├── exec7.sub
│   ├── exec8.sub
│   ├── exec9.sub
│   ├── exec.right
│   ├── execscript
│   ├── exp1.sub
│   ├── exp2.sub
│   ├── exp3.sub
│   ├── exp4.sub
│   ├── exp5.sub
│   ├── exp6.sub
│   ├── exp.right
│   ├── exp.tests
│   ├── extglob1a.sub
│   ├── extglob1.sub
│   ├── extglob2.right
│   ├── extglob2.tests
│   ├── extglob3.right
│   ├── extglob3.tests
│   ├── extglob.right
│   ├── extglob.tests
│   ├── func1.sub
│   ├── func2.sub
│   ├── func3.sub
│   ├── func4.sub
│   ├── func.right
│   ├── func.tests
│   ├── getopts1.sub
│   ├── getopts2.sub
│   ├── getopts3.sub
│   ├── getopts4.sub
│   ├── getopts5.sub
│   ├── getopts6.sub
│   ├── getopts7.sub
│   ├── getopts.right
│   ├── getopts.tests
│   ├── glob1.sub
│   ├── glob.right
│   ├── globstar1.sub
│   ├── globstar2.sub
│   ├── globstar.right
│   ├── globstar.tests
│   ├── glob.tests
│   ├── heredoc1.sub
│   ├── heredoc2.sub
│   ├── heredoc3.sub
│   ├── heredoc.right
│   ├── heredoc.tests
│   ├── herestr.right
│   ├── herestr.tests
│   ├── histexp.right
│   ├── histexp.tests
│   ├── history1.sub
│   ├── history2.sub
│   ├── history.list
│   ├── history.right
│   ├── history.tests
│   ├── ifs-posix.right
│   ├── ifs-posix.tests
│   ├── ifs.right
│   ├── ifs.tests
│   ├── input-line.sh
│   ├── input-line.sub
│   ├── input.right
│   ├── intl1.sub
│   ├── intl2.sub
│   ├── intl.right
│   ├── intl.tests
│   ├── invert.right
│   ├── invert.tests
│   ├── iquote1.sub
│   ├── iquote.right
│   ├── iquote.tests
│   ├── jobs1.sub
│   ├── jobs2.sub
│   ├── jobs3.sub
│   ├── jobs4.sub
│   ├── jobs5.sub
│   ├── jobs.right
│   ├── jobs.tests
│   ├── lastpipe1.sub
│   ├── lastpipe.right
│   ├── lastpipe.tests
│   ├── mapfile1.sub
│   ├── mapfile.data
│   ├── mapfile.right
│   ├── mapfile.tests
│   ├── misc
│   │   ├── dev-tcp.tests
│   │   ├── perf-script
│   │   ├── perftest
│   │   ├── read-nchars.tests
│   │   ├── redir-t2.sh
│   │   ├── run-r2.sh
│   │   ├── sigint-1.sh
│   │   ├── sigint-2.sh
│   │   ├── sigint-3.sh
│   │   ├── sigint-4.sh
│   │   ├── test-minus-e.1
│   │   ├── test-minus-e.2
│   │   └── wait-bg.tests
│   ├── more-exp.right
│   ├── more-exp.tests
│   ├── nameref1.sub
│   ├── nameref2.sub
│   ├── nameref3.sub
│   ├── nameref4.sub
│   ├── nameref5.sub
│   ├── nameref6.sub
│   ├── nameref7.sub
│   ├── nameref8.sub
│   ├── nameref.right
│   ├── nameref.tests
│   ├── new-exp1.sub
│   ├── new-exp2.sub
│   ├── new-exp3.sub
│   ├── new-exp4.sub
│   ├── new-exp5.sub
│   ├── new-exp6.sub
│   ├── new-exp7.sub
│   ├── new-exp8.sub
│   ├── new-exp9.sub
│   ├── new-exp.right
│   ├── new-exp.tests
│   ├── nquote1.right
│   ├── nquote1.sub
│   ├── nquote1.tests
│   ├── nquote2.right
│   ├── nquote2.sub
│   ├── nquote2.tests
│   ├── nquote3.right
│   ├── nquote3.tests
│   ├── nquote4.right
│   ├── nquote4.tests
│   ├── nquote5.right
│   ├── nquote5.tests
│   ├── nquote.right
│   ├── nquote.tests
│   ├── posix2.right
│   ├── posix2.tests
│   ├── posixexp1.sub
│   ├── posixexp2.right
│   ├── posixexp2.sub
│   ├── posixexp2.tests
│   ├── posixexp.right
│   ├── posixexp.tests
│   ├── posixpat.right
│   ├── posixpat.tests
│   ├── posixpipe.right
│   ├── posixpipe.tests
│   ├── precedence
│   ├── prec.right
│   ├── printf1.sub
│   ├── printf2.sub
│   ├── printf3.sub
│   ├── printf4.sub
│   ├── printf.right
│   ├── printf.tests
│   ├── quote1.sub
│   ├── quote.right
│   ├── quote.tests
│   ├── read1.sub
│   ├── read2.sub
│   ├── read3.sub
│   ├── read4.sub
│   ├── read5.sub
│   ├── read6.sub
│   ├── README
│   ├── read.right
│   ├── read.tests
│   ├── redir10.sub
│   ├── redir1.sub
│   ├── redir2.sub
│   ├── redir3.in1
│   ├── redir3.in2
│   ├── redir3.sub
│   ├── redir4.in1
│   ├── redir4.sub
│   ├── redir5.sub
│   ├── redir6.sub
│   ├── redir7.sub
│   ├── redir8.sub
│   ├── redir9.sub
│   ├── redir.right
│   ├── redir.tests
│   ├── rhs-exp1.sub
│   ├── rhs-exp.right
│   ├── rhs-exp.tests
│   ├── rsh.right
│   ├── rsh.tests
│   ├── run-alias
│   ├── run-all
│   ├── run-appendop
│   ├── run-arith
│   ├── run-arith-for
│   ├── run-array
│   ├── run-array2
│   ├── run-assoc
│   ├── run-braces
│   ├── run-builtins
│   ├── run-case
│   ├── run-casemod
│   ├── run-comsub
│   ├── run-comsub-eof
│   ├── run-comsub-posix
│   ├── run-cond
│   ├── run-coproc
│   ├── run-cprint
│   ├── run-dbg-support
│   ├── run-dbg-support2
│   ├── run-dirstack
│   ├── run-dollars
│   ├── run-errors
│   ├── run-execscript
│   ├── run-exp-tests
│   ├── run-extglob
│   ├── run-extglob2
│   ├── run-extglob3
│   ├── run-func
│   ├── run-getopts
│   ├── run-globstar
│   ├── run-glob-test
│   ├── run-heredoc
│   ├── run-herestr
│   ├── run-histexpand
│   ├── run-history
│   ├── run-ifs
│   ├── run-ifs-posix
│   ├── run-input-test
│   ├── run-intl
│   ├── run-invert
│   ├── run-iquote
│   ├── run-jobs
│   ├── run-lastpipe
│   ├── run-mapfile
│   ├── run-minimal
│   ├── run-more-exp
│   ├── run-nameref
│   ├── run-new-exp
│   ├── run-nquote
│   ├── run-nquote1
│   ├── run-nquote2
│   ├── run-nquote3
│   ├── run-nquote4
│   ├── run-nquote5
│   ├── run-posix2
│   ├── run-posixexp
│   ├── run-posixexp2
│   ├── run-posixpat
│   ├── run-posixpipe
│   ├── run-precedence
│   ├── run-printf
│   ├── run-quote
│   ├── run-read
│   ├── run-redir
│   ├── run-rhs-exp
│   ├── run-rsh
│   ├── run-set-e
│   ├── run-set-x
│   ├── run-shopt
│   ├── run-strip
│   ├── run-test
│   ├── run-tilde
│   ├── run-tilde2
│   ├── run-trap
│   ├── run-type
│   ├── run-varenv
│   ├── run-vredir
│   ├── set-e1.sub
│   ├── set-e2.sub
│   ├── set-e3a.sub
│   ├── set-e3.sub
│   ├── set-e.right
│   ├── set-e.tests
│   ├── set-x1.sub
│   ├── set-x.right
│   ├── set-x.tests
│   ├── shopt.right
│   ├── shopt.tests
│   ├── source1.sub
│   ├── source2.sub
│   ├── source3.sub
│   ├── source4.sub
│   ├── source5.sub
│   ├── source6.sub
│   ├── source7.sub
│   ├── strip.right
│   ├── strip.tests
│   ├── test.right
│   ├── test.tests
│   ├── tilde2.right
│   ├── tilde2.tests
│   ├── tilde.right
│   ├── tilde.tests
│   ├── trap1.sub
│   ├── trap2a.sub
│   ├── trap2.sub
│   ├── trap3.sub
│   ├── trap4.sub
│   ├── trap5.sub
│   ├── trap.right
│   ├── trap.tests
│   ├── type1.sub
│   ├── type2.sub
│   ├── type3.sub
│   ├── type4.sub
│   ├── type.right
│   ├── type.tests
│   ├── unicode1.sub
│   ├── unicode2.sub
│   ├── unicode3.sub
│   ├── varenv1.sub
│   ├── varenv2.sub
│   ├── varenv3.sub
│   ├── varenv4.sub
│   ├── varenv5.sub
│   ├── varenv6.sub
│   ├── varenv.right
│   ├── varenv.sh
│   ├── version
│   ├── version.mini
│   ├── vredir1.sub
│   ├── vredir2.sub
│   ├── vredir3.sub
│   ├── vredir4.sub
│   ├── vredir5.sub
│   ├── vredir6.sub
│   ├── vredir.right
│   └── vredir.tests
├── trap.c
├── trap.h
├── unwind_prot.c
├── unwind_prot.h
├── variables.c
├── variables.h
├── version.c
├── xmalloc.c
├── xmalloc.h
├── Y2K
├── y.tab.c
└── y.tab.h

33 directories, 1215 files

```
