WARNING: CONFIG_IP_NF_MATCH_ECN is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables ecn match

WARNING: CONFIG_BLK_CGROUP is invalid
It is unset
Allowed values : y, !
Comment says: systemd (optional): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html

WARNING: CONFIG_IP_NF_TARGET_MASQUERADE is invalid
It is unset
Allowed values : y, m, !
Comment says: connman (optional): support tethering, http://git.kernel.org/cgit/network/connman/connman.git/commit/README?id=19fe7cad485afa6a7a5cc4aa75615ce8b7b8d376

WARNING: CONFIG_CPUSETS is invalid
It is unset
Allowed values : y, m, !
Comment says: lxc (optional): required to run lxc containers

WARNING: CONFIG_IP6_NF_MATCH_AH is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for ip6tables ah match

WARNING: CONFIG_ECRYPT_FS is invalid
It is unset
Allowed values : y, m, !
Comment says: optional extra filesystem (ecryptfs)

WARNING: CONFIG_LOCKD_V4 is invalid
It is unset
Allowed values : y, !
Comment says: optional, for NFS support

ERROR: CONFIG_DEVTMPFS_MOUNT is invalid
It is unset
Allowed values : y
Comment says: Required by hybris-boot init-script

WARNING: CONFIG_LBDAF is invalid
It is unset
Allowed values : y, !
Comment says: ext4 filesystem requires this in order to support filesysetms with huge_file feature, which is enabled by default by mke2fs.ext4

WARNING: CONFIG_BT_RFCOMM is invalid
It is unset
Allowed values : y, !
Comment says: Bluez (optional): Needed if bluez used as bluetooth stack

WARNING: CONFIG_SCHEDSTATS is invalid
It is unset
Allowed values : y, !
Comment says: systemd-bootchart (optional): http://cgit.freedesktop.org/systemd/systemd/commit/README?id=f1c24fea94e19cf2108abbeed1d36ded7102ab98

ERROR: CONFIG_TMPFS_POSIX_ACL is invalid
It is unset
Allowed values : y
Comment says: systemd: required by hybris-boot init-script, if you want pam_systemd.so to setup your "seats". http://cgit.freedesktop.org/systemd/systemd/commit/README?id=77b6e19458f37cfde127ec6aa9494c0ac45ad890

WARNING: CONFIG_NETFILTER_XT_MATCH_HASHLIMIT is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables hashlimit match

WARNING: CONFIG_CGROUP_MEM_RES_CTLR_KMEM is invalid
It is unset
Allowed values : y, !, <=3.5
Comment says: systemd (optional): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html, only valid if kernel version <= 3.5

ERROR: CONFIG_TIMERFD is invalid
It is unset
Allowed values : y
Comment says: systemd: http://cgit.freedesktop.org/systemd/systemd/commit/README?id=713bc0cfa477ca1df8769041cb3dbc83c10eace2

WARNING: CONFIG_CGROUP_MEM_RES_CTLR is invalid
It is unset
Allowed values : y, !, <=3.5
Comment says: systemd (optional): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html, only valid if kernel version <= 3.5

ERROR: CONFIG_IKCONFIG_PROC is invalid
It is unset
Allowed values : y
Comment says: Required by hybris-boot init-script

WARNING: CONFIG_CGROUP_DEVICE is invalid
It is unset
Allowed values : y, !
Comment says: systemd (optional): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html

WARNING: CONFIG_SECURITY_SELINUX_BOOTPARAM is invalid
It is unset
Allowed values : y, !
Comment says: Required by hybris, SELinux needs to be disabled. Leave as not set, if you have unset AUDIT (read more about the CONFIG_AUDIT flag)

WARNING: CONFIG_BT_HCIUART_H4 is invalid
It is unset
Allowed values : y, !
Comment says: Bluez (optional): Needed if bluez used as bluetooth stack

WARNING: CONFIG_NFS_ACL_SUPPORT is invalid
It is unset
Allowed values : y, m, !
Comment says: optional, for NFS support

WARNING: CONFIG_TUN is invalid
It is unset
Allowed values : y, m, !
Comment says: ofono: http://git.kernel.org/?p=network/ofono/ofono.git;a=blob;f=README;h=413d789e5f9e96024986f5116d3c8aff0c9f15b8;hb=HEAD#l28

ERROR: CONFIG_NET is invalid
It is unset
Allowed values : y
Comment says: systemd: http://cgit.freedesktop.org/systemd/systemd/commit/README?id=41938693e76c32161d2b3b83253ce996468cbf9b

ERROR: CONFIG_SIGNALFD is invalid
It is unset
Allowed values : y
Comment says: systemd: http://cgit.freedesktop.org/systemd/systemd/commit/README?id=713bc0cfa477ca1df8769041cb3dbc83c10eace2

WARNING: CONFIG_RTC_DRV_CMOS is invalid
It is unset
Allowed values : y, !
Comment says: optional, but highly recommended

WARNING: CONFIG_NETFILTER_NETLINK_ACCT is invalid
It is unset
Allowed values : y, m, !
Comment says: connman (optional): for routing and statistic support in sessions, http://git.kernel.org/cgit/network/connman/connman.git/commit/README?id=41f37125887cb9208da2441e350e1e3324c17ee6

ERROR: CONFIG_NETFILTER_XT_MATCH_QTAGUID is invalid
It is unset
Allowed values : y, m
Comment says: connman: for iptables owner/qtaguid match

ERROR: CONFIG_NETFILTER_XT_MATCH_CONNTRACK is invalid
It is unset
Allowed values : y
Comment says: connman: for iptables conntrack match

WARNING: CONFIG_NF_NAT_IPV6 is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: to enable IPv6 NAT

WARNING: CONFIG_NETFILTER_XT_MATCH_IPRANGE is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables iprange match

WARNING: CONFIG_SCHED_DEBUG is invalid
It is unset
Allowed values : y, !
Comment says: systemd-bootchart (optional): http://cgit.freedesktop.org/systemd/systemd/commit/README?id=f1c24fea94e19cf2108abbeed1d36ded7102ab98

WARNING: CONFIG_IP6_NF_MATCH_MH is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for ip6tables mh match

WARNING: CONFIG_WATCHDOG_NOWAYOUT is invalid
It is unset
Allowed values : y, !
Comment says: If device uses watchdogs with dsme (https://github.com/nemomobile/dsme), this option should be enabled or watchdog does not protect the device in case dsme crashes.

WARNING: CONFIG_NFS_FS is invalid
It is unset
Allowed values : y, m, !
Comment says: optional, for NFS support

WARNING: CONFIG_BLK_DEV_NBD is invalid
It is unset
Allowed values : y, m, !
Comment says: optional, for NFS & CIFS support

ERROR: CONFIG_IP_NF_MATCH_RPFILTER is invalid
It is unset
Allowed values : y
Comment says: Add to have both IPv4 and IPv6 RPFILTER matches set

WARNING: CONFIG_IPC_NS is invalid
It is unset
Allowed values : y, !
Comment says: optional, enables kernel namespaces for systemd-nspawn containers

ERROR: CONFIG_EPOLL is invalid
It is unset
Allowed values : y
Comment says: systemd: http://cgit.freedesktop.org/systemd/systemd/commit/README?id=713bc0cfa477ca1df8769041cb3dbc83c10eace2

WARNING: CONFIG_NETWORK_FILESYSTEMS is invalid
It is unset
Allowed values : y, !
Comment says: optional, for NFS support

WARNING: CONFIG_NFS_V4_1 is invalid
It is unset
Allowed values : y, !
Comment says: optional, for NFS support

WARNING: CONFIG_BRIDGE is invalid
It is unset
Allowed values : y, m, !
Comment says: connman (optional): support tethering, http://git.kernel.org/cgit/network/connman/connman.git/commit/README?id=19fe7cad485afa6a7a5cc4aa75615ce8b7b8d376

ERROR: CONFIG_NETFILTER_XT_MATCH_MULTIPORT is invalid
It is unset
Allowed values : y
Comment says: connman: for iptables multiple port match

WARNING: CONFIG_TMPFS_XATTR is invalid
It is unset
Allowed values : y, !
Comment says: systemd (optional): strongly recommended, http://cgit.freedesktop.org/systemd/systemd/commit/README?id=713bc0cfa477ca1df8769041cb3dbc83c10eace2

WARNING: CONFIG_IP_NF_MATCH_AH is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables ah match

WARNING: CONFIG_CIFS is invalid
It is unset
Allowed values : y, m, !
Comment says: optional extra filesystem (CIFS - Windows net fs)

WARNING: CONFIG_MEMCG_SWAP is invalid
It is unset
Allowed values : y, !, >=3.6
Comment says: systemd (optional, but recommended): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html, only valid if kernel version >= 3.6

WARNING: CONFIG_NFS_COMMON is invalid
It is unset
Allowed values : y, !
Comment says: optional, for NFS support

ERROR: CONFIG_CGROUPS is invalid
It is unset
Allowed values : y
Comment says: systemd: http://cgit.freedesktop.org/systemd/systemd/commit/README?id=713bc0cfa477ca1df8769041cb3dbc83c10eace2

WARNING: CONFIG_F2FS_FS is invalid
It is unset
Allowed values : y, m, !
Comment says: optional extra filesystem (f2fs - a good SD filesystem)

WARNING: CONFIG_NETPRIO_CGROUP is invalid
It is unset
Allowed values : y, !
Comment says: systemd (optional): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html

WARNING: CONFIG_SECCOMP is invalid
It is unset
Allowed values : y, !
Comment says: systemd (optional): strongly recommended, http://cgit.freedesktop.org/systemd/systemd/commit/README?id=f28cbd0382ca53baa99803bbc907a469fbf68128

WARNING: CONFIG_NETFILTER_XT_MATCH_LIMIT is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables limit match

ERROR: CONFIG_NLS_UTF8 is invalid
It is unset
Allowed values : y
Comment says: Ensure that we support UTF8 filenames.

WARNING: CONFIG_CGROUP_PERF is invalid
It is unset
Allowed values : y, !
Comment says: systemd (optional): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html

WARNING: CONFIG_IP_NF_MATCH_TTL is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables ttl match

WARNING: CONFIG_NETFILTER_XT_MATCH_DCCP is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables dccp match

WARNING: CONFIG_NETFILTER_XT_MATCH_MARK is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables mark match

WARNING: CONFIG_NET_CLS_CGROUP is invalid
It is unset
Allowed values : y, !
Comment says: systemd (optional): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html

WARNING: CONFIG_UDF_FS is invalid
It is unset
Allowed values : y, m, !
Comment says: optional extra filesystem (DVD & portable USB)

WARNING: CONFIG_NFS_V3_ACL is invalid
It is unset
Allowed values : y, !
Comment says: optional, for NFS support

WARNING: CONFIG_NETFILTER_XT_MATCH_PKTTYPE is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables pkttype match

WARNING: CONFIG_CGROUP_SCHED is invalid
It is unset
Allowed values : y, !
Comment says: systemd (optional): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html

WARNING: CONFIG_UTS_NS is invalid
It is unset
Allowed values : y, !
Comment says: optional, enables kernel namespaces for systemd-nspawn containers

WARNING: CONFIG_IP_MULTIPLE_TABLES is invalid
It is unset
Allowed values : y, m, !
Comment says: connman (optional): for routing and statistic support in sessions, http://git.kernel.org/cgit/network/connman/connman.git/commit/README?id=41f37125887cb9208da2441e350e1e3324c17ee6

WARNING: CONFIG_ANDROID_LOW_MEMORY_KILLER is invalid
It is unset
Allowed values : y, !
Comment says: Helping memory handling at least with Android runtime (tested on Jolla C)

WARNING: CONFIG_ISO9660_FS is invalid
It is unset
Allowed values : y, m, !
Comment says: optional extra filesystem (CD-ROM)

ERROR: CONFIG_INOTIFY_USER is invalid
It is unset
Allowed values : y
Comment says: systemd: http://cgit.freedesktop.org/systemd/systemd/commit/README?id=713bc0cfa477ca1df8769041cb3dbc83c10eace2

WARNING: CONFIG_NETFILTER_XT_MATCH_RECENT is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables recent match

WARNING: CONFIG_IP6_NF_MATCH_FRAG is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for ip6tables frag match

ERROR: CONFIG_RD_GZIP is invalid
It is unset
Allowed values : y
Comment says: Required by hybris-boot Android.mk

WARNING: CONFIG_NET_NS is invalid
It is unset
Allowed values : y, !
Comment says: optional, enables kernel namespaces for systemd-nspawn containers

WARNING: CONFIG_MODULES is invalid
It is unset
Allowed values : y, !
Comment says: optional, required for module support (Such as WLAN for example)

WARNING: CONFIG_NFS_V3 is invalid
It is unset
Allowed values : y, !
Comment says: optional, for NFS support

WARNING: CONFIG_NETFILTER_XT_MATCH_STATE is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables state match

WARNING: CONFIG_NETFILTER_XT_MATCH_SCTP is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables sctp match

WARNING: CONFIG_SUNRPC_GSS is invalid
It is unset
Allowed values : y, m, !
Comment says: optional, for NFS support

WARNING: CONFIG_NFS_USE_KERNEL_DNS is invalid
It is unset
Allowed values : y, !
Comment says: optional, for NFS support

ERROR: CONFIG_PROC_FS is invalid
It is unset
Allowed values : y
Comment says: systemd: http://cgit.freedesktop.org/systemd/systemd/commit/README?id=06d461ee6f3da6650e6d023d7828455752d70b0b

WARNING: CONFIG_FANOTIFY is invalid
It is unset
Allowed values : y, !
Comment says: optional, required for systemd readahead.

ERROR: CONFIG_FHANDLE is invalid
It is unset
Allowed values : y
Comment says: systemd: http://cgit.freedesktop.org/systemd/systemd/commit/README?id=001809282918f273d372f1ee09d10b783c18a474

WARNING: CONFIG_MEMCG is invalid
It is unset
Allowed values : y, !, >=3.6
Comment says: systemd (optional, but recommended): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html, only valid if version >= 3.6

ERROR: CONFIG_UNIX is invalid
It is unset
Allowed values : y
Comment says: UNIX sockets option is required to run Mer

ERROR: CONFIG_SYSVIPC is invalid
It is unset
Allowed values : y
Comment says: Inter Process Communication option is required to run Mer

WARNING: CONFIG_BT_HCIUART is invalid
It is unset
Allowed values : y, !
Comment says: Bluez (optional): Needed if bluez used as bluetooth stack

WARNING: CONFIG_IP_NF_IPTABLES is invalid
It is unset
Allowed values : y, m, !
Comment says: connman (optional): for routing and statistic support in sessions, http://git.kernel.org/cgit/network/connman/connman.git/commit/README?id=41f37125887cb9208da2441e350e1e3324c17ee6

WARNING: CONFIG_UEVENT_HELPER_PATH is invalid
It is unset
Allowed values : "", !
Comment says: should be empty, if you want to use systemd without initramfs. Also systemd: http://cgit.freedesktop.org/systemd/systemd/commit/README?id=713bc0cfa477ca1df8769041cb3dbc83c10eace2

WARNING: CONFIG_NETFILTER_XT_MATCH_HELPER is invalid
It is unset
Allowed values : y, m, !
Comment says: connman: for iptables helper match

ERROR: CONFIG_VT is invalid
It is unset
Allowed values : y
Comment says: Required for virtual consoles

WARNING: CONFIG_NETFILTER_XT_MATCH_CONNMARK is invalid
It is unset
Allowed values : y, m, !
Comment says: connman (optional): for routing and statistic support in sessions, http://git.kernel.org/cgit/network/connman/connman.git/commit/README?id=115cb9cbd3cdda00784e58a4ea12b42d128732b4

WARNING: CONFIG_F2FS_FS_SECURITY is invalid
It is unset
Allowed values : y, m, !
Comment says: required to mount f2fs volumes under SELinux

WARNING: CONFIG_CGROUP_MEM_RES_CTLR_SWAP is invalid
It is unset
Allowed values : y, !, <=3.5
Comment says: systemd (optional): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html, only valid if kernel version <= 3.5

WARNING: CONFIG_SECURITY_YAMA is invalid
It is unset
Allowed values : y, !
Comment says: optional, prevents user's processes from ptracing each other

WARNING: CONFIG_SUNRPC is invalid
It is unset
Allowed values : y, m, !
Comment says: optional, for NFS support

WARNING: CONFIG_NETFILTER_XT_CONNMARK is invalid
It is unset
Allowed values : y, m, !
Comment says: connman (optional): for routing and statistic support in sessions, http://git.kernel.org/cgit/network/connman/connman.git/commit/README?id=115cb9cbd3cdda00784e58a4ea12b42d128732b4

WARNING: CONFIG_NETFILTER_XT_TARGET_CONNMARK is invalid
It is unset
Allowed values : y, m, !
Comment says: connman (optional): for routing and statistic support in sessions, http://git.kernel.org/cgit/network/connman/connman.git/commit/README?id=115cb9cbd3cdda00784e58a4ea12b42d128732b4

WARNING: CONFIG_PID_NS is invalid
It is unset
Allowed values : y, !
Comment says: optional, enables kernel namespaces for systemd-nspawn containers

WARNING: CONFIG_BT is invalid
It is unset
Allowed values : y, !
Comment says: Bluez (optional): Needed if bluez used as bluetooth stack

WARNING: CONFIG_AUTOFS4_FS is invalid
It is unset
Allowed values : y, m, !
Comment says: systemd (optional): http://cgit.freedesktop.org/systemd/systemd/commit/README?id=713bc0cfa477ca1df8769041cb3dbc83c10eace2

WARNING: CONFIG_CGROUP_FREEZER is invalid
It is unset
Allowed values : y, !
Comment says: systemd (optional): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html

ERROR: CONFIG_DEVTMPFS is invalid
It is unset
Allowed values : y
Comment says: systemd: http://cgit.freedesktop.org/systemd/systemd/commit/README?id=713bc0cfa477ca1df8769041cb3dbc83c10eace2

WARNING: CONFIG_NETFILTER_XT_MATCH_NFACCT is invalid
It is unset
Allowed values : y, m, !
Comment says: connman (optional): for routing and statistic support in sessions, http://git.kernel.org/cgit/network/connman/connman.git/commit/README?id=41f37125887cb9208da2441e350e1e3324c17ee6

WARNING: CONFIG_BTRFS_FS is invalid
It is unset
Allowed values : y, !
Comment says: optional extra filesystem (BTRFS)

WARNING: CONFIG_SECURITY_YAMA_STACKED is invalid
It is unset
Allowed values : y, !, <4.3
Comment says: optional, only valid for kernel < 4.3

ERROR: CONFIG_IP6_NF_MATCH_RPFILTER is invalid
It is unset
Allowed values : y
Comment says: To be able to mitigate CVE-2019-14899 with ConnMan iptables rule

WARNING: CONFIG_LOCKD is invalid
It is unset
Allowed values : y, m, !
Comment says: optional, for NFS support

WARNING: CONFIG_EXT4_FS is invalid
It is unset
Allowed values : y, m, !
Comment says: Mer uses ext4 as rootfs by default

ERROR: CONFIG_SYSFS is invalid
It is unset
Allowed values : y
Comment says: systemd: http://cgit.freedesktop.org/systemd/systemd/commit/README?id=713bc0cfa477ca1df8769041cb3dbc83c10eace2

WARNING: CONFIG_IPV6 is invalid
It is unset
Allowed values : y, m, !
Comment says: systemd: http://cgit.freedesktop.org/systemd/systemd/tree/README#n37

WARNING: CONFIG_MEMCG_KMEM is invalid
It is unset
Allowed values : y, !, >=3.6
Comment says: systemd (optional, but recommended): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html, only valid if kernel version >= 3.6

WARNING: CONFIG_CGROUP_CPUACCT is invalid
It is unset
Allowed values : y, !
Comment says: systemd (optional): http://0pointer.de/blog/projects/cgroups-vs-cgroups.html

WARNING: CONFIG_NFS_V4 is invalid
It is unset
Allowed values : y, !
Comment says: optional, for NFS support

WARNING: CONFIG_NETFILTER_XT_MATCH_ESP is invalid
It is unset
Allowed values : y, m, !
Comment says: connmman: for iptables esp match

WARNING: CONFIG_CHECKPOINT_RESTORE is invalid
It is unset
Allowed values : y, !
Comment says: rich-core-dumper (https://github.com/mer-tools/sp-rich-core/) needs this to collect all data for environment recreation.

WARNING: CONFIG_HIDRAW is invalid
It is unset
Allowed values : y, m, !
Comment says: optional: Support HID devices
