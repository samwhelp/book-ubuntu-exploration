# locate info


## 套件資訊

執行

```
$ apt-cache show locate
```

顯示

```
Package: locate
Priority: optional
Section: universe/utils
Installed-Size: 370
Maintainer: Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Original-Maintainer: Andreas Metzler <ametzler@debian.org>
Architecture: amd64
Source: findutils
Version: 4.4.2-7
Replaces: findutils (<< 4.2.31-2)
Depends: libc6 (>= 2.14), findutils (>> 4.2.31-1)
Conflicts: slocate (<= 3.1-1.1)
Filename: pool/universe/f/findutils/locate_4.4.2-7_amd64.deb
Size: 81302
MD5sum: a75546212c7a33f4b3ed79d5482d8e90
SHA1: 3d340248b4d0796fcbe882fea31bf927403e53b4
SHA256: b7acbdb5dce6bf6965bad04beb229c728bdf220ffa47861dd0869e5f19dae248
Description-en: maintain and query an index of a directory tree
 updatedb generates an index of files and directories. GNU locate can be used
 to quickly query this index.
Description-md5: bff4cb1129be08196a6ed2311b3d1fbc
Multi-Arch: foreign
Homepage: http://savannah.gnu.org/projects/findutils/
Bugs: https://bugs.launchpad.net/ubuntu/+filebug
Origin: Ubuntu
Supported: 9m
```

執行

```
$ apt-cache showpkg locate
```

顯示

```
Package: locate
Versions:
4.4.2-7 (/var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_universe_binary-amd64_Packages)
 Description Language:
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_universe_binary-amd64_Packages
                  MD5: bff4cb1129be08196a6ed2311b3d1fbc
 Description Language: en
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_universe_i18n_Translation-en
                  MD5: bff4cb1129be08196a6ed2311b3d1fbc


Reverse Depends:
  locate:i386,locate
  xfce4-linelight-plugin,locate
  texmacs,locate
  phatch-cli,locate
  gnome-do-plugins,locate
  catfish,locate
  findutils,locate
Dependencies:
4.4.2-7 - libc6 (2 2.14) findutils (4 4.2.31-1) slocate (1 3.1-1.1) slocate:i386 (1 3.1-1.1) findutils (3 4.2.31-2) findutils:i386 (3 4.2.31-2) locate:i386 (0 (null))
Provides:
4.4.2-7 - locate:i386
Reverse Provides:
locate:i386 4.4.2-7


```

執行

```
$ apt-cache showsrc locate
```

顯示

```
Package: findutils
Binary: findutils, locate
Version: 4.4.2-7
Priority: required
Section: utils
Maintainer: Andreas Metzler <ametzler@debian.org>
Build-Depends: texinfo, debhelper (>= 9), autotools-dev, dejagnu, bison
Architecture: any
Standards-Version: 3.9.4
Format: 3.0 (quilt)
Directory: pool/main/f/findutils
Files:
 5de434a0f2f36fdfec0c6ccaff30d8cb 1967 findutils_4.4.2-7.dsc
 351cc4adb07d54877fa15f75fb77d39f 2149838 findutils_4.4.2.orig.tar.gz
 1ae4d3ba270cf256089cc3d1918932dc 25449 findutils_4.4.2-7.debian.tar.gz
Uploaders: Chuan-kai Lin <cklin@debian.org>
Homepage: http://savannah.gnu.org/projects/findutils/
Vcs-Browser: http://svn.debian.org/wsvn/pkg-findutils/trunk/
Vcs-Svn: svn://svn.debian.org/svn/pkg-findutils/trunk
Package-List:
 findutils deb utils required
 locate deb utils optional
Checksums-Sha1:
 fde0c5456e5b5b1258fa357831af393ced4d1591 1967 findutils_4.4.2-7.dsc
 e8dd88fa2cc58abffd0bfc1eddab9020231bb024 2149838 findutils_4.4.2.orig.tar.gz
 fc40339addfbc3e3f08225e44ce64d13e76edfd7 25449 findutils_4.4.2-7.debian.tar.gz
Checksums-Sha256:
 02cfd094ec168a2a1604822a6012fda1525a792d9834112e09293ec11ebfaae0 1967 findutils_4.4.2-7.dsc
 434f32d171cbc0a5e72cfc5372c6fc4cb0e681f8dce566a0de5b6fccd702b62a 2149838 findutils_4.4.2.orig.tar.gz
 251b00023cab27e8d85b3844f1c69f009319d34d33aa4a996b183056c3cfe48a 25449 findutils_4.4.2-7.debian.tar.gz

```

執行

```
$ dpkg -s locate
```

顯示

```
dpkg-query: package 'locate' is not installed and no information is available
Use dpkg --info (= dpkg-deb --info) to examine archive files,
and dpkg --contents (= dpkg-deb --contents) to list their contents.

```

執行

```
$ dpkg -l locate
```

顯示

```
Desired=Unknown/Install/Remove/Purge/Hold
| Status=Not/Inst/Conf-files/Unpacked/halF-conf/Half-inst/trig-aWait/Trig-pend
|/ Err?=(none)/Reinst-required (Status,Err: uppercase=bad)
||/ Name                         Version             Architecture        Description
+++-============================-===================-===================-==============================================================
un  locate                       <none>              <none>              (no description available)


```


## 準備工作環境

```
mkdir  ~/Downloads/locate -p
cd ~/Downloads/locate
mkdir download source
```

## 探索「Package: [locate](http://packages.ubuntu.com/trusty/locate)」

切換到「~/Downloads/locate/download」

``` sh
$ cd ~/Downloads/locate/download
```

下載「Package: locate」。

``` sh
$ apt-get download locate
```

解開「package sudo」

``` sh
dpkg -x locate_4.4.2-7_amd64.deb locate
dpkg -e locate_4.4.2-7_amd64.deb
# ar xv locate_4.4.2-7_amd64.deb
```

檢視套件檔案

``` sh
tree locate
```

顯示

```
locate
├── etc
│   └── cron.daily
│       └── locate
├── usr
│   ├── bin
│   │   ├── locate.findutils
│   │   └── updatedb.findutils
│   ├── lib
│   │   └── locate
│   │       ├── bigram
│   │       ├── code
│   │       └── frcode
│   └── share
│       ├── doc
│       │   └── locate
│       │       ├── changelog.Debian.gz -> ../findutils/changelog.Debian.gz
│       │       ├── copyright
│       │       └── README.Debian
│       └── man
│           ├── man1
│           │   ├── locate.findutils.1.gz
│           │   └── updatedb.findutils.1.gz
│           └── man5
│               └── locatedb.5.gz
└── var
    └── cache
        └── locate

15 directories, 12 files


```

```
tree DEBIAN
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


## 探索「Source Package: [locate](http://packages.ubuntu.com/trusty/locate)」

切換到「~/Downloads/locate/source」

``` sh
$ cd ~/Downloads/locate/source
```

下載「Source Package: locate」。

``` sh
$ apt-get source locate
```

檢視原始碼套件檔案。

```
$ tree findutils-4.4.2
```

顯示

```
locate-4.4.2
├── ABOUT-NLS
├── aclocal.m4
├── AUTHORS
├── build-aux
│   ├── check-testfiles.sh
│   ├── compile
│   ├── config.guess
│   ├── config.rpath
│   ├── config.sub
│   ├── depcomp
│   ├── install-sh
│   ├── link-warning.h
│   ├── Makefile.am
│   ├── Makefile.in
│   ├── man-lint.sh
│   ├── mdate-sh
│   ├── missing
│   ├── mkinstalldirs
│   ├── texinfo.tex
│   └── ylwrap
├── ChangeLog
├── config.h.in
├── configure
├── configure.ac
├── COPYING
├── debian
│   ├── changelog
│   ├── clean
│   ├── compat
│   ├── control
│   ├── copyright
│   ├── locate.doc-base
│   ├── locate.docs
│   ├── locate.info
│   ├── locate.install
│   ├── locate.links
│   ├── locate.manpages
│   ├── locate.NEWS
│   ├── locate.postinst
│   ├── locate.preinst
│   ├── locate.cron.daily
│   ├── locate.dirs
│   ├── locate.install
│   ├── locate.manpages
│   ├── locate.postinst
│   ├── locate.postrm
│   ├── locate.preinst
│   ├── locate.prerm
│   ├── locate.README.debian
│   ├── patches
│   │   ├── 10_Fix29828-testsuite-FreeBSD.patch
│   │   ├── 20_texi_ftbfs.diff
│   │   ├── 21-Fix-time_t-vs-long-int-mismatches.patch
│   │   └── series
│   ├── rules
│   ├── source
│   │   └── format
│   └── watch
├── doc
│   ├── fdl.texi
│   ├── find.info
│   ├── find-maint.info
│   ├── find-maint.texi
│   ├── find.texi
│   ├── getdate.texi
│   ├── Makefile.am
│   ├── Makefile.in
│   ├── mdate-sh
│   ├── perm.texi
│   ├── regexprops.texi
│   ├── stamp-1
│   ├── stamp-vti
│   ├── texinfo.tex
│   ├── versionmaint.texi
│   └── version.texi
├── find
│   ├── defs.h
│   ├── find.1
│   ├── find.c
│   ├── finddata.c
│   ├── fstype.c
│   ├── ftsfind.c
│   ├── Makefile.am
│   ├── Makefile.in
│   ├── parser.c
│   ├── pred.c
│   ├── testsuite
│   │   ├── config
│   │   │   └── unix.exp
│   │   ├── find.gnu
│   │   │   ├── access.exp
│   │   │   ├── access.xo
│   │   │   ├── comma.exp
│   │   │   ├── comma.xo
│   │   │   ├── deletedir.exp
│   │   │   ├── deletedir.xo
│   │   │   ├── delete.exp
│   │   │   ├── deletefile.exp
│   │   │   ├── deletefile.xo
│   │   │   ├── delete.xo
│   │   │   ├── depth-d.exp
│   │   │   ├── depth-d.xo
│   │   │   ├── depth.exp
│   │   │   ├── depth.xo
│   │   │   ├── empty.exp
│   │   │   ├── empty.xo
│   │   │   ├── execdir-hier.exp
│   │   │   ├── execdir-hier.xo
│   │   │   ├── execdir-in-unreadable.exp
│   │   │   ├── execdir-one.exp
│   │   │   ├── execdir-one.xo
│   │   │   ├── execdir-pwd.exp
│   │   │   ├── execdir-root-only.exp
│   │   │   ├── execdir-root-only.xo
│   │   │   ├── exec-many-rtn-failure.exp
│   │   │   ├── exec-many-rtn-failure.xo
│   │   │   ├── exec-many-rtn-success.exp
│   │   │   ├── exec-many-rtn-success.xo
│   │   │   ├── exec-one-rtn-fail.exp
│   │   │   ├── exec-one-rtn-fail.xo
│   │   │   ├── exec-one-rtn-success.exp
│   │   │   ├── exec-one-rtn-success.xo
│   │   │   ├── false.exp
│   │   │   ├── false.xo
│   │   │   ├── follow-arg-parent-symlink.exp
│   │   │   ├── follow-arg-parent-symlink.xo
│   │   │   ├── follow-basic.exp
│   │   │   ├── follow-basic.xo
│   │   │   ├── fprint0_stdout.exp
│   │   │   ├── fprint0_stdout.xo
│   │   │   ├── fprint-unwritable.exp
│   │   │   ├── gnuand.exp
│   │   │   ├── gnuand.xo
│   │   │   ├── gnunot.exp
│   │   │   ├── gnunot.xo
│   │   │   ├── gnu-or.exp
│   │   │   ├── gnu-or.xo
│   │   │   ├── ilname.exp
│   │   │   ├── ilname.xo
│   │   │   ├── iname.exp
│   │   │   ├── iname.xo
│   │   │   ├── inum.exp
│   │   │   ├── inum.xo
│   │   │   ├── ipath.exp
│   │   │   ├── ipath.xo
│   │   │   ├── iregex1.exp
│   │   │   ├── iregex1.xo
│   │   │   ├── iwholename.exp
│   │   │   ├── iwholename.xo
│   │   │   ├── lname.exp
│   │   │   ├── lname.xo
│   │   │   ├── mindepth-arg.exp
│   │   │   ├── mindepth-arg.xo
│   │   │   ├── mindepth-badarg.exp
│   │   │   ├── name-opt.exp
│   │   │   ├── name-opt.xo
│   │   │   ├── name-period.exp
│   │   │   ├── name-period.xo
│   │   │   ├── name-slash.exp
│   │   │   ├── name-slash.xo
│   │   │   ├── path.exp
│   │   │   ├── path.xo
│   │   │   ├── perm000.exp
│   │   │   ├── perm000.xo
│   │   │   ├── perm.exp
│   │   │   ├── perm-slash.exp
│   │   │   ├── perm-slash.xo
│   │   │   ├── perm.xo
│   │   │   ├── posix-dflt.exp
│   │   │   ├── posix-dflt.xo
│   │   │   ├── posix-h.exp
│   │   │   ├── posix-h.xo
│   │   │   ├── posix-l.exp
│   │   │   ├── posix-l.xo
│   │   │   ├── posix-perminvalid.exp
│   │   │   ├── print0.exp
│   │   │   ├── print0.xo
│   │   │   ├── printf.exp
│   │   │   ├── printfHdfl.exp
│   │   │   ├── printfHdfl.xo
│   │   │   ├── printf-h.exp
│   │   │   ├── printf-h.xo
│   │   │   ├── printf-slash.exp
│   │   │   ├── printf-slash.xo
│   │   │   ├── printf-symlink.exp
│   │   │   ├── printf-symlink.xo
│   │   │   ├── printf.xo
│   │   │   ├── print_stdout.exp
│   │   │   ├── print_stdout.xo
│   │   │   ├── prune-default-print.exp
│   │   │   ├── prune-default-print.xo
│   │   │   ├── quit.exp
│   │   │   ├── quit.xo
│   │   │   ├── regex1.exp
│   │   │   ├── regex1.xo
│   │   │   ├── regex2.exp
│   │   │   ├── regex2.xo
│   │   │   ├── samefile-copy.exp
│   │   │   ├── samefile-copy.xo
│   │   │   ├── samefile-link.exp
│   │   │   ├── samefile-link.xo
│   │   │   ├── samefile-missing.exp
│   │   │   ├── samefile-p-brokenlink.exp
│   │   │   ├── samefile-p-brokenlink.xo
│   │   │   ├── samefile-same.exp
│   │   │   ├── samefile-same.xo
│   │   │   ├── samefile-symlink.exp
│   │   │   ├── samefile-symlink.xo
│   │   │   ├── sv-bug-12230.exp
│   │   │   ├── sv-bug-17477.exp
│   │   │   ├── sv-bug-17490.exp
│   │   │   ├── sv-bug-17782.exp
│   │   │   ├── sv-bug-17782.xo
│   │   │   ├── sv-bug-18222.exp
│   │   │   ├── sv-bug-18222.xo
│   │   │   ├── sv-bug-24169.exp
│   │   │   ├── true.exp
│   │   │   ├── true.xo
│   │   │   ├── used-invarg.exp
│   │   │   ├── used-missing.exp
│   │   │   ├── user-invalid.exp
│   │   │   ├── wholename.exp
│   │   │   ├── wholename.xo
│   │   │   ├── xtype.exp
│   │   │   ├── xtype-symlink.exp
│   │   │   ├── xtype-symlink.xo
│   │   │   └── xtype.xo
│   │   ├── find.posix
│   │   │   ├── and.exp
│   │   │   ├── and.xo
│   │   │   ├── bracket-depth.exp
│   │   │   ├── depth1.exp
│   │   │   ├── depth1.xo
│   │   │   ├── empty-parens.exp
│   │   │   ├── exec-one.exp
│   │   │   ├── exec-one.xo
│   │   │   ├── files-not-expressions1.exp
│   │   │   ├── files-not-expressions1.xo
│   │   │   ├── files-not-expressions2.exp
│   │   │   ├── files-not-expressions2.xo
│   │   │   ├── files-not-expressions3.exp
│   │   │   ├── files-not-expressions3.xo
│   │   │   ├── group-empty.exp
│   │   │   ├── grouping.exp
│   │   │   ├── grouping.xo
│   │   │   ├── group-missing.exp
│   │   │   ├── links.exp
│   │   │   ├── links.xo
│   │   │   ├── mtime0.exp
│   │   │   ├── mtime0.xo
│   │   │   ├── name.exp
│   │   │   ├── name-missing.exp
│   │   │   ├── nameslash.exp
│   │   │   ├── nameslash.xo
│   │   │   ├── name.xo
│   │   │   ├── parent.exp
│   │   │   ├── parent.xo
│   │   │   ├── perm-vanilla.exp
│   │   │   ├── perm-vanilla.xo
│   │   │   ├── perm-X.exp
│   │   │   ├── perm-X.xo
│   │   │   ├── posixnot.exp
│   │   │   ├── posixnot.xo
│   │   │   ├── prune.exp
│   │   │   ├── prune-result.exp
│   │   │   ├── prune-result.xo
│   │   │   ├── prune-stat.exp
│   │   │   ├── prune-stat.xo
│   │   │   ├── prune.xo
│   │   │   ├── size-invalid.exp
│   │   │   ├── size-missing.exp
│   │   │   ├── sizes.exp
│   │   │   ├── sizes.xo
│   │   │   ├── sizetype.exp
│   │   │   ├── sizetype.xo
│   │   │   ├── sv-bug-11175.exp
│   │   │   ├── sv-bug-11175.xo
│   │   │   ├── sv-bug-12181.exp
│   │   │   ├── sv-bug-12181.xo
│   │   │   ├── sv-bug-15235.exp
│   │   │   ├── sv-bug-15235.xo
│   │   │   ├── sv-bug-19605.exp
│   │   │   ├── sv-bug-19613.exp
│   │   │   ├── sv-bug-19613.xo
│   │   │   ├── sv-bug-19617.exp
│   │   │   ├── typearg.exp
│   │   │   ├── typesize.exp
│   │   │   ├── typesize.xo
│   │   │   ├── user-empty.exp
│   │   │   └── user-missing.exp
│   │   ├── Makefile.am
│   │   └── Makefile.in
│   ├── tree.c
│   └── util.c
├── gnulib
│   ├── lib
│   │   ├── alloca.c
│   │   ├── alloca.in.h
│   │   ├── areadlink.h
│   │   ├── areadlink-with-size.c
│   │   ├── argmatch.c
│   │   ├── argmatch.h
│   │   ├── at-func.c
│   │   ├── basename.c
│   │   ├── canonicalize.c
│   │   ├── canonicalize.h
│   │   ├── canonicalize-lgpl.c
│   │   ├── chdir-long.c
│   │   ├── chdir-long.h
│   │   ├── chown.c
│   │   ├── closein.c
│   │   ├── closein.h
│   │   ├── closeout.c
│   │   ├── closeout.h
│   │   ├── close-stream.c
│   │   ├── close-stream.h
│   │   ├── config.charset
│   │   ├── creat-safer.c
│   │   ├── c-strstr.c
│   │   ├── c-strstr.h
│   │   ├── cycle-check.c
│   │   ├── cycle-check.h
│   │   ├── dev-ino.h
│   │   ├── dirent.in.h
│   │   ├── dirfd.c
│   │   ├── dirfd.h
│   │   ├── dirname.c
│   │   ├── dirname.h
│   │   ├── dup2.c
│   │   ├── dup-safer.c
│   │   ├── error.c
│   │   ├── error.h
│   │   ├── exitfail.c
│   │   ├── exitfail.h
│   │   ├── fchdir.c
│   │   ├── fchmodat.c
│   │   ├── fchownat.c
│   │   ├── fchown-stub.c
│   │   ├── fcntl--.h
│   │   ├── fcntl.in.h
│   │   ├── fcntl-safer.h
│   │   ├── fd-safer.c
│   │   ├── fflush.c
│   │   ├── fileblocks.c
│   │   ├── filemode.c
│   │   ├── filemode.h
│   │   ├── filenamecat.c
│   │   ├── filenamecat.h
│   │   ├── file-set.c
│   │   ├── file-set.h
│   │   ├── fnmatch.c
│   │   ├── fnmatch.in.h
│   │   ├── fnmatch_loop.c
│   │   ├── fopen-safer.c
│   │   ├── fpending.c
│   │   ├── fpending.h
│   │   ├── fpurge.c
│   │   ├── fpurge.h
│   │   ├── freadahead.c
│   │   ├── freadahead.h
│   │   ├── freading.c
│   │   ├── freading.h
│   │   ├── fseeko.c
│   │   ├── fstatat.c
│   │   ├── ftello.c
│   │   ├── fts.c
│   │   ├── fts-cycle.c
│   │   ├── fts_.h
│   │   ├── getcwd.c
│   │   ├── getdate.c
│   │   ├── getdate.h
│   │   ├── getdate.y
│   │   ├── getdelim.c
│   │   ├── getline.c
│   │   ├── getopt1.c
│   │   ├── getopt.c
│   │   ├── getopt.in.h
│   │   ├── getopt_int.h
│   │   ├── gettext.h
│   │   ├── gettime.c
│   │   ├── gettimeofday.c
│   │   ├── hash.c
│   │   ├── hash.h
│   │   ├── hash-pjw.c
│   │   ├── hash-pjw.h
│   │   ├── hash-triple.c
│   │   ├── hash-triple.h
│   │   ├── human.c
│   │   ├── human.h
│   │   ├── idcache.c
│   │   ├── idcache.h
│   │   ├── intprops.h
│   │   ├── inttypes.in.h
│   │   ├── i-ring.c
│   │   ├── i-ring.h
│   │   ├── lchown.c
│   │   ├── localcharset.c
│   │   ├── localcharset.h
│   │   ├── lseek.c
│   │   ├── lstat.c
│   │   ├── lstat.h
│   │   ├── Makefile.am
│   │   ├── Makefile.in
│   │   ├── malloca.c
│   │   ├── malloca.h
│   │   ├── malloca.valgrind
│   │   ├── malloc.c
│   │   ├── mbchar.c
│   │   ├── mbchar.h
│   │   ├── mbscasestr.c
│   │   ├── mbslen.c
│   │   ├── mbsstr.c
│   │   ├── mbuiter.h
│   │   ├── memchr.c
│   │   ├── memcmp.c
│   │   ├── mempcpy.c
│   │   ├── memrchr.c
│   │   ├── memset.c
│   │   ├── mkdirat.c
│   │   ├── mktime.c
│   │   ├── modechange.c
│   │   ├── modechange.h
│   │   ├── mountlist.c
│   │   ├── mountlist.h
│   │   ├── openat.c
│   │   ├── openat-die.c
│   │   ├── openat.h
│   │   ├── openat-priv.h
│   │   ├── openat-proc.c
│   │   ├── open-safer.c
│   │   ├── pathmax.h
│   │   ├── pipe-safer.c
│   │   ├── progname.c
│   │   ├── progname.h
│   │   ├── quotearg.c
│   │   ├── quotearg.h
│   │   ├── quote.c
│   │   ├── quote.h
│   │   ├── readlink.c
│   │   ├── realloc.c
│   │   ├── ref-add.sin
│   │   ├── ref-del.sin
│   │   ├── regcomp.c
│   │   ├── regex.c
│   │   ├── regexec.c
│   │   ├── regex.h
│   │   ├── regex_internal.c
│   │   ├── regex_internal.h
│   │   ├── rpmatch.c
│   │   ├── same.c
│   │   ├── same.h
│   │   ├── same-inode.h
│   │   ├── save-cwd.c
│   │   ├── save-cwd.h
│   │   ├── savedir.c
│   │   ├── savedir.h
│   │   ├── setenv.c
│   │   ├── setenv.h
│   │   ├── stat-macros.h
│   │   ├── stat-time.h
│   │   ├── stdbool.in.h
│   │   ├── stdint.in.h
│   │   ├── stdio--.h
│   │   ├── stdio.in.h
│   │   ├── stdio-safer.h
│   │   ├── stdlib.in.h
│   │   ├── stpcpy.c
│   │   ├── strcasestr.c
│   │   ├── strdup.c
│   │   ├── streq.h
│   │   ├── strerror.c
│   │   ├── strftime.c
│   │   ├── strftime.h
│   │   ├── string.in.h
│   │   ├── stripslash.c
│   │   ├── strndup.c
│   │   ├── strnlen1.c
│   │   ├── strnlen1.h
│   │   ├── strnlen.c
│   │   ├── strtoimax.c
│   │   ├── strtol.c
│   │   ├── strtoll.c
│   │   ├── strtoul.c
│   │   ├── strtoull.c
│   │   ├── strtoumax.c
│   │   ├── sys_stat.in.h
│   │   ├── sys_time.in.h
│   │   ├── time.in.h
│   │   ├── time_r.c
│   │   ├── timespec.h
│   │   ├── unistd--.h
│   │   ├── unistd.in.h
│   │   ├── unistd-safer.h
│   │   ├── unitypes.h
│   │   ├── uniwidth
│   │   │   ├── cjk.h
│   │   │   └── width.c
│   │   ├── uniwidth.h
│   │   ├── unsetenv.c
│   │   ├── verify.h
│   │   ├── version-etc.c
│   │   ├── version-etc-fsf.c
│   │   ├── version-etc.h
│   │   ├── wchar.in.h
│   │   ├── wctype.in.h
│   │   ├── wcwidth.c
│   │   ├── xalloc-die.c
│   │   ├── xalloc.h
│   │   ├── xgetcwd.c
│   │   ├── xgetcwd.h
│   │   ├── xmalloc.c
│   │   ├── xstrndup.c
│   │   ├── xstrndup.h
│   │   ├── xstrtod.c
│   │   ├── xstrtod.h
│   │   ├── xstrtol.c
│   │   ├── xstrtol-error.c
│   │   ├── xstrtol.h
│   │   ├── xstrtoul.c
│   │   ├── xstrtoumax.c
│   │   ├── yesno.c
│   │   └── yesno.h
│   ├── m4
│   │   ├── alloca.m4
│   │   ├── argmatch.m4
│   │   ├── assert.m4
│   │   ├── bison.m4
│   │   ├── canonicalize-lgpl.m4
│   │   ├── canonicalize.m4
│   │   ├── chdir-long.m4
│   │   ├── chown.m4
│   │   ├── clock_time.m4
│   │   ├── closein.m4
│   │   ├── closeout.m4
│   │   ├── close-stream.m4
│   │   ├── codeset.m4
│   │   ├── cycle-check.m4
│   │   ├── d-ino.m4
│   │   ├── dirfd.m4
│   │   ├── dirname.m4
│   │   ├── dos.m4
│   │   ├── double-slash-root.m4
│   │   ├── d-type.m4
│   │   ├── dup2.m4
│   │   ├── eealloc.m4
│   │   ├── error.m4
│   │   ├── exitfail.m4
│   │   ├── extensions.m4
│   │   ├── fchdir.m4
│   │   ├── fcntl_h.m4
│   │   ├── fcntl-safer.m4
│   │   ├── fflush.m4
│   │   ├── fileblocks.m4
│   │   ├── filemode.m4
│   │   ├── filenamecat.m4
│   │   ├── flexmember.m4
│   │   ├── fnmatch.m4
│   │   ├── fpending.m4
│   │   ├── fpurge.m4
│   │   ├── freading.m4
│   │   ├── fseeko.m4
│   │   ├── fstypename.m4
│   │   ├── ftello.m4
│   │   ├── fts.m4
│   │   ├── getcwd-abort-bug.m4
│   │   ├── getcwd.m4
│   │   ├── getcwd-path-max.m4
│   │   ├── getdate.m4
│   │   ├── getdelim.m4
│   │   ├── getline.m4
│   │   ├── getopt.m4
│   │   ├── gettext.m4
│   │   ├── gettime.m4
│   │   ├── gettimeofday.m4
│   │   ├── glibc21.m4
│   │   ├── gnulib-common.m4
│   │   ├── gnulib-comp.m4
│   │   ├── hash.m4
│   │   ├── human.m4
│   │   ├── iconv.m4
│   │   ├── idcache.m4
│   │   ├── include_next.m4
│   │   ├── inline.m4
│   │   ├── intlmacosx.m4
│   │   ├── inttypes.m4
│   │   ├── inttypes-pri.m4
│   │   ├── i-ring.m4
│   │   ├── lchown.m4
│   │   ├── lib-ld.m4
│   │   ├── lib-link.m4
│   │   ├── lib-prefix.m4
│   │   ├── localcharset.m4
│   │   ├── locale-fr.m4
│   │   ├── locale-tr.m4
│   │   ├── locale-zh.m4
│   │   ├── longlong.m4
│   │   ├── lseek.m4
│   │   ├── ls-mntd-fs.m4
│   │   ├── lstat.m4
│   │   ├── malloca.m4
│   │   ├── malloc.m4
│   │   ├── mbchar.m4
│   │   ├── mbiter.m4
│   │   ├── mbrtowc.m4
│   │   ├── mbscasestr.m4
│   │   ├── mbslen.m4
│   │   ├── mbsstr.m4
│   │   ├── mbstate_t.m4
│   │   ├── memchr.m4
│   │   ├── memcmp.m4
│   │   ├── mempcpy.m4
│   │   ├── memrchr.m4
│   │   ├── memset.m4
│   │   ├── mktime.m4
│   │   ├── modechange.m4
│   │   ├── mountlist.m4
│   │   ├── nls.m4
│   │   ├── onceonly_2_57.m4
│   │   ├── openat.m4
│   │   ├── pathmax.m4
│   │   ├── po.m4
│   │   ├── progtest.m4
│   │   ├── quotearg.m4
│   │   ├── quote.m4
│   │   ├── readlink.m4
│   │   ├── realloc.m4
│   │   ├── regex.m4
│   │   ├── rpmatch.m4
│   │   ├── same.m4
│   │   ├── save-cwd.m4
│   │   ├── savedir.m4
│   │   ├── setenv.m4
│   │   ├── ssize_t.m4
│   │   ├── stat-time.m4
│   │   ├── stdarg.m4
│   │   ├── stdbool.m4
│   │   ├── stdint.m4
│   │   ├── stdio_h.m4
│   │   ├── stdio-safer.m4
│   │   ├── stdlib_h.m4
│   │   ├── st_dm_mode.m4
│   │   ├── stpcpy.m4
│   │   ├── strcasestr.m4
│   │   ├── strdup.m4
│   │   ├── strerror.m4
│   │   ├── strftime.m4
│   │   ├── string_h.m4
│   │   ├── strndup.m4
│   │   ├── strnlen.m4
│   │   ├── strtoimax.m4
│   │   ├── strtoll.m4
│   │   ├── strtol.m4
│   │   ├── strtoull.m4
│   │   ├── strtoul.m4
│   │   ├── strtoumax.m4
│   │   ├── sys_stat_h.m4
│   │   ├── sys_time_h.m4
│   │   ├── time_h.m4
│   │   ├── time_r.m4
│   │   ├── timespec.m4
│   │   ├── tm_gmtoff.m4
│   │   ├── unistd_h.m4
│   │   ├── unistd-safer.m4
│   │   ├── wchar.m4
│   │   ├── wchar_t.m4
│   │   ├── wctype.m4
│   │   ├── wcwidth.m4
│   │   ├── wint_t.m4
│   │   ├── xalloc.m4
│   │   ├── xgetcwd.m4
│   │   ├── xstrndup.m4
│   │   ├── xstrtod.m4
│   │   ├── xstrtol.m4
│   │   └── yesno.m4
│   ├── Makefile.am
│   └── Makefile.in
├── import-gnulib.config
├── import-gnulib.sh
├── INSTALL
├── lib
│   ├── buildcmd.c
│   ├── buildcmd.h
│   ├── dircallback.c
│   ├── dircallback.h
│   ├── extendbuf.c
│   ├── extendbuf.h
│   ├── locate-version.c
│   ├── locate-version.h
│   ├── forcefindlib.c
│   ├── gnulib-version.c
│   ├── gnulib-version.h
│   ├── listfile.c
│   ├── listfile.h
│   ├── Makefile.am
│   ├── Makefile.in
│   ├── modetype.h
│   ├── nextelem.c
│   ├── nextelem.h
│   ├── printquoted.c
│   ├── printquoted.h
│   ├── qmark.c
│   ├── regexprops.c
│   ├── regextype.c
│   ├── regextype.h
│   ├── savedirinfo.c
│   ├── savedirinfo.h
│   ├── wait.h
│   └── waitpid.c
├── locate
│   ├── bigram.c
│   ├── code.c
│   ├── frcode.c
│   ├── locate.1
│   ├── locate.c
│   ├── locatedb.5
│   ├── locatedb.h
│   ├── Makefile.am
│   ├── Makefile.in
│   ├── testsuite
│   │   ├── config
│   │   │   └── unix.exp
│   │   ├── locate.gnu
│   │   │   ├── bigendian.exp
│   │   │   ├── bigendian.xo
│   │   │   ├── bigprefix1.exp
│   │   │   ├── exceedshort.exp
│   │   │   ├── exists1.exp
│   │   │   ├── exists1.xo
│   │   │   ├── exists2.exp
│   │   │   ├── exists2.xo
│   │   │   ├── exists3.exp
│   │   │   ├── exists3.xo
│   │   │   ├── ignore_case1.exp
│   │   │   ├── ignore_case1.xo
│   │   │   ├── ignore_case2.exp
│   │   │   ├── ignore_case2.xo
│   │   │   ├── ignore_case3.exp
│   │   │   ├── ignore_case3.xo
│   │   │   ├── littleendian.exp
│   │   │   ├── littleendian.xo
│   │   │   ├── locateddb.old.powerpc.xi
│   │   │   ├── locateddb.old.x86.xi
│   │   │   ├── notexists1.exp
│   │   │   ├── notexists1.xo
│   │   │   ├── notexists2.exp
│   │   │   ├── notexists2.xo
│   │   │   ├── notexists3.exp
│   │   │   ├── notexists3.xo
│   │   │   ├── old_prefix.exp
│   │   │   ├── old_prefix.xo
│   │   │   ├── regex1.exp
│   │   │   ├── space1st.exp
│   │   │   └── sv-bug-14535.exp
│   │   ├── Makefile.am
│   │   └── Makefile.in
│   ├── updatedb.1
│   ├── updatedb.sh
│   └── word_io.c
├── m4
│   ├── findlib.m4
│   ├── Makefile.am
│   ├── Makefile.in
│   ├── mkinstalldirs.m4
│   ├── noreturn.m4
│   ├── nullsort.m4
│   ├── order-bad.bin
│   ├── order-good.bin
│   └── withfts.m4
├── Makefile.am
├── Makefile.in
├── NEWS
├── po
│   ├── be.gmo
│   ├── be.po
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
│   ├── en@boldquot.header
│   ├── en@quot.header
│   ├── eo.gmo
│   ├── eo.po
│   ├── es.gmo
│   ├── es.po
│   ├── et.gmo
│   ├── et.po
│   ├── fi.gmo
│   ├── locate.pot
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
│   ├── ko.gmo
│   ├── ko.po
│   ├── lg.gmo
│   ├── lg.po
│   ├── lt.gmo
│   ├── lt.po
│   ├── Makefile.in.in
│   ├── Makevars
│   ├── ms.gmo
│   ├── ms.po
│   ├── nl.gmo
│   ├── nl.po
│   ├── pl.gmo
│   ├── pl.po
│   ├── POTFILES.in
│   ├── pt_BR.gmo
│   ├── pt_BR.po
│   ├── pt.gmo
│   ├── pt.po
│   ├── quot.sed
│   ├── remove-potcdate.sin
│   ├── ro.gmo
│   ├── ro.po
│   ├── ru.gmo
│   ├── Rules-quot
│   ├── ru.po
│   ├── rw.gmo
│   ├── rw.po
│   ├── sk.gmo
│   ├── sk.po
│   ├── sl.gmo
│   ├── sl.po
│   ├── sr.gmo
│   ├── sr.po
│   ├── stamp-po
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
├── README
├── README-hacking
├── stamp-h.in
├── tests
│   ├── binary-io.h
│   ├── dummy.c
│   ├── Makefile.am
│   ├── Makefile.in
│   ├── test-alloca-opt.c
│   ├── test-argmatch.c
│   ├── test-binary-io.c
│   ├── test-binary-io.sh
│   ├── test-canonicalize.c
│   ├── test-canonicalize-lgpl.c
│   ├── test-canonicalize-lgpl.sh
│   ├── test-canonicalize.sh
│   ├── test-closein.c
│   ├── test-closein.sh
│   ├── test-c-strstr.c
│   ├── test-dirname.c
│   ├── test-fcntl.c
│   ├── test-fflush.c
│   ├── test-filenamecat.c
│   ├── test-fpending.c
│   ├── test-fpending.sh
│   ├── test-fpurge.c
│   ├── test-freadahead.c
│   ├── test-freadahead.sh
│   ├── test-freading.c
│   ├── test-fseeko.c
│   ├── test-fseeko.sh
│   ├── test-ftello.c
│   ├── test-ftello.sh
│   ├── test-getdelim.c
│   ├── test-getline.c
│   ├── test-gettimeofday.c
│   ├── test-inttypes.c
│   ├── test-i-ring.c
│   ├── test-lseek.c
│   ├── test-lseek.sh
│   ├── test-malloca.c
│   ├── test-mbscasestr1.c
│   ├── test-mbscasestr2.c
│   ├── test-mbscasestr2.sh
│   ├── test-mbscasestr3.c
│   ├── test-mbscasestr3.sh
│   ├── test-mbscasestr4.c
│   ├── test-mbscasestr4.sh
│   ├── test-mbsstr1.c
│   ├── test-mbsstr2.c
│   ├── test-mbsstr2.sh
│   ├── test-mbsstr3.c
│   ├── test-mbsstr3.sh
│   ├── test-stat-time.c
│   ├── test-stdbool.c
│   ├── test-stdint.c
│   ├── test-stdio.c
│   ├── test-stdlib.c
│   ├── test-strcasestr.c
│   ├── test-strerror.c
│   ├── test-string.c
│   ├── test-sys_stat.c
│   ├── test-sys_time.c
│   ├── test-time.c
│   ├── test-unistd.c
│   ├── test-wchar.c
│   ├── test-wctype.c
│   ├── test-wcwidth.c
│   ├── test-xstrtol.c
│   ├── test-xstrtol.sh
│   ├── test-xstrtoul.c
│   ├── test-xstrtoumax.c
│   ├── test-xstrtoumax.sh
│   ├── test-yesno.c
│   ├── test-yesno.sh
│   └── uniwidth
│       └── test-uc_width.c
├── THANKS
├── TODO
├── tool-versions.txt
└── xargs
    ├── Makefile.am
    ├── Makefile.in
    ├── testsuite
    │   ├── config
    │   │   └── unix.exp
    │   ├── inputs
    │   │   ├── 16383-ys.xi
    │   │   ├── 32767-ys.xi
    │   │   ├── blank.xi
    │   │   ├── empty.xi
    │   │   ├── eof_-0.xi
    │   │   ├── eof1.xi
    │   │   ├── EOFb.xi
    │   │   ├── EOFe.xi
    │   │   ├── eofstr.xi
    │   │   ├── eof_.xi
    │   │   ├── EOF.xi
    │   │   ├── ett.xi
    │   │   ├── files0.xi
    │   │   ├── files.xi
    │   │   ├── foobar.xi
    │   │   ├── formfeeds.xi
    │   │   ├── ftt.xi
    │   │   ├── helloworld.xi
    │   │   ├── items-0.xi
    │   │   ├── items.xi
    │   │   ├── ldata-0.xi
    │   │   ├── ldatab-0.xi
    │   │   ├── ldatab.xi
    │   │   ├── ldata.xi
    │   │   ├── lines.xi
    │   │   ├── noeof-0.xi
    │   │   ├── noeof.xi
    │   │   ├── Pdata.xi
    │   │   ├── quotes.xi
    │   │   ├── space.xi
    │   │   ├── stairs-0.xi
    │   │   ├── stairs2-0.xi
    │   │   ├── stairs2.xi
    │   │   ├── stairs.xi
    │   │   ├── stt.xi
    │   │   ├── sv-bug-20273.xi
    │   │   ├── unmatched2.xi
    │   │   ├── unmatched.xi
    │   │   └── verticaltabs.xi
    │   ├── Makefile.am
    │   ├── Makefile.in
    │   ├── xargs.gnu
    │   │   ├── 0n3.exp
    │   │   ├── 0n3.xo
    │   │   ├── delim-o.exp
    │   │   ├── delim-o.xo
    │   │   ├── E_-0.exp
    │   │   ├── E_-0.xo
    │   │   ├── empty_def-r.exp
    │   │   ├── empty-r.exp
    │   │   ├── idef-0.exp
    │   │   ├── idef-0.xo
    │   │   ├── idef-s26-0.exp
    │   │   ├── idef-s26-0.xo
    │   │   ├── l1-0.exp
    │   │   ├── l1-0.xo
    │   │   ├── l1_2-0.exp
    │   │   ├── l1_2-0.xo
    │   │   ├── L2-0.exp
    │   │   ├── L2-0.xo
    │   │   ├── L2_2-0.exp
    │   │   ├── L2_2-0.xo
    │   │   ├── L3-0.exp
    │   │   ├── L3-0.xo
    │   │   ├── n1-0.exp
    │   │   ├── n1-0.xo
    │   │   ├── n2-0.exp
    │   │   ├── n2-0.xo
    │   │   ├── n2-s26-0.exp
    │   │   ├── n2-s26-0.xo
    │   │   ├── n2-s26-x-0.exp
    │   │   ├── n2-s26-x-0.xo
    │   │   ├── n3-0.exp
    │   │   ├── n3-0.xo
    │   │   ├── n3-s36-0.exp
    │   │   ├── n3-s36-0.xo
    │   │   ├── noeof-0.exp
    │   │   ├── noeof-0.xo
    │   │   ├── nothing.exp
    │   │   ├── nothing.xo
    │   │   ├── P3-n1-IARG.exp
    │   │   ├── P3-n1-IARG.xo
    │   │   ├── r.exp
    │   │   ├── r.xo
    │   │   ├── s118-0.exp
    │   │   ├── s118-0.xo
    │   │   ├── s19-0.exp
    │   │   ├── s19-0.xo
    │   │   ├── s19_2-0.exp
    │   │   ├── s20-0.exp
    │   │   ├── s20-0.xo
    │   │   ├── s30-0.exp
    │   │   ├── s30-0.xo
    │   │   ├── space-0.exp
    │   │   ├── space-0.xo
    │   │   ├── space-r.exp
    │   │   ├── space-t-0.exp
    │   │   ├── space-t-0.xe
    │   │   └── space-t-0.xo
    │   ├── xargs.posix
    │   │   ├── arg_max_32bit_linux_bug.exp
    │   │   ├── arg_max_64bit_linux_bug.exp
    │   │   ├── childfail.exp
    │   │   ├── EEOFb.exp
    │   │   ├── EEOFb.xo
    │   │   ├── EEOFe.exp
    │   │   ├── EEOFe.xo
    │   │   ├── EEOF.exp
    │   │   ├── EEOF.xo
    │   │   ├── E_.exp
    │   │   ├── E_-IARG.exp
    │   │   ├── E_-IARG.xo
    │   │   ├── empty_def.exp
    │   │   ├── empty_def.xo
    │   │   ├── empty.exp
    │   │   ├── empty.xo
    │   │   ├── E_.xo
    │   │   ├── hithere.exp
    │   │   ├── hithere.xo
    │   │   ├── IARG-E_.exp
    │   │   ├── IARG-E_.xo
    │   │   ├── IARG.exp
    │   │   ├── IARG-s15.exp
    │   │   ├── IARG-s15.xo
    │   │   ├── IARG.xo
    │   │   ├── L2_2.exp
    │   │   ├── L2_2.xo
    │   │   ├── L2-n2.exp
    │   │   ├── L2-n2.xo
    │   │   ├── L3.exp
    │   │   ├── L3.xo
    │   │   ├── n1.exp
    │   │   ├── n1.xo
    │   │   ├── n2.exp
    │   │   ├── n2-s26.exp
    │   │   ├── n2-s26-x.exp
    │   │   ├── n2-s26.xo
    │   │   ├── n2-s26-x.xo
    │   │   ├── n2.xo
    │   │   ├── n3.exp
    │   │   ├── n3-s36.exp
    │   │   ├── n3-s36.xo
    │   │   ├── n3.xo
    │   │   ├── noeof.exp
    │   │   ├── noeof.xo
    │   │   ├── quotes.exp
    │   │   ├── quotes.xo
    │   │   ├── rc-123.exp
    │   │   ├── rc-123.xo
    │   │   ├── rc-124.exp
    │   │   ├── rc-125.exp
    │   │   ├── rc-126.exp
    │   │   ├── rc-127.exp
    │   │   ├── s118.exp
    │   │   ├── s118.xo
    │   │   ├── s19_2.exp
    │   │   ├── s19.exp
    │   │   ├── s19.xo
    │   │   ├── s20.exp
    │   │   ├── s20.xo
    │   │   ├── s30.exp
    │   │   ├── s30.xo
    │   │   ├── s470.exp
    │   │   ├── s470.xo
    │   │   ├── s47.exp
    │   │   ├── s47.xo
    │   │   ├── s48.exp
    │   │   ├── s48.xo
    │   │   ├── s6.exp
    │   │   ├── savannah-11865.exp
    │   │   ├── savannah-11865.xo
    │   │   ├── space.exp
    │   │   ├── space-I.exp
    │   │   ├── space.xo
    │   │   ├── sv-bug-18714b.exp
    │   │   ├── sv-bug-18714b.xo
    │   │   ├── sv-bug-18714.exp
    │   │   ├── sv-bug-18714.xo
    │   │   ├── sv-bug-20273.exp
    │   │   ├── sv-bug-20273.xo
    │   │   ├── uc_L2.exp
    │   │   ├── uc_L2.xo
    │   │   ├── unmatched2.exp
    │   │   ├── unmatched2.xo
    │   │   ├── unmatched.exp
    │   │   ├── unmatched-n2-x.exp
    │   │   └── unmatched.xo
    │   └── xargs.sysv
    │       ├── eEOF.exp
    │       ├── eEOF.xo
    │       ├── e.exp
    │       ├── empty_def-t.exp
    │       ├── empty_def-t.xe
    │       ├── empty_def-t.xo
    │       ├── empty-t.exp
    │       ├── empty-t.xe
    │       ├── empty-t.xo
    │       ├── eof1.exp
    │       ├── eof1.xo
    │       ├── e.xo
    │       ├── iARG.exp
    │       ├── iARG.xo
    │       ├── idef.exp
    │       ├── idef-s26.exp
    │       ├── idef-s26.xo
    │       ├── idef.xo
    │       ├── iquotes.exp
    │       ├── iquotes.xo
    │       ├── l1_2.exp
    │       ├── l1_2.xo
    │       ├── l1.exp
    │       ├── l1n4.exp
    │       ├── l1n4.xo
    │       ├── l1.xo
    │       ├── lc_l2.exp
    │       ├── lc_l2.xo
    │       ├── s30-t.exp
    │       ├── s30-t.xe
    │       ├── s30-t.xo
    │       ├── space-t.exp
    │       ├── space-t.xe
    │       ├── space-t.xo
    │       ├── sv-bug-18713.exp
    │       ├── sv-bug-18713.xo
    │       ├── trace.exp
    │       ├── trace.xe
    │       └── trace.xo
    ├── xargs.1
    └── xargs.c

30 directories, 1148 files

```
