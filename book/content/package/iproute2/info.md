# iproute2 info


## 套件資訊

執行

```
$ apt-cache show iproute2
```

顯示

```
Package: iproute2
Priority: required
Section: net
Installed-Size: 1147
Maintainer: Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Original-Maintainer: Debian iproute2 Maintainers <ah-iproute@debian.org>
Architecture: amd64
Version: 3.12.0-2
Replaces: iproute
Provides: arpd
Depends: libc6 (>= 2.14), libdb5.3
Recommends: libatm1 (>= 2.4.1-17~), libxtables10
Suggests: iproute2-doc
Conflicts: arpd, iproute (<< 20130000-1)
Filename: pool/main/i/iproute2/iproute2_3.12.0-2_amd64.deb
Size: 399966
MD5sum: c42f26bf580f71ed30e6c2ded3687e26
SHA1: 84f46124118117f274b99e5b3ad209cd3e46f8ef
SHA256: be0007c38cfc6b908ff3e50f44b276c0ccc3c0d83bd996666e82eb3b4c79a5b0
Description-en: networking and traffic control tools
 The iproute2 suite is a collection of utilities for networking and
 traffic control.
 .
 These tools communicate with the Linux kernel via the (rt)netlink
 interface, providing advanced features not available through the
 legacy net-tools commands 'ifconfig' and 'route'.
Description-md5: d10cc46ca4a9e5489b7d2c879fcfba17
Multi-Arch: foreign
Homepage: http://www.linux-foundation.org/en/Net:Iproute2
Bugs: https://bugs.launchpad.net/ubuntu/+filebug
Origin: Ubuntu
Supported: 5y
Task: minimal
```

執行

```
$ apt-cache showpkg iproute2
```

顯示

```
Package: iproute2
Versions:
3.12.0-2 (/var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_binary-amd64_Packages) (/var/lib/dpkg/status)
 Description Language:
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_binary-amd64_Packages
                  MD5: d10cc46ca4a9e5489b7d2c879fcfba17
 Description Language: en
                 File: /var/lib/apt/lists/tw.archive.ubuntu.com_ubuntu_dists_trusty_main_i18n_Translation-en
                  MD5: d10cc46ca4a9e5489b7d2c879fcfba17


Reverse Depends:
  strongswan-ike,iproute2
  openvpn,iproute2
  ifupdown,iproute2
  iproute2:i386,iproute2
  snort,iproute2
  iodine,iproute2
  inxi,iproute2
  ifupdown-extra,iproute2
  gogoc,iproute2
  ganeti,iproute2
  firehol,iproute2
  ctdb,iproute2
  core-network-daemon,iproute2
  vlan,iproute2
  ubuntu-minimal,iproute2
  strongswan-ike,iproute2
  openvpn,iproute2
  network-manager,iproute2
  isc-dhcp-client,iproute2
  iproute,iproute2
  ifupdown,iproute2
  ifenslave,iproute2
Dependencies:
3.12.0-2 - libc6 (2 2.14) libdb5.3 (0 (null)) iproute2-doc (0 (null)) libatm1 (2 2.4.1-17~) libxtables10 (0 (null)) arpd (0 (null)) arpd:i386 (0 (null)) iproute (3 20130000-1) iproute:i386 (3 20130000-1) iproute (0 (null)) iproute:i386 (0 (null)) iproute2:i386 (0 (null))
Provides:
3.12.0-2 - iproute2:i386 arpd:i386 arpd
Reverse Provides:
iproute2:i386 3.12.0-2

```

執行

```
$ apt-cache showsrc iproute2
```

顯示

```
Package: iproute2
Binary: iproute2, iproute2-doc, iproute, iproute-doc
Version: 3.12.0-2
Priority: required
Section: misc
Maintainer: Debian iproute2 Maintainers <ah-iproute@debian.org>
Build-Depends: texlive-latex-base, texlive-latex-recommended, texlive-fonts-recommended, iptables-dev, libatm1-dev, libdb-dev, linuxdoc-tools, linux-libc-dev, debhelper (>= 8), lynx | lynx-cur, pkg-config, bison, flex
Architecture: any all
Standards-Version: 3.9.4
Format: 3.0 (quilt)
Directory: pool/main/i/iproute2
Files:
 592dde3c472ba9948dc9b3ce83a6a6a6 1626 iproute2_3.12.0-2.dsc
 f87386aaaecafab95607fd10e8152c68 425192 iproute2_3.12.0.orig.tar.xz
 d6386c62ce5645a565a0eb036bf7232f 26352 iproute2_3.12.0-2.debian.tar.xz
Uploaders: Andreas Henriksson <andreas@fatal.se>, Alexander Wirt <formorer@debian.org>
Homepage: http://www.linux-foundation.org/en/Net:Iproute2
Vcs-Browser: http://git.debian.org/?p=collab-maint/pkg-iproute.git
Vcs-Git: git://git.debian.org/git/collab-maint/pkg-iproute.git
Package-List:
 iproute deb oldlibs optional
 iproute-doc deb oldlibs optional
 iproute2 deb net important
 iproute2-doc deb doc optional
Checksums-Sha1:
 2b98118fc0dd30aa6b46abab1c093a76bb3a50a4 1626 iproute2_3.12.0-2.dsc
 9397376e5d4dcbb1182745cd58625895fcdb868d 425192 iproute2_3.12.0.orig.tar.xz
 734ade3bf3a1b571cebd8dd2e306552b3cc09abc 26352 iproute2_3.12.0-2.debian.tar.xz
Checksums-Sha256:
 f111b140dd8df6e78f372ed20cdabdab7f465ccfade5d10aa66f5f5eb4d7bf4f 1626 iproute2_3.12.0-2.dsc
 44f600475d27a421688cda2294efec38513473a740c24ead78eb20005f08f111 425192 iproute2_3.12.0.orig.tar.xz
 8387ee9f16db4f8051c20f05e5e6840888f0b52b6f833e520392feb62f1a5603 26352 iproute2_3.12.0-2.debian.tar.xz
```

執行

```
$ dpkg -s iproute2
```

顯示

```
Package: iproute2
Status: install ok installed
Priority: required
Section: net
Installed-Size: 1147
Maintainer: Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>
Architecture: amd64
Multi-Arch: foreign
Version: 3.12.0-2
Replaces: iproute
Provides: arpd
Depends: libc6 (>= 2.14), libdb5.3
Recommends: libatm1 (>= 2.4.1-17~), libxtables10
Suggests: iproute2-doc
Conflicts: arpd, iproute (<< 20130000-1)
Conffiles:
 /etc/iproute2/group 3aea2c0e0dd75e13a5f8f48f2936915f
 /etc/iproute2/ematch_map b91e7f9b26918449bade9573f8871d61
 /etc/iproute2/rt_realms 7137bdf40e8d58c87ac7e3bba503767f
 /etc/iproute2/rt_tables a1313318d6778fe6b8c680248ef5a463
 /etc/iproute2/rt_dsfield 4264d5c7c8298300185aa04e1a736934
 /etc/iproute2/rt_protos 95ce0b4b5b79f5a8a45941fb418a904c
 /etc/iproute2/rt_scopes 6298b8df09e9bda23ea7da49021ca457
Description: networking and traffic control tools
 The iproute2 suite is a collection of utilities for networking and
 traffic control.
 .
 These tools communicate with the Linux kernel via the (rt)netlink
 interface, providing advanced features not available through the
 legacy net-tools commands 'ifconfig' and 'route'.
Original-Maintainer: Debian iproute2 Maintainers <ah-iproute@debian.org>
Homepage: http://www.linux-foundation.org/en/Net:Iproute2
```

執行

```
$ dpkg -l iproute2
```

顯示

```
Desired=Unknown/Install/Remove/Purge/Hold
| Status=Not/Inst/Conf-files/Unpacked/halF-conf/Half-inst/trig-aWait/Trig-pend
|/ Err?=(none)/Reinst-required (Status,Err: uppercase=bad)
||/ Name                            Version              Architecture         Description
+++-===============================-====================-====================-====================================================================
ii  iproute2                        3.12.0-2             amd64                networking and traffic control tools


```


## 準備工作環境

```
mkdir  ~/Downloads/iproute2 -p
cd ~/Downloads/iproute2
mkdir download source
```

## 探索「Package: [iproute2](http://packages.ubuntu.com/trusty/iproute2)」

切換到「~/Downloads/iproute2/download」

``` sh
$ cd ~/Downloads/iproute2/download
```

下載「Package: iproute2」。

``` sh
$ apt-get download iproute2
```

解開「package iproute2」

``` sh
dpkg -x iproute2_3.12.0-2_amd64.deb iproute2
dpkg -e iproute2_3.12.0-2_amd64.deb
# ar xv iproute2_3.12.0-2_amd64.deb
```

檢視套件檔案

``` sh
$ tree iproute2
```

顯示

```
iproute2
├── bin
│   ├── ip
│   └── ss
├── etc
│   └── iproute2
│       ├── ematch_map
│       ├── group
│       ├── rt_dsfield
│       ├── rt_protos
│       ├── rt_realms
│       ├── rt_scopes
│       └── rt_tables
├── sbin
│   ├── bridge
│   ├── ip -> /bin/ip
│   ├── rtacct
│   ├── rtmon
│   └── tc
└── usr
    ├── bin
    │   ├── ctstat -> lnstat
    │   ├── lnstat
    │   ├── nstat
    │   ├── routef
    │   ├── routel
    │   └── rtstat -> lnstat
    ├── lib
    │   └── tc
    │       ├── experimental.dist
    │       ├── m_ipt.so -> m_xt.so
    │       ├── m_xt.so
    │       ├── normal.dist
    │       ├── pareto.dist
    │       ├── paretonormal.dist
    │       └── q_atm.so
    ├── sbin
    │   └── arpd
    └── share
        ├── doc
        │   └── iproute2
        │       ├── changelog.Debian.gz
        │       ├── copyright
        │       └── README.Debian
        └── man
            ├── man3
            │   └── libnetlink.3.gz
            ├── man7
            │   └── tc-hfsc.7.gz
            └── man8
                ├── arpd.8.gz
                ├── bridge.8.gz
                ├── ctstat.8.gz -> lnstat.8.gz
                ├── ip.8.gz
                ├── ip-address.8.gz
                ├── ip-addrlabel.8.gz
                ├── ip-l2tp.8.gz
                ├── ip-link.8.gz
                ├── ip-maddress.8.gz
                ├── ip-monitor.8.gz
                ├── ip-mroute.8.gz
                ├── ip-neighbour.8.gz
                ├── ip-netconf.8.gz
                ├── ip-netns.8.gz
                ├── ip-ntable.8.gz
                ├── ip-route.8.gz
                ├── ip-rule.8.gz
                ├── ip-tcp_metrics.8.gz
                ├── ip-token.8.gz
                ├── ip-tunnel.8.gz
                ├── ip-xfrm.8.gz
                ├── lnstat.8.gz
                ├── nstat.8.gz -> rtacct.8.gz
                ├── routef.8.gz -> routel.8.gz
                ├── routel.8.gz
                ├── rtacct.8.gz
                ├── rtmon.8.gz
                ├── rtstat.8.gz -> lnstat.8.gz
                ├── ss.8.gz
                ├── tc.8.gz
                ├── tc-bfifo.8.gz
                ├── tc-cbq.8.gz
                ├── tc-cbq-details.8.gz
                ├── tc-choke.8.gz
                ├── tc-codel.8.gz
                ├── tc-drr.8.gz
                ├── tc-ematch.8.gz
                ├── tc-fq_codel.8.gz
                ├── tc-hfsc.8.gz
                ├── tc-htb.8.gz
                ├── tc-netem.8.gz
                ├── tc-pfifo.8.gz -> tc-bfifo.8.gz
                ├── tc-pfifo_fast.8.gz
                ├── tc-prio.8.gz
                ├── tc-red.8.gz
                ├── tc-sfb.8.gz
                ├── tc-sfq.8.gz
                ├── tc-stab.8.gz
                └── tc-tbf.8.gz

16 directories, 82 files

```

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


## 探索「Source Package: [iproute2](http://packages.ubuntu.com/trusty/iproute2)」

切換到「~/Downloads/iproute2/source」

``` sh
$ cd ~/Downloads/iproute2/source
```

下載「Source Package: iproute2」。

``` sh
$ apt-get source iproute2
```

檢視原始碼套件檔案。

```
$ tree iproute2-3.12.0
```

顯示

```
iproute2-3.12.0
├── bridge
│   ├── br_common.h
│   ├── bridge.c
│   ├── fdb.c
│   ├── link.c
│   ├── Makefile
│   ├── mdb.c
│   ├── monitor.c
│   └── vlan.c
├── configure
├── COPYING
├── debian
│   ├── changelog
│   ├── compat
│   ├── control
│   ├── copyright
│   ├── doc
│   │   └── htb
│   │       ├── htbfaq.htm
│   │       └── userg.htm
│   ├── iproute2-doc.docs
│   ├── iproute2-doc.install
│   ├── iproute2.install
│   ├── iproute2.links
│   ├── iproute2.manpages
│   ├── patches
│   │   ├── 0001-Add-moo-feature.patch
│   │   ├── 0002-txtdocs.patch
│   │   ├── f_u32
│   │   └── series
│   ├── README.Debian
│   ├── README.source
│   ├── rules
│   ├── source
│   │   └── format
│   └── watch
├── doc
│   ├── actions
│   │   ├── actions-general
│   │   ├── gact-usage
│   │   ├── ifb-README
│   │   └── mirred-usage
│   ├── api-ip6-flowlabels.tex
│   ├── arpd.sgml
│   ├── do-psnup
│   ├── ip-cref.tex
│   ├── ip-tunnels.tex
│   ├── Makefile
│   ├── nstat.sgml
│   ├── Plan
│   ├── preamble.tex
│   ├── rtstat.sgml
│   ├── SNAPSHOT.tex
│   └── ss.sgml
├── etc
│   └── iproute2
│       ├── ematch_map
│       ├── group
│       ├── rt_dsfield
│       ├── rt_protos
│       ├── rt_realms
│       ├── rt_scopes
│       └── rt_tables
├── examples
│   ├── cbqinit.eth1
│   ├── cbq.init-v0.7.3
│   ├── dhcp-client-script
│   ├── diffserv
│   │   ├── afcbq
│   │   ├── Edge1
│   │   ├── Edge2
│   │   ├── Edge31-ca-u32
│   │   ├── Edge31-cb-chains
│   │   ├── Edge32-ca-u32
│   │   ├── Edge32-cb-chains
│   │   ├── Edge32-cb-u32
│   │   ├── efcbq
│   │   ├── ef-prio
│   │   ├── README
│   │   └── regression-testing
│   ├── gaiconf
│   ├── README.cbq
│   └── SYN-DoS.rate.limit
├── genl
│   ├── ctrl.c
│   ├── genl.c
│   ├── genl_utils.h
│   ├── Makefile
│   └── static-syms.c
├── include
│   ├── dlfcn.h
│   ├── hlist.h
│   ├── ip6tables.h
│   ├── iptables_common.h
│   ├── iptables.h
│   ├── libgenl.h
│   ├── libiptc
│   │   ├── ipt_kernel_headers.h
│   │   ├── libip6tc.h
│   │   └── libiptc.h
│   ├── libnetlink.h
│   ├── linux
│   │   ├── atmapi.h
│   │   ├── atm.h
│   │   ├── atmioc.h
│   │   ├── atmsap.h
│   │   ├── can
│   │   │   └── netlink.h
│   │   ├── can.h
│   │   ├── fib_rules.h
│   │   ├── filter.h
│   │   ├── genetlink.h
│   │   ├── gen_stats.h
│   │   ├── hdlc
│   │   │   └── ioctl.h
│   │   ├── if_addr.h
│   │   ├── if_addrlabel.h
│   │   ├── if_arp.h
│   │   ├── if_bridge.h
│   │   ├── if_ether.h
│   │   ├── if.h
│   │   ├── if_link.h
│   │   ├── if_tun.h
│   │   ├── if_tunnel.h
│   │   ├── if_vlan.h
│   │   ├── inet_diag.h
│   │   ├── ip6_tunnel.h
│   │   ├── l2tp.h
│   │   ├── neighbour.h
│   │   ├── netconf.h
│   │   ├── netdevice.h
│   │   ├── netfilter
│   │   │   ├── x_tables.h
│   │   │   └── xt_tcpudp.h
│   │   ├── netfilter.h
│   │   ├── netfilter_ipv4
│   │   │   └── ip_tables.h
│   │   ├── netfilter_ipv4.h
│   │   ├── netlink_diag.h
│   │   ├── netlink.h
│   │   ├── packet_diag.h
│   │   ├── pkt_cls.h
│   │   ├── pkt_sched.h
│   │   ├── rtnetlink.h
│   │   ├── sock_diag.h
│   │   ├── socket.h
│   │   ├── tc_act
│   │   │   ├── tc_csum.h
│   │   │   ├── tc_defact.h
│   │   │   ├── tc_gact.h
│   │   │   ├── tc_ipt.h
│   │   │   ├── tc_mirred.h
│   │   │   ├── tc_nat.h
│   │   │   ├── tc_pedit.h
│   │   │   └── tc_skbedit.h
│   │   ├── tc_ematch
│   │   │   ├── tc_em_cmp.h
│   │   │   ├── tc_em_meta.h
│   │   │   ├── tc_em_nbyte.h
│   │   │   └── tc_em_text.h
│   │   ├── tcp.h
│   │   ├── tcp_metrics.h
│   │   ├── types.h
│   │   ├── unix_diag.h
│   │   ├── veth.h
│   │   └── xfrm.h
│   ├── ll_map.h
│   ├── netinet
│   │   └── tcp.h
│   ├── rtm_map.h
│   ├── rt_names.h
│   ├── SNAPSHOT.h
│   ├── utils.h
│   └── xt-internal.h
├── ip
│   ├── ifcfg
│   ├── ip6tunnel.c
│   ├── ipaddress.c
│   ├── ipaddrlabel.c
│   ├── ip.c
│   ├── ip_common.h
│   ├── ipl2tp.c
│   ├── iplink.c
│   ├── iplink_can.c
│   ├── iplink_ipoib.c
│   ├── iplink_macvlan.c
│   ├── iplink_macvtap.c
│   ├── iplink_vlan.c
│   ├── iplink_vxlan.c
│   ├── ipmaddr.c
│   ├── ipmonitor.c
│   ├── ipmroute.c
│   ├── ipneigh.c
│   ├── ipnetconf.c
│   ├── ipnetns.c
│   ├── ipntable.c
│   ├── ipprefix.c
│   ├── iproute.c
│   ├── iprule.c
│   ├── iptoken.c
│   ├── iptunnel.c
│   ├── iptuntap.c
│   ├── ipxfrm.c
│   ├── link_gre6.c
│   ├── link_gre.c
│   ├── link_ip6tnl.c
│   ├── link_iptnl.c
│   ├── link_veth.c
│   ├── link_vti.c
│   ├── Makefile
│   ├── routef
│   ├── routel
│   ├── rtm_map.c
│   ├── rtmon.c
│   ├── rtpr
│   ├── static-syms.c
│   ├── tcp_metrics.c
│   ├── tunnel.c
│   ├── tunnel.h
│   ├── xfrm.h
│   ├── xfrm_monitor.c
│   ├── xfrm_policy.c
│   └── xfrm_state.c
├── lib
│   ├── dnet_ntop.c
│   ├── dnet_pton.c
│   ├── inet_proto.c
│   ├── ipx_ntop.c
│   ├── ipx_pton.c
│   ├── libgenl.c
│   ├── libnetlink.c
│   ├── ll_addr.c
│   ├── ll_map.c
│   ├── ll_proto.c
│   ├── ll_types.c
│   ├── Makefile
│   ├── rt_names.c
│   └── utils.c
├── Makefile
├── man
│   ├── Makefile
│   ├── man3
│   │   ├── libnetlink.3
│   │   └── Makefile
│   ├── man7
│   │   ├── Makefile
│   │   └── tc-hfsc.7
│   └── man8
│       ├── arpd.8
│       ├── bridge.8
│       ├── ctstat.8
│       ├── ip.8
│       ├── ip-address.8.in
│       ├── ip-addrlabel.8
│       ├── ip-l2tp.8
│       ├── ip-link.8.in
│       ├── ip-maddress.8
│       ├── ip-monitor.8
│       ├── ip-mroute.8
│       ├── ip-neighbour.8
│       ├── ip-netconf.8
│       ├── ip-netns.8
│       ├── ip-ntable.8
│       ├── ip-route.8.in
│       ├── ip-rule.8
│       ├── ip-tcp_metrics.8
│       ├── ip-token.8
│       ├── ip-tunnel.8
│       ├── ip-xfrm.8
│       ├── lnstat.8
│       ├── Makefile
│       ├── nstat.8
│       ├── routef.8
│       ├── routel.8
│       ├── rtacct.8
│       ├── rtmon.8
│       ├── rtstat.8
│       ├── ss.8
│       ├── tc.8
│       ├── tc-bfifo.8
│       ├── tc-cbq.8
│       ├── tc-cbq-details.8
│       ├── tc-choke.8
│       ├── tc-codel.8
│       ├── tc-drr.8
│       ├── tc-ematch.8
│       ├── tc-fq_codel.8
│       ├── tc-hfsc.8
│       ├── tc-htb.8
│       ├── tc-netem.8
│       ├── tc-pfifo.8
│       ├── tc-pfifo_fast.8
│       ├── tc-prio.8
│       ├── tc-red.8
│       ├── tc-sfb.8
│       ├── tc-sfq.8
│       ├── tc-stab.8
│       └── tc-tbf.8
├── misc
│   ├── arpd.c
│   ├── ifstat.c
│   ├── lnstat.c
│   ├── lnstat.h
│   ├── lnstat_util.c
│   ├── Makefile
│   ├── nstat.c
│   ├── rtacct.c
│   ├── ss.c
│   ├── ssfilter.h
│   └── ssfilter.y
├── netem
│   ├── experimental.dat
│   ├── Makefile
│   ├── maketable.c
│   ├── normal.c
│   ├── pareto.c
│   ├── paretonormal.c
│   ├── README.distribution
│   └── stats.c
├── README
├── README.decnet
├── README.devel
├── README.distribution
├── README.iproute2+tc
├── README.lnstat
├── tc
│   ├── em_canid.c
│   ├── em_cmp.c
│   ├── em_ipset.c
│   ├── em_meta.c
│   ├── em_nbyte.c
│   ├── emp_ematch.l
│   ├── emp_ematch.y
│   ├── em_u32.c
│   ├── f_basic.c
│   ├── f_cgroup.c
│   ├── f_flow.c
│   ├── f_fw.c
│   ├── f_route.c
│   ├── f_rsvp.c
│   ├── f_tcindex.c
│   ├── f_u32.c
│   ├── m_action.c
│   ├── Makefile
│   ├── m_csum.c
│   ├── m_ematch.c
│   ├── m_ematch.h
│   ├── m_estimator.c
│   ├── m_gact.c
│   ├── m_ipt.c
│   ├── m_mirred.c
│   ├── m_nat.c
│   ├── m_pedit.c
│   ├── m_pedit.h
│   ├── m_police.c
│   ├── m_simple.c
│   ├── m_skbedit.c
│   ├── m_xt.c
│   ├── m_xt_old.c
│   ├── p_icmp.c
│   ├── p_ip.c
│   ├── p_tcp.c
│   ├── p_udp.c
│   ├── q_atm.c
│   ├── q_cbq.c
│   ├── q_choke.c
│   ├── q_codel.c
│   ├── q_drr.c
│   ├── q_dsmark.c
│   ├── q_fifo.c
│   ├── q_fq.c
│   ├── q_fq_codel.c
│   ├── q_gred.c
│   ├── q_hfsc.c
│   ├── q_htb.c
│   ├── q_ingress.c
│   ├── q_mqprio.c
│   ├── q_multiq.c
│   ├── q_netem.c
│   ├── q_prio.c
│   ├── q_qfq.c
│   ├── q_red.c
│   ├── q_rr.c
│   ├── q_sfb.c
│   ├── q_sfq.c
│   ├── q_tbf.c
│   ├── README.last
│   ├── static-syms.c
│   ├── tc.c
│   ├── tc_cbq.c
│   ├── tc_cbq.h
│   ├── tc_class.c
│   ├── tc_common.h
│   ├── tc_core.c
│   ├── tc_core.h
│   ├── tc_estimator.c
│   ├── tc_filter.c
│   ├── tc_monitor.c
│   ├── tc_qdisc.c
│   ├── tc_red.c
│   ├── tc_red.h
│   ├── tc_stab.c
│   ├── tc_util.c
│   └── tc_util.h
└── testsuite
    ├── configs
    │   ├── all-2.4
    │   ├── all-no-act
    │   └── all-police-act
    ├── iproute2
    │   └── Makefile
    ├── lib
    │   └── generic.sh
    ├── Makefile
    └── tests
        ├── cbq.t
        ├── cls-testbed.t
        ├── dsmark.t
        └── policer

37 directories, 382 files


```
