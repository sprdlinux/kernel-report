16:58:04@~/sprdroid5.0_trunk/kernel$ git log --graph --oneline  linux-lts/linux-3.18.y 
* 96e199f Linux 3.18.10
* da7a053 cxl: Add missing return statement after handling AFU errror
* 3bc64c1 cxl: Fix device_node reference counting
* 0153a8f cxl: Use image state defaults for reloading FPGA
* 22374fc clk-gate: fix bit # check in clk_register_gate()
* 9acb057 sched/autogroup: Fix failure to set cpu.rt_runtime_us
* c462adc vmstat: do not use deferrable delayed work for vmstat_update
* 71a2b6d pinctrl: imx25: fix numbering for pins
* 248f2c5 pinctrl: pinctrl-imx: don't use invalid value of conf_reg
* a5754ab ath5k: fix spontaneus AR5312 freezes
* 46b6f10 GFS2: Fix crash during ACL deletion in acl max entry check in gfs2_set_acl()
* c0064e1 of/pci: Free resources on failure in of_pci_get_host_bridge_resources()
* f42e86dc sched: Fix hrtick_start() on UP
* ac99673 stable_kernel_rules: reorganize and update submission options
* a607783 ASoC: rt5670: Set RT5670_IRQ_CTRL1 non volatile
* 651b0e4 ASoC: omap-pcm: Correct dma mask
* 1b9428b NFSv4: Don't call put_rpccred() under the rcu_read_lock()
* 6394d0e NFS: Don't invalidate a submounted dentry in nfs_prime_dcache()
* 76e118b ACPI / LPSS: provide con_id for the clkdev
* 78f8ef0 ACPI / video: Load the module even if ACPI is disabled
* 4a1167f eCryptfs: don't pass fs-specific ioctl commands through
* e16752a efi/libstub: Fix boundary checking in efi_high_alloc()
* f3b9a85 efi: Small leak on error in runtime map code
* 95379cd nfsd: fix clp->cl_revoked list deletion causing softlock in nfsd
* 6a6eed5 reservation: Remove shadowing local variable 'ret'
* eb67532 drm/i915: avoid processing spurious/shared interrupts in low-power states
* fc6f347 drm/i915: Dell Chromebook 11 has PWM backlight
* a0e57b2 drm/i915: Check obj->vma_list under the struct_mutex
* 914b78e drm/i915/bdw: PCI IDs ending in 0xb are ULT.
* f69d665 drm/radeon: fix 1 RB harvest config setup for TN/RL
* 7b1fcda drm/radeon: use drm_mode_vrefresh() rather than mode->vrefresh
* 8144751 drm/radeon: enable native backlight control on old macs
* 60efb89 HID: wacom: Report ABS_MISC event for Cintiq Companion Hybrid
* c6cbffb HID: fixup the conflicting keyboard mappings quirk
* 1e1d4d7 HID: input: fix confusion on conflicting mappings
* a437367 staging: comedi: cb_pcidas64: fix incorrect AI range code handling
* 29bc146 dm snapshot: fix a possible invalid memory access on unload
* ed68077 dm: fix a race condition in dm_get_md
* 48703ea dm io: reject unsupported DISCARD requests with EOPNOTSUPP
* 0a877df dm mirror: do not degrade the mirror on discard error
* 0e60c38 staging: comedi: comedi_compat32.c: fix COMEDI_CMD copy back
* d3fd045 sunxi: clk: Set sun6i-pll1 n_start = 1
* af33873 clk: Fix debugfs clk removal before inited
* 5be4a62 clk: zynq: Force CPU_2X clock to be ungated
* 83ace36 fixed invalid assignment of 64bit mask to host dma_boundary for scatter gather segment boundary limit.
* 814643b nilfs2: fix potential memory overrun on inode
* 6ff59ab IB/core: When marshaling ucma path from user-space, clear unused fields
* f90ead8 IB/core: Fix deadlock on uverbs modify_qp error flow
* b092f84 IB/mlx4: Fix wrong usage of IPv4 protocol for multicast attach/detach
* f8a4faf IB/mlx4: Fix memory leak in __mlx4_ib_modify_qp
* aeda89a IB/mlx5: Fix error code in get_port_caps()
* 78a1437 IB/iser: Use correct dma direction when unmapping SGs
* caa2a1a IB/iser: Fix memory regions possible leak
* bbc56fb IB/qib: Do not write EEPROM
* 26a3448 sg: fix read() error reporting
* 6366973 locking/rtmutex: Avoid a NULL pointer dereference on deadlock
* e055b8c ALSA: hda - One more Dell macine needs DELL1_MIC_NO_PRESENCE quirk
* 33da15b ALSA: hda - Disable runtime PM for Panther Point again
* fc30e76 ALSA: hda: controller code - do not export static functions
* c78962a ALSA: hda - Add pin configs for ASUS mobo with IDT 92HD73XX codec
* 10556d5 ALSA: pcm: Don't leave PREPARED state after draining
* d2d74ad4 serial: 8250: Revert "tty: serial: 8250_core: read only RX if there is something in the FIFO"
* 8ca9d12 tty: fix up atime/mtime mess, take four
* b7dc640 ARC: Fix KSTK_ESP()
* 8ed378b SUNRPC: Always manipulate rpc_rqst::rq_bc_pa_list under xprt->bc_pa_lock
* ca261c9 sunrpc: fix braino in ->poll()
* 208fb83 procfs: fix race between symlink removals and traversals
* c74eb98 debugfs: leave freeing a symlink body until inode eviction
* be9eb99 autofs4 copy_dev_ioctl(): keep the value of ->size we'd used for allocation
* 318dc9c USB: serial: fix tty-device error handling at probe
* acc6963 USB: serial: fix potential use-after-free after failed probe
* 2e52da5 TTY: fix tty_wait_until_sent on 64-bit machines
* ec02f95 USB: serial: fix infinite wait_until_sent timeout
* d6bc66d net: irda: fix wait_until_sent poll timeout
* 13c5441 mac80211: Send EAPOL frames at lowest rate
* 1d2dcde xhci: Workaround for PME stuck issues in Intel xhci
* 662a8fb xhci: fix reporting of 0-sized URBs in control endpoint
* cc40531 xhci: Allocate correct amount of scratchpad buffers
* 9e3e203 usb: XHCI: platform: Move the Marvell quirks after the enabling the clocks
* 8bea8b4 usb: gadget: configfs: don't NUL-terminate (sub)compatible ids
* 0921401 usb: dwc3: dwc3-omap: Fix disable IRQ
* e377af7 usb: ftdi_sio: Add jtag quirk support for Cyber Cortex AV boards
* 7ab6306 USB: ftdi_sio: add PIDs for Actisense USB devices
* 9705b41 USB: usbfs: don't leak kernel data in siginfo
* 4057033 USB: mxuport: fix null deref when used as a console
* e7d3ac3 USB: serial: cp210x: Adding Seletek device id's
* 64264c3 Revert "USB: serial: make bulk_out_size a lower limit"
* ddcc85e uas: Add US_FL_NO_REPORT_OPCODES for JMicron JMS539
* a3ee104 KVM: MIPS: Fix trace event to save PC directly
* c8b6504 KVM: emulate: fix CMPXCHG8B on 32-bit hosts
* 218c886 Btrfs:__add_inode_ref: out of bounds memory read when looking for extended ref.
* 0ab9252 Btrfs: fix data loss in the fast fsync path
* d771f1d btrfs: fix lost return value due to variable shadowing
* 67b67df Btrfs: fix fsync race leading to ordered extent memory leaks
* 85f1ab8 mei: make device disabled on stop unconditionally
* 2c76bd8 iio:adc:mcp3422 Fix incorrect scales table
* 328499b iio: ad5686: fix optional reference voltage declaration
* 30fa0db iio: mxs-lradc: only update the buffer when its conversions have finished
* 9f074c6 iio: mxs-lradc: make ADC reads not unschedule touchscreen conversions
* 1322dc3 iio: mxs-lradc: make ADC reads not disable touchscreen interrupts
* 567a6d5 iio: mxs-lradc: separate touchscreen and buffer virtual channels
* c0d65db iio: imu: adis16400: Fix sign extension
* ec23c85 iio: mxs-lradc: fix iio channel map regression
* 6ddd115 x86/fpu/xsaves: Fix improper uses of __ex_table
* ce5dd33 x86/asm/entry/64: Remove a bogus 'ret_from_fork' optimization
* cdc937a target: Check for LBA + sectors wrap-around in sbc_parse_cdb
* f38a130 target: Add missing WRITE_SAME end-of-device sanity check
* aff40ba target: Fix PR_APTPL_BUF_LEN buffer size limitation
* e12d499 drm/i915: Correct the IOSF Dev_FN field for IOSF transfers
* 5c8bf2b drm/i915: Prevent use-after-free in invalidate_range_start callback
* 4182c01 drm/i915: Drop vblank wait from intel_dp_link_down
* 2de5e09 drm/i915: Insert a command barrier on BLT/BSD cache flushes
* 93fd529 drm/radeon: fix voltage setup on hawaii
* c112fd1 drm/radeon/dp: Set EDP_CONFIGURATION_SET for bridge chips if necessary
* 5b77767 drm/radeon: workaround for CP HW bug on CIK
* fee477d drm/radeon: only enable kv/kb dpm interrupts once v3
* 22d4d7e drm/radeon: Don't try to enable write-combining without PAT
* c5131a9 drm/tegra: Use correct relocation target offsets
* b7c386c mm: fix negative nr_isolated counts
* 463fb5a mm/memory.c: actually remap enough memory
* 42af81d mm/compaction: fix wrong order check in compact_finished()
* f0f7d8f mm/nommu.c: fix arithmetic overflow in __vm_enough_memory()
* 64ac320 mm/mmap.c: fix arithmetic overflow in __vm_enough_memory()
* 8473518 mm: when stealing freepages, also take pages created by splitting buddy page
* 6f59e64 mm, hugetlb: remove unnecessary lower bound on sysctl handlers"?
* ac36991 mm/hugetlb: add migration entry check in __unmap_hugepage_range
* fa94a39 mm/hugetlb: add migration/hwpoisoned entry check in hugetlb_change_protection
* 674eefd mm/hugetlb: fix getting refcount 0 page in hugetlb_fault()
* c3b2b0d team: don't traverse port list using rcu in team_set_mac_address
* f009d6b net: ping: Return EAFNOSUPPORT when appropriate.
* 1b5d485 udp: only allow UFO for packets from SOCK_DGRAM sockets
* af5b76c usb: plusb: Add support for National Instruments host-to-host cable
* 0972883 net: do not use rcu in rtnl_dump_ifinfo()
* 29db1c2 net: bcmgenet: fix throughtput regression
* e2aaa2c macvtap: make sure neighbour code can push ethernet header
* 7c03ec3 net: compat: Ignore MSG_CMSG_COMPAT in compat_sys_{send, recv}msg
* 722243f team: fix possible null pointer dereference in team_handle_frame
* 5395001 net: pktgen: disable xmit_clone on virtual devices
* 4e7a29f Revert "r8169: add support for Byte Queue Limits"
* e664c2c net: reject creation of netdev names with colons
* 4946f9d sock: sock_dequeue_err_skb() needs hard irq safety
* 91f3fc9 openvswitch: Fix net exit.
* cbac74b ematch: Fix auto-loading of ematch modules.
* e6aa677 net: phy: Fix verification of EEE support in phy_init_eee
* e95afb0 ipv4: ip_check_defrag should not assume that skb_network_offset is zero
* 913c52e ipv4: ip_check_defrag should correctly check return value of skb_copy_bits
* aaf410b gen_stats.c: Duplicate xstats buffer for later use
* 8652a96 rtnetlink: call ->dellink on failure when ->newlink exists
* 677aa4a ipv6: fix ipv6_cow_metrics for non DST_HOST case
* 82629d5 tcp: make sure skb is not shared before using skb_get()
* 33617de rtnetlink: ifla_vf_policy: fix misuses of NLA_BINARY
* 76936e5 pktgen: fix UDP checksum computation
* 5cd5724 ipv6: addrconf: add missing validate_link_af handler
* a7dc52c flowcache: Fix kernel panic in flow_cache_flush_task
* d1034e8 Linux 3.18.9
* 83b7094a quota: Store maximum space limit in bytes
* 1e5c872 x86/irq: Fix regression caused by commit b568b8601f05
* 25dd360 x86: pmc-atom: Assign debugfs node as soon as possible
* 805f25c x86, mm/ASLR: Fix stack randomization on 64-bit systems
* 55c0226 x86/efi: Avoid triple faults during EFI mixed mode calls
* b715907 blk-throttle: check stats_cpu before reading it from sysfs
* f8d6da8 Btrfs: fix fsync data loss after adding hard link to inode
* 751e276 btrfs: fix leak of path in btrfs_find_item
* b4d32c3 btrfs: set proper message level for skinny metadata
* cd95650 libceph: fix double __remove_osd() problem
* b3b3972 samsung-laptop: Add use_native_backlight quirk, and enable it on some models
* 37ae6d6 jffs2: fix handling of corrupted summary length
* 6a35db9 EDAC, amd64_edac: Prevent OOPS with >16 memory controllers
* 90de8c9 sb_edac: Fix detection on SNB machines
* 177f6a7 md/raid1: fix read balance when a drive is write-mostly.
* dbf3bbd md/raid5: Fix livelock when array is both resyncing and degraded.
* f2ee626 perf tools: Fix probing for PERF_FLAG_FD_CLOEXEC flag
* df1d651 clocksource: mtk: Fix race conditions in probe code
* 32effd1 metag: Fix KSTK_EIP() and KSTK_ESP() macros
* 1a5f213 xfs: Fix quota type in quota structures when reusing quota file
* 171f992 gpio: tps65912: fix wrong container_of arguments
* 7229e9b gpiolib: of: allow of_gpiochip_find_and_xlate to find more than one chip per node
* a4fedc8 arm64: compat Fix siginfo_t -> compat_siginfo_t conversion on big endian
* 17392a1 hx4700: regulator: declare full constraints
* d7e4888 x86/xen: Treat SCI interrupt as normal GSI interrupt
* 0b4a17f KVM: s390: avoid memory leaks if __inject_vm() fails
* 6d6cdca KVM: s390: floating irqs: fix user triggerable endless loop
* 6d351ca KVM: s390: base hrtimer on a monotonic clock
* ed9eb28 KVM: s390: forward hrtimer if guest ckc not pending yet
* d204feb KVM: x86: update masterclock values on TSC writes
* f21d9d4 udf: Check length of extended attributes and allocation descriptors
* f414565 udf: Remove repeated loads blocksize
* 09f2e74 MIPS: HTW: Prevent accidental HTW start due to nested htw_{start, stop}
* b3b345a ARC: fix page address calculation if PAGE_OFFSET != LINUX_LINK_BASE
* 8f9b87b serial: fsl_lpuart: avoid new transfer while DMA is running
* 5716a78 serial: fsl_lpuart: delete timer on shutdown
* 20dcda8 ntp: Fixup adjtimex freq validation on 32-bit systems
* ab66a1f kdb: fix incorrect counts in KDB summary command output
* 67d4f78 ARM: mvebu: build armada375-smp code conditionally
* 9487809 ARM: vexpress: use ARM_CPU_SUSPEND if needed
* 4a6cc3b ARM: pxa: add regulator_has_full_constraints to poodle board file
* 30cb324 ARM: pxa: add regulator_has_full_constraints to corgi board file
* 6122424 vt: provide notifications on selection changes
* 4e5b83d USB: add flag for HCDs that can't receive wakeup requests (isp1760-hcd)
* 76730c9 USB: don't cancel queued resets when unbinding drivers
* 482b4b7 usb: core: buffer: smallest buffer should start at ARCH_DMA_MINALIGN
* 7a0c5e1 USB: fix use-after-free bug in usb_hcd_unlink_urb()
* c865d81 USB: cp210x: add ID for RUGGEDCOM USB Serial Console
* 986718d mei: me: release hw from reset only during the reset flow
* c27fd6e mei: mask interrupt set bit on clean reset bit
* 7e4f91b tty/serial: at91: fix error handling in atmel_serial_probe()
* 07ed07a tty: Prevent untrappable signals from malicious program
* 532f6e6 axonram: Fix bug in direct_access
* 3ddf67d smack: fix possible use after frees in task_security() callers
* 49c1bf0 ring-buffer: Do not wake up a splice waiter when page is not full
* e5b55e1 cipso: don't use IPCB() to locate the CIPSO IP option
* 4a07d7d cfq-iosched: fix incorrect filing of rt async cfqq
* e83be4d cfq-iosched: handle failure of cfq group allocation
* e78f848 iscsi-target: Drop problematic active_ts_list usage
* fe34c4e sg: fix EWOULDBLOCK errors with scsi-mq
* ba48f24 sg: fix unkillable I/O wait deadlock with scsi-mq
* 70bcf9f NFSv4.1: Fix a kfree() of uninitialised pointers in decode_cb_sequence_args
* 7952f49 NFSv4: Ensure we reference the inode for return-on-close in delegreturn
* bcc9c50 SUNRPC: NULL utsname dereference on NFS umount during namespace cleanup
* 08be8f0 nfs41: .init_read and .init_write can be called with valid pg_lseg
* 052f8db Added Little Endian support to vtpm module
* 4243c6c tpm/tpm_i2c_stm_st33: Fix potential bug in tpm_stm_i2c_send
* 2a7a206 tpm: Fix NULL return in tpm_ibmvtpm_get_desired_dma
* 73da074 char: tpm: Add missing error check for devm_kzalloc
* 2bce1b5 TPM: Add new TPMs to the tail of the list to prevent inadvertent change of dev
* 675643b tpm_tis: verify interrupt during init
* c8fc365 ARM: dts: BCM63xx: fix L2 cache properties
* 0eb370c ARM: dts: am335x-bone*: usb0 is hardwired for peripheral
* 120cd11 ARM: dts: tegra20: fix GR3D, DSI unit and reg base addresses
* 11cfd8b ARM: DRA7: hwmod: Fix boot crash with DEBUG_LL enabled on UART3
* d53ecbb ARM: 8284/1: sa1100: clear RCSR_SMR on resume
* 7da36aa blk-mq: fix double-free in error path
* d2c8636 tracing: Fix unmapping loop in tracing_mark_write
* bebc511 mm/hugetlb: pmd_huge() returns true for non-present hugepage
* aa07e80 MIPS: Export MSA functions used by lose_fpu(1) for KVM
* b91d95f9 MIPS: Export FP functions used by lose_fpu(1) for KVM
* e3201ff MIPS: asm: pgtable: Prevent HTW race when updating PTEs
* 6ce23db MIPS: asm: pgtable: Add c0 hazards on HTW start/stop sequences
* ef20dc5 MIPS: asm: asmmacro: Replace "add" instructions with "addu"
* 2aac25e MIPS: kernel: cps-vec: Replace "addi" with "addiu"
* 6a5f2ac MIPS: Alchemy: Fix cpu clock calculation
* 22d0e08 KVM: MIPS: Don't leak FPU/DSP to guest
* ceab52b KVM: MIPS: Disable HTW while in guest
* 4a73309 NFS: struct nfs_commit_info.lock must always point to inode->i_lock
* e616478 nfs: don't call blocking operations while !TASK_RUNNING
* c08ed34 proc/pagemap: walk page tables under pte lock
* ac8623f mmc: sdhci-pxav3: Fix Armada 38x controller's caps according to erratum ERR-7878951
* 2bca6f8 mmc: sdhci-pxav3: Fix SDR50 and DDR50 capabilities for the Armada 38x flavor
* dd55350 mmc: sdhci-pxav3: fix setting of pdata->clk_delay_cycles
* 4d025d8 mmc: sdhci-pxav3: fix unbalanced clock issues during probe
* 1229822 em28xx-audio: fix missing newlines, again
* 21bfc5a em28xx-dvb: fix missing newlines
* 5d2093b em28xx-video: fix missing newlines
* b7bd0ea em28xx-core: fix missing newlines
* 058eb67 em28xx-audio: fix missing newlines
* 3c17bf1 em28xx-input: fix missing newlines
* d28003a em28xx: ensure "closing" messages terminate with a newline
* 33b2fb5 timberdale: do not select TIMB_DMA
* 7497d7d rc-main: Re-apply filter for no-op protocol change
* aedfcf1 megaraid_sas: disable interrupt_mask before enabling hardware interrupts
* 138fb06 megaraid_sas: fix the problem of non-existing VD exposed to host
* 45e9f5c megaraid_sas: endianness related bug fixes and code optimization
* c2d3b46 power: gpio-charger: balance enable/disable_irq_wake calls
* ff5405c power: bq24190: Fix ignored supplicants
* cba19a2 power_supply: 88pm860x: Fix leaked power supply on probe fail
* b52ef41 ALSA: hdspm - Constrain periods to 2 on older cards
* 42596d7 ALSA: hda - enable mute led quirk for one more hp machine.
* d82c3f5 ALSA: hda - Set up GPIO for Toshiba Satellite S50D
* 72753a3 ALSA: off by one bug in snd_riptide_joystick_probe()
* 74945cb si2168: define symbol rate limits
* c51d7f70 lmedm04: Fix usb_submit_urb BOGUS urb xfer, pipe 1 != type 3 in interrupt urb
* e4d75d0 lmedm04: Increase Interupt due time to 200 msec
* 7ee6733 ACPI / LPSS: Deassert resets for SPI host controllers on Braswell
* 86e8d6b ACPI / LPSS: Always disable I2C host controllers
* bf14e51 xen-scsiback: mark pvscsi frontend request consumed only after last read
* beb843e xen/manage: Fix USB interaction issues when resuming
* 8ebba75 cpufreq: s3c: remove last use of resume_clocks callback
* 2b21e24 cpufreq: s3c: remove incorrect __init annotations
* bfb4e3f cpufreq: speedstep-smi: enable interrupts when waiting
* 125c662 cpufreq: Set cpufreq_cpu_data to NULL before putting kobject
* 66d955d rtlwifi: Remove logging statement that is no longer needed
* 78eb509 rtlwifi: rtl8192ee: Fix problems with calculating free space in FIFO
* 31151ff rtlwifi: rtl8192ee: Fix DMA stalls
* 791f7ad rtlwifi: rtl8192ee: Fix parsing of received packet
* 67861ed rtlwifi: rtl8192ee: Fix TX hang due to failure to update TX write point
* db8ecaa rtlwifi: rtl8192ee: Fix adhoc fail
* d71cea8 ASoC: davinci: fix DM365_EVM codec selection
* a09c233 ASoC: mioa701_wm9713: Fix speaker event
* e1f2c17 ASoC: rt5670: Set use_single_rw flag for regmap
* 9ada148 PCI: Fix infinite loop with ROM image of size 0
* c38fae9 PCI: Generate uppercase hex for modalias var in uevent
* dff8c9d HID: i2c-hid: Limit reads to wMaxInputLength bytes for input events
* e8f143e iwlwifi: mvm: always use mac color zero
* 71ed878 iwlwifi: mvm: fix failure path when power_update fails in add_interface
* 77786bd iwlwifi: mvm: validate tid and sta_id in ba_notif
* eba5407 iwlwifi: pcie: disable the SCD_BASE_ADDR when we resume from WoWLAN
* ed6e4ac fsnotify: fix handling of renames in audit
* 0dc8a9c xfs: set superblock buffer type correctly
* 3236381 xfs: set buf types when converting extent formats
* 4c60b12 xfs: inode unlink does not set AGI buffer type
* 3d2dae9 xfs: ensure buffer types are set correctly
* b2c618c random: Fix fast_mix() function
* 8b602c5 Bluetooth: btusb: Add support for Lite-On (04ca) Broadcom based, BCM43142
* 004db58 Bluetooth: btusb: Add support for Dynex/Insignia USB dongles
* 0cfe1a4 Bluetooth: btusb: Add Broadcom patchram support for ASUSTek devices
* f879c09 Bluetooth: Fix valid Identity Address check
* c86e12f Bluetooth: ath3k: Add support of AR3012 bluetooth 13d3:3423 device
* a73e33e Bluetooth: ath3k: workaround the compatibility issue with xHCI controller
* e5c9f0b Linux 3.18.8
* bdb39cc media/rc: Send sync space information on the lirc device
* 4e55dad ext4: ignore journal checksum on remount; don't fail
* a17ad4a net: sched: fix panic in rate estimators
* d2ddce3d hyperv: Fix the error processing in netvsc_send()
* 6743ca7 net: sctp: fix passing wrong parameter header to param_type2af in sctp_process_param
* 15f7f69 ppp: deflate: never return len larger than output buffer
* b974d00 ipv4: tcp: get rid of ugly unicast_sock
* 617417f tcp: ipv4: initialize unicast_sock sk_pacing_rate
* 7a01893 bridge: dont send notification when skb->len == 0 in rtnl_bridge_notify
* db4d24b net: don't OOPS on socket aio
* e3b175f bnx2x: fix napi poll return value for repoll
* b0e7916 ipv6: replacing a rt6_info needs to purge possible propagated rt6_infos too
* 3a06a68 ping: Fix race in free in receive path
* faf8cf0 udp_diag: Fix socket skipping within chain
* 9ad1a95 ipv4: try to cache dst_entries which would cause a redirect
* c75e4b0 net: sctp: fix slab corruption from use after free on INIT collisions
* e452612 netxen: fix netxen_nic_poll() logic
* eb489005 ipv6: stop sending PTB packets for MTU < 1280
* 9e4cc1e net: rps: fix cpu unplug
* 8e9f6bd ip: zero sockaddr returned on error queue
* a17f9bf Linux 3.18.7
* 61cfce3 x86: mm: move mmap_sem unlock from mm_fault_error() to caller
* 299f459 x86/tlb/trace: Do not trace on CPU that is offline
* 409b0c0 tracing: Add condition check to RCU lockdep checks
* fef76ea hrtimer: Fix incorrect tai offset calculation for non high-res timer systems
* 1c3a363 smpboot: Add missing get_online_cpus() in smpboot_register_percpu_thread()
* ff0d188 x86, microcode: Return error from driver init code when loader is disabled
* 6ea9ca8 ARM: dts: Fix I2S1, I2S2 compatible for exynos4 SoCs
* dde4963 ALSA: ak411x: Fix stall in work callback
* 085d9e9 ASoC: sgtl5000: add delay before first I2C access
* c0c9fe8 ASoC: atmel_ssc_dai: fix start event for I2S mode
* 31bf97f lib/checksum.c: fix build for generic csum_tcpudp_nofold
* 1fb3267 arm64: Fix up /proc/cpuinfo
* e5e10c0 kconfig: Fix warning "‘jump’ may be used uninitialized"
* 4fb5076 drm/radeon: properly set vm fragment size for TN/RL
* 83108f2 drm/radeon: fix the crash in test functions
* 624ddd1 drm/radeon: fix the crash in benchmark functions
* 7530584 drm/radeon: fix PLLs on RS880 and older v2
* 2a1398b drm/radeon: don't init gpuvm if accel is disabled (v3)
* 7bb9e4a nilfs2: fix deadlock of segment constructor over I_SYNC flag
* 32a7d7c memcg, shmem: fix shmem migration to use lrucare
* a01e161 lib/checksum.c: fix carry in csum_tcpudp_nofold
* 0003499 mm: pagewalk: call pte_hole() for VM_PFNMAP during walk_page_range
* d2d9e9e md/raid5: fix another livelock caused by non-aligned writes.
* 0e84224 Complete oplock break jobs before closing file handle
* 714a56f ARM: 8299/1: mm: ensure local active ASID is marked as allocated on rollover
* 2e9560ee MIPS: traps: Fix inline asm ctc1 missing .set hardfloat
* 061aa85 MIPS: mipsregs.h: Add write_32bit_cp1_register()
* 69ab8e5 MIPS: Fix kernel lockup or crash after CPU offline/online
* a88c24f MIPS: OCTEON: fix kernel crash when offlining a CPU
* 83c9c2c MIPS: IRQ: Fix disable_irq on CPU IRQs
* dbbd278 MIPS: Fix C0_Pagegrain[IEC] support.
* 458919c sd: Fix max transfer length for 4k disks
* 0ee291a spi: imx: use pio mode for i.mx6dl
* 6fe528d spi: spi-fsl-dspi: Remove usage of devm_kzalloc
* 96c5584 PCI: Handle read-only BARs on AMD CS553x devices
* 42dcb70 PCI: Add NEC variants to Stratus ftServer PCIe DMI check
* 0df05be PCI: designware: Reject MSI-X IRQs
* 9a42a8a gpio: mcp23s08: handle default gpio base
* 64f2260 gpio: sysfs: fix memory leak in gpiod_sysfs_set_active_low
* 22f837c gpio: sysfs: fix memory leak in gpiod_export_link
* 9960914 Linux 3.18.6
* a6df136 xen/arm/arm64: introduce xen_arch_need_swiotlb
* b2f21d1 clocksource: arch_timer: Only use the virtual counter (CNTVCT) on arm64
* 793332a can: c_can: end pending transmission on network stop (ifdown)
* 427a574 HID: rmi: Check for additional ACM registers appended to F11 data report
* ce95554 perf/rapl: Fix crash in rapl_scale()
* 09c0adc perf/x86/intel: Add model number for Airmont
* 5a4a00b memcg: remove extra newlines from memcg oom kill log
* 8a71cc4 quota: Switch ->get_dqblk() and ->set_dqblk() to use bytes as space units
* 77ca136 drm/i915: fix inconsistent brightness after resume
* 50a4668 drm/i915: Init PPGTT before context enable
* bcee607 drm/i915: BDW Fix Halo PCI IDs marked as ULT.
* 817697b drm/i915: Only fence tiled region of object.
* e63fea1 drm: fix fb-helper vs MST dangling connector ptrs (v2)
* f1d5aa4 drivers: net: cpsw: discard dual emac default vlan configuration
* ba31c58 regulator: core: fix race condition in regulator_put()
* 198bcce drivers/rtc/rtc-s5m.c: terminate s5m_rtc_id array with empty element
* 072ef65 spi/pxa2xx: Clear cur_chip pointer before starting next message
* d483628 drm/radeon: Restore GART table contents after pinning it in VRAM v3
* 588039c drm/radeon: Split off gart_get_page_entry ASIC hook from set_page_entry
* c818bed drm/vmwgfx: Replace the hw mutex with a hw spinlock
* bc8eeaf dm cache: fix missing ERR_PTR returns and handling
* e046f3d dm thin: don't allow messages to be sent to a pool target in READ_ONLY or FAIL mode
* 6ab11bb ARM: mvebu: don't set the PL310 in I/O coherency mode when I/O coherency is disabled
* d5b4818 pinctrl: at91: allow to have disabled gpio bank
* a916db4 nl80211: fix per-station group key get/del and memory leak
* d75bd2a mac80211: only roll back station states for WDS when suspending
* aefbc0b mac80211: properly set CCK flag in radiotap
* 0c21735 NFSv4.1: Fix an Oops in nfs41_walk_client_list
* 19387f4 nfs: fix dio deadlock when O_DIRECT flag is flipped
* 203ba54 Input: i8042 - add noloop quirk for Medion Akoya E7225 (MD98857)
* 424befd Input: elantech - add more Fujtisu notebooks to force crc_enabled
* 74a0ac4 Input: synaptics - adjust min/max for Lenovo ThinkPad X1 Carbon 2nd
* 5e1b35c i2c: s3c2410: fix ABBA deadlock by keeping clock prepared
* f1764f8 uas: Add no-report-opcodes quirk for Simpletech devices with id 4971:8017
* 6e34056 usb-storage/SCSI: blacklist FUA on JMicron 152d:2566 USB-SATA controller
* f97b23d USB: Add OTG PET device to TPL
* 0539097 rbd: fix rbd_dev_parent_get() when parent_overlap == 0
* 186eb06 rbd: drop parent_ref in rbd_dev_unprobe() unconditionally
* a95d838 ALSA: seq-dummy: remove deadlock-causing events on close
* 7170885 powerpc/xmon: Fix another endiannes issue in RTAS call from xmon
* bccd8fd can: kvaser_usb: Fix state handling upon BUS_ERROR events
* 1c13b0f can: kvaser_usb: Retry the first bulk transfer on -ETIMEDOUT
* 40b50e0 can: kvaser_usb: Send correct context to URB completion
* 97a4392 can: kvaser_usb: Do not sleep in atomic context
* f952583 udf: Release preallocation on last writeable close
* 75229a2 ASoC: omap-mcbsp: Correct CBM_CFS dai format configuration
* c78af34 ASoC: simple-card: Fix crash in asoc_simple_card_unref()
* 971784f ASoC: soc-compress.c: fix NULL dereference
* 2605715 ASoC: fsl_esai: Fix incorrect xDC field width of xCCR registers
* 2b298f9 ASoC: pcm512x: Fix DSP program selection
* aaadfdb ASoC: wm8960: Fix capture sample rate from 11250 to 11025
* 338dcaf vm: make stack guard page errors return VM_FAULT_SIGSEGV rather than SIGBUS
* 4c0720f arc: mm: Fix build failure
* da7f8de vm: add VM_FAULT_SIGSEGV handling support
* 7b483af spi: dw-mid: fix FIFO size
* 128e534 spi: dw: Fix detecting FIFO depth
* 179ac90 x86, build: replace Perl script with Shell script
* c2d6598 Linux 3.18.5
* 47e4434 crypto: add missing crypto module aliases
* acc5ccb crypto: include crypto- module prefix in template
* f2efa86 crypto: prefix module autoloading with "crypto-"
* c4302b5 ACPI / PM: Do not disable wakeup GPEs that have not been enabled
* 11ba6ba iwlwifi: mvm: add a flag to enable match found notification
* 840b131 Revert "swiotlb-xen: pass dev_addr to swiotlb_tbl_unmap_single"
* 34be580 ipvs: uninitialized data with IP_VS_IPV6
* 4270214 netfilter: conntrack: fix race between confirmation and flush
* 9eed158 netfilter: nfnetlink: relax strict multicast group check from netlink_bind
* 436322e netfilter: nf_tables: fix flush ruleset chain dependencies
* 7266a6b netfilter: nfnetlink: validate nfnetlink header from batch
* 513c668 mm: get rid of radix tree gfp mask for pagecache_get_page
* 8326fa8 KEYS: close race between key lookup and freeing
* 101e595 ahci_xgene: Fix the endianess issue in APM X-Gene SoC AHCI SATA controller driver.
* 55f8b81 sata_dwc_460ex: fix resource leak on error path
* 990785d x86/apic: Re-enable PCI_MSI support for non-SMP X86_32
* 7b6b3d6 x86, tls: Interpret an all-zero struct user_desc as "no segment"
* e3b3b6d x86, tls, ldt: Stop checking lm in LDT_empty
* f84d9d8 KVM: x86: Fix of previously incomplete fix for CVE-2014-8480
* cb2567b KVM: x86: SYSENTER emulation is broken
* c546e47 x86, boot: Skip relocs when load address unchanged
* 056ad39 x86/tsc: Change Fast TSC calibration failed from error to info
* 246b6252 x86, hyperv: Mark the Hyper-V clocksource as being continuous
* ec987a1 clocksource: exynos_mct: Fix bitmask regression for exynos4_mct_write
* 89a2e6e x86, irq: Properly tag virtualization entry in /proc/interrupts
* 449af28 irqchip: atmel-aic-common: Prevent clobbering of priority when changing IRQ type
* 24f1a31 fix deadlock in cifs_ioctl_clone()
* 3436c0a bus: mvebu-mbus: fix support of MBus window 13
* 1f20756 ARM: mvebu: completely disable hardware I/O coherency
* 7b915d3 ARM: dts: imx25: Fix PWM "per" clocks
* e8e3b6d time: adjtimex: Validate the ADJ_FREQUENCY values
* 5f4d540 time: settimeofday: Validate the values of tv from user
* cfaa685 irqchip: omap-intc: Fix legacy DMA regression
* 538c2bc dm cache: fix problematic dual use of a single migration count variable
* 7bf9ed7 dm cache: share cache-metadata object across inactive and active DM tables
* 7536e0d vb2: fix vb2_thread_stop race conditions
* 5d9aa9e cx23885: Split Hauppauge WinTV Starburst from HVR4400 card entry
* a2d8617 ipr: wait for aborted command responses
* 587a7ba PCI: Mark Atheros AR93xx to avoid bus reset
* b01f144 PCI: Add flag for devices where we can't use bus reset
* 3365876 x86/PCI: Clip bridge windows to fit in upstream windows
* 73698b0 PCI: Add pci_bus_clip_resource() to clip to fit upstream window
* 9f2e98f PCI: Add pci_claim_bridge_resource() to clip window if necessary
* ad5fa86 PCI: Pass bridge device, not bus, when updating bridge windows
* d5adda6 drm/radeon: use rv515_ring_start on r5xx
* ff32f6a drm/radeon: add si dpm quirk list
* 4e77f9f drm/radeon: add a dpm quirk list
* 8dcffdd drm/i915: Fix mutex->owner inspection race under DEBUG_MUTEXES
* 00647db drm/i915: Ban Haswell from using RCS flips
* 7cc613f scripts/recordmcount.pl: There is no -m32 gcc option on Super-H anymore
* 8fdd4f7 workqueue: fix subtle pool management issue which can stall whole worker_pool
* 335b7ac ALSA: usb-audio: Add mic volume fix quirk for Logitech Webcam C210
* 362a0d6 libata: prevent HSM state change race between ISR and PIO
* 99bde8f libata: allow sata_sil24 to opt-out of tag ordered submission
* 28de6f3 mfd: rtsx_usb: Fix runtime PM deadlock
* 5a8405c mfd: tps65218: Make INT1 our status_base register
* fc904760 mfd: tps65218: Make INT[12] and STATUS registers volatile
* 515939f pinctrl: Fix two deadlocks
* ce441cb pinctrl: qcom: Don't iterate past end of function array
* b47d1db can: m_can: tag current CAN FD controllers as non-ISO
* 96bfa38 can: dev: fix crtlmode_supported check
* 71745ce Linux 3.18.4
* 0bcd13a KVM: nVMX: Disable unrestricted mode if ept=0
* 3e038e9 drm/i915: Kill check_power_well() calls
* 65f81cc vhost-scsi: Add missing virtio-scsi -> TCM attribute conversion
* 82bc9d0 target: Drop arbitrary maximum I/O size limit
* e7b2033 LOCKD: Fix a race when initialising nlmsvc_timeout
* 90293ff kbuild: Fix removal of the debian/ directory
* 51fbc05 x86, um: actually mark system call tables readonly
* b9d078c um: Skip futex_atomic_cmpxchg_inatomic() test
* dcd295f decompress_bunzip2: off by one in get_next_block()
* 13b2e3a iio: ad799x: Fix ad7991/ad7995/ad7999 config setup
* 8d62208 ARM: dts: dra7-evm: fix qspi device tree partition size
* 7a66eeb ARM: shmobile: sh73a0 legacy: Set .control_parent for all irqpin instances
* 25bcda8 ARM: dts: berlin: add broken-cd and set bus width for eMMC in Marvell DMP DT
* 4cb194f bus: omap_l3_noc: Correct returning IRQ_HANDLED unconditionally in the irq handler
* 397ee66 bus: omap_l3_noc: Add resume hook to restore context
* fa036ea ARM: omap5/dra7xx: Enable booting secondary CPU in HYP mode
* 3af7a88 ARM: omap5/dra7xx: Fix frequency typos
* 73ea8ac ARM: clk-imx6q: fix video divider for rev T0 1.0
* 61bca51 ARM: imx6q: drop unnecessary semicolon
* a3576e4 ARM: dts: imx51-babbage: Fix ULPI PHY reset modelling
* 1fb91db ARM: dts: imx25: Fix the SPI1 clocks
* 64c2607 ARM: imx6sx: Set PLL2 as parent of QSPI clocks
* 2e953b8 ARM: omap2plus_defconfig: use CONFIG_CPUFREQ_DT
* d3c248b Input: I8042 - add Acer Aspire 7738 to the nomux list
* aae7cd9 Input: i8042 - reset keyboard to fix Elantech touchpad detection
* 17afe47 Input: elantech - support new ICs types for version 4
* 17fb11a can: kvaser_usb: Don't send a RESET_CHIP for non-existing channels
* 9111e41 can: kvaser_usb: Reset all URB tx contexts upon channel close
* 198e0c9 can: kvaser_usb: Don't free packets when tight on URBs
* 81699fe usb: musb: stuff leak of struct usb_hcd
* 99688ec USB: EHCI: fix initialization bug in iso_stream_schedule()
* 7293491 USB: console: fix potential use after free
* 68d91b4 USB: console: fix uninitialised ldisc semaphore
* f33e402 usb: gadget: udc: atmel: fix possible oops when unloading module
* 967e562 usb: gadget: udc: atmel: fix possible IN hang issue
* c811188 usb: gadget: udc: atmel: change setting for DMA
* 84ac889 usb: gadget: gadgetfs: Free memory allocated by memdup_user()
* 2c5d2dd USB: keyspan: fix null-deref at probe
* 14d38f7 USB: qcserial/option: make AT URCs work for Sierra Wireless MC73xx
* 34aa8bb USB: cp210x: add IDs for CEL USB sticks and MeshWorks devices
* ee4597b USB: cp210x: fix ID for production CEL MeshConnect USB Stick
* 11fb1b9 usb: dwc3: gadget: Stop TRB preparation after limit is reached
* 64227c1 usb: dwc3: gadget: Fix TRB preparation during SG
* 8db5755 OHCI: add a quirk for ULi M5237 blocking on reset
* f0f49ab gpio: sysfs: fix gpio device-attribute leak
* 3d6b88b gpio: sysfs: fix gpio-chip device-attribute leak
* 72d8d4d gpio: fix sleep-while-atomic in gpiochip_remove
* 2bc26f4 gpio: fix memory leak and sleep-while-atomic
* e1c76d6 gpio: fix memory and reference leaks in gpiochip_add error path
* fe7930b gpio: crystalcove: use handle_nested_irq
* 0dc7c71 gpiolib: of: Correct error handling in of_get_named_gpiod_flags
* f32b586 pinctrl: lantiq: remove bogus of_gpio_chip_add
* d384560 ARM: dts: berlin: correct BG2Q's SM GPIO location.
* a96747d reset: sunxi: fix spinlock initialization
* e77b867 uas: Add US_FL_NO_ATA_1X for 2 more Seagate disk enclosures
* 03642fd uas: Add US_FL_NO_REPORT_OPCODES for JMicron JMS566 with usb-id 0bc2:a013
* 887934e uas: Add US_FL_NO_ATA_1X for Seagate devices with usb-id 0bc2:a013
* ee45552e mei: clean reset bit before reset
* 60ff540 NFSv4.1: Fix client id trunking on Linux
* a2a15f4 ftrace: Check both notrace and filter for old hash
* edc9d33 ftrace: Fix updating of filters for shared global_ops filters
* 7769f8b ftrace/jprobes/x86: Fix conflict between jprobes and function graph tracing
* 87a5d56 leds: netxbig: fix oops at probe time
* 76da8f9 drivers: net: cpsw: fix multicast flush in dual emac mode
* d8682e1 i40e: adds FCoE configure option
* 87a1898 iwlwifi: mvm: fix Rx with both chains
* 27f1650 arm64: partially revert "ARM: 8167/1: extend the reserved memory for initrd to be page aligned"
* 6a31593 mmc: sdhci: Set SDHCI_POWER_ON with external vmmc
* e247868 powernv: Fix OPAL tracepoint code
* d5471f8 locks: fix NULL-deref in generic_delete_lease
* 820b511 vfio-pci: Fix the check on pci device type in vfio_pci_probe()
* 24a209f vivid: fix CROP_BOUNDS typo for video output
* e6bd63e img-ir/hw: Fix potential deadlock stopping timer
* 7abbdc9 img-ir/hw: Always read data to clear buffer
* 73db430 uvcvideo: Fix destruction order in uvc_delete()
* 3971a1c sound: Update au0828 quirks table
* 5eb7814 sound: simplify au0828 quirk table
* 129d51a smiapp: Take mutex during PLL update in sensor initialisation
* 8d5d2e1 af9005: fix kernel panic on init if compiled without IR
* b5b7b72 smiapp-pll: Correct clock debug prints
* e5dcc09 video/fbdev: fix defio's fsync
* 7c73bd9 video/logo: prevent use of logos after they have been freed
* bf80baa x86/build: Clean auto-generated processor feature files
* 7e20e84 net: ethernet: cpsw: fix hangs with interrupts
* 143b34a storvsc: ring buffer failures may result in I/O freeze
* ac5a275 serial: fix parisc boot hang
* 5292595 parisc: fix out-of-register compiler error in ldcw inline assembler function
* 31b6929 dm: fix missed error code if .end_io isn't implemented by target_type
* 3b7dd6e bugon.cocci: fix Options at the macro
* f128480 ARM: dts: berlin: fix io clk and add missing core clk for BG2Q sdhci2 host
* 8f3922e clk: at91: keep slow clk enabled to prevent system hang
* cfde14b clk: berlin: bg2q: remove non-exist "smemc" gate clock
* 9408503 clk: rockchip: fix rk3066 pll lock bit location
* a195f75 clk: rockchip: fix rk3288 cpuclk core dividers
* f3067bf Revert "clk: ppc-corenet: Fix Section mismatch warning"
* fcdb6d6 clk: Don't try to use a struct clk* after it could have been freed
* e2481b6 clk: Really fix deadlock with mmap_sem
* e553baa clk: samsung: Fix double add of syscore ops after driver rebind
* f8db847 SCSI: fix regression in scsi_send_eh_cmnd()
* 7fbdd0e scsi: fix random memory corruption with scsi-mq + T10 PI
* 5f5628f scsi: blacklist RSOC for Microsoft iSCSI target devices
* f6637f8 Revert "[SCSI] mpt3sas: Remove phys on topology change"
* f3018e1 Revert "[SCSI] mpt2sas: Remove phys on topology change."
* 527400f Revert "drm/i915: Preserve VGACNTR bits from the BIOS"
* 5786521 iscsi,iser-target: Expose supported protection ops according to t10_pi
* 7737bb0 iser-target: Fix NULL dereference in SW mode DIF
* 80e47cd iser-target: Allocate PI contexts dynamically
* a536c94 iser-target: Fix implicit termination of connections
* b8444e9 iser-target: Handle ADDR_CHANGE event for listener cm_id
* 0105b02 iser-target: Fix connected_handler + teardown flow race
* 2413d95 iser-target: Parallelize CM connection establishment
* 425ec46 iser-target: Fix flush + disconnect completion handling
* 9881684 iscsi,iser-target: Initiate termination only once
* 2fc431d iscsi-target: Fail connection on short sendmsg writes
* a27d8a2 genirq: Prevent proc race against freeing of irq descriptors
* f7146ce IB/iser: Fix possible SQ overflow
* 1943a1a tcm_loop: Fix wrong I_T nexus association
* 937723c uapi/linux/target_core_user.h: fix headers_install.sh badness
* 97bb3ed tick/powerclamp: Remove tick_nohz_idle abuse
* 4514556 hp_accel: Add support for HP ZBook 15
* 37c8f27 asus-nb-wmi: Add another wapf=4 quirk
* 42e6206 rtlwifi: Fix error when accessing unmapped memory in skb
* 7d01c21 rtlwifi: rtl8192ce: Set fw_ready flag
* fff8244 cfg80211: Fix 160 MHz channels with 80+80 and 160 MHz drivers
* a7b2c7f cfg80211: avoid mem leak on driver hint set
* 0a57c26 cfg80211: don't WARN about two consecutive Country IE hint
* 65a39b3 nl80211: check matches array length before acessing it
* 7d277a0 xhci: Add broken-streams quirk for Fresco Logic FL1000G xhci controllers
* cb7ac02 xhci: Check if slot is already in default state before moving it there
* 00ba021 cxl: Unmap MMIO regions when detaching a context
* 3db65db cxl: Add timeout to process element commands
* d4a26d1 cxl: Change contexts_lock to a mutex to fix sleep while atomic bug
* 70819ea ARC: [nsimosci] move peripherals to match model to FPGA
* a754520 drm/irq: BUG_ON() -> WARN_ON()
* 00a80b7 drm/i915: Don't call intel_prepare_page_flip() multiple times on gen2-4
* bb0edc8 drm/i915: Disable PSMI sleep messages on all rings around context switches
* 3ea5944 drm/i915: Force the CS stall for invalidate flushes
* 1c61a71 drm/i915: Invalidate media caches on gen7
* 715f7c8 drm/nv4c/mc: disable msi
* 6ba4636 drm/i915: save/restore GMBUS freq across suspend/resume on gen4
* ddf6f9a drm/i915: resume MST after reading back hw state
* a5872ca drm/i915: Only warn the first time we attempt to mmio whilst suspended
* 06b7ae7 drm/i915: Disallow pin ioctl completely for kms drivers
* 0976457 drm/i915: Don't complain about stolen conflicts on gen3
* e8e547f drm/radeon: properly filter DP1.2 4k modes on non-DP1.2 hw
* 2710eb2 drm/radeon: adjust default bapm settings for KV
* ca01c8f drm/radeon: fix sad_count check for dce3
* 310a18b drm/radeon: KV has three PPLLs (v2)
* 65c48e0 drm/radeon: check the right ring in radeon_evict_flags()
* b29b3ee drm/radeon: work around a hw bug in MGCG on CIK
* 0d05214 drm/radeon: fix typo in CI dpm disable
* c3c1620 drm/dp-mst: Remove branches before dropping the reference
* 1cc635a drm/dp: retry AUX transactions 32 times (v1.1)
* f5f6dd6 drm/fb_helper: move deferred fb checking into restore mode (v2)
* 3308413 drm/ttm: Avoid memory allocation from shrinker functions.
* a869935 drm/vmwgfx: Fix fence event code
* ad2b9bb drm/vmwgfx: Fix error printout on signals pending
* 28c54a2 drm/vmwgfx: Don't use memory accounting for kernel-side fence objects
* 4c056b8 enic: fix rx skb checksum
* 58f2f9c team: avoid possible underflow of count_pending value for notify_peers and mcast_rejoin
* ff9df48 alx: fix alx_poll()
* 2aab953 xen-netback: fixing the propagation of the transmit shaper timeout
* 04e5427 tcp: Do not apply TSO segment limit to non-TSO packets
* f3721ea net/mlx4_core: Correcly update the mtt's offset in the MR re-reg flow
* 12d5e0b net: Generalize ndo_gso_check to ndo_features_check
* 3890e42 net/core: Handle csum for CHECKSUM_COMPLETE VXLAN forwarding
* 253ab52 net: Reset secmark when scrubbing packet
* 2986248 net: Fix stacked vlan offload features computation
* 060e283 tcp6: don't move IP6CB before xfrm6_policy_check()
* bfd6ab6 net/mlx4_en: Doorbell is byteswapped in Little Endian archs
* a67fa81 batman-adv: avoid NULL dereferences and fix if check
* 4a4867f batman-adv: Unify fragment size calculation
* 53fd27c batman-adv: Calculate extra tail size based on queued fragments
* ea1e9a3 tg3: tg3_disable_ints using uninitialized mailbox value to disable interrupts
* b7efdb6 in6: fix conflict with glibc
* 3614d56 net: drop the packet when fails to do software segmentation or header check
* 639e13d xen-netback: support frontends without feature-rx-notify again
* bce2a13 geneve: Fix races between socket add and release.
* 4378fe7 geneve: Remove socket and offload handlers at destruction.
* 3c030f1 netlink: Don't reorder loads/stores before marking mmap netlink frame as available
* b68d3ab netlink: Always copy on mmap TX.
* 15c1160 net/mlx4: Cache line CQE/EQE stride fixes
* feb15ac gre: fix the inner mac header in nbma tunnel xmit path
* 219b188 Linux 3.18.3
* f2f5d44 mm: Don't count the stack guard page towards RLIMIT_STACK
* c03aed6 mm: propagate error from stack expansion even for guard page
* 53bcf5c mm, vmscan: prevent kswapd livelock due to pfmemalloc-throttled process being killed
* a78e877 mm: protect set_page_dirty() from ongoing truncation
* d73437a exit: fix race between wait_consider_task() and wait_task_zombie()
* 0324896 mmc: sdhci: Fix sleep in atomic after inserting SD card
* 9abaccf regulator: s2mps11: Fix dw_mmc failure on Gear 2
* cc01e9c nouveau: bring back legacy mmap handler
* f4589f7 drm/nouveau/nouveau: Do not BUG_ON(!spin_is_locked()) on UP
* f34d67feb spi: sh-msiof: Add runtime PM lock in initializing
* e8ff149 perf session: Do not fail on processing out of order event
* 7f5dada perf/x86/uncore/hsw-ep: Handle systems with only two SBOXes
* 78a458e perf: Fix events installation during moving group
* 8fa60cc perf/x86/intel/uncore: Make sure only uncore events are collected
* a4a59e5 Revert "mac80211: Fix accounting of the tailroom-needed counter"
* 30e4fb8 Btrfs: don't delay inode ref updates during log replay
* 087e791 crypto: aesni - fix "by8" variant for 128 bit keys
* 553aeac crypto: sha-mb - Add avx2_supported check.
* 1a7227f arm64/efi: add missing call to early_ioremap_reset()
* 058ec24 arm64: kernel: fix __cpu_suspend mm switch on warm-boot
* 734e756 arm64: Move cpu_resume into the text section
* b0bb769 Input: alps - v7: fix finger counting for > 2 fingers on clickpads
* 7b35ab6 Input: alps - v7: sometimes a single touch is reported in mt[1]
* 98eb06b Input: alps - v7: ignore new packets
* 3dcf157 ACPI / PM: Fix PM initialization for devices that are not present
* de42aa3 ACPI / video: Add some Samsung models to disable_native_backlight list
* 9e80aeb rpc: fix xdr_truncate_encode to handle buffer ending on page boundary
* 713beaa Revert "ARM: 7830/1: delay: don't bother reporting bogomips in /proc/cpuinfo"
* 95a76bd ARM: OMAP4: PM: Only do static dependency configuration in omap4_init_static_deps
* b8775da ARM: dts: Enable PWM node by default for s3c64xx
* e3041d3 ARM: dts: DRA7: wdt: Fix compatible property for watchdog node
* 5573b63 ARM: defconfigs: use CONFIG_CPUFREQ_DT
* 20cb719 ARM: dts: am437x-sk-evm.dts: fix LCD timings
* 4e5a37c ARM: dts: am437x-sk: fix lcd enable pin mux data
* 170f69f sched: Add missing rcu protection to wake_up_all_idle_cpus
* f88708a sched/deadline: Avoid double-accounting in case of missed deadlines
* fbbd9c2 sched/deadline: Fix migration of SCHED_DEADLINE tasks
* 8b65e97 scripts/kernel-doc: don't eat struct members with __aligned
* 83d1782 nilfs2: fix the nilfs_iget() vs. nilfs_new_inode() races
* 53575aa5 mtd: nand: omap: Fix NAND enumeration on 3430 LDP
* d019b46 MTD: m25p80: fix inconsistency in m25p_ids compared to spi_nor_ids
* 8513071 mtd: tests: abort torturetest on erase errors
* d5f902a ceph: do_sync is never initialized
* 7e79126 ACPI / video: update the skip case for acpi_video_device_in_dod()
* bff467f nfsd: fix fi_delegees leak when fi_had_conflict returns true
* 7599f17 nfsd4: fix xdr4 count of server in fs_location4
* 6a4edf5 nfsd4: fix xdr4 inclusion of escaped char
* fb0a855 fs: nfsd: Fix signedness bug in compare_blob
* cb64628 Drivers: hv: util: make struct hv_do_fcopy match Hyper-V host messages
* ae4b4f1 Drivers: hv: vmbus: Fix a race condition when unregistering a device
* 3db4308 n_tty: Fix read_buf race condition, increment read_head after pushing data
* 66a2cbe reiserfs: destroy allocated commit workqueue
* 45f5afb xtensa: fix kmap_prot definition
* 69db263 serial: samsung: wait for transfer completion before clock disable
* 0fd0e78 tty: serial: men_z135_uart: Add terminating entry for men_z135_ids
* 2ce1eeb tracing/sched: Check preempt_count() for current when reading task->state
* 02a59e2 writeback: fix a subtle race condition in I_DIRTY clearing
* 7bde172 drbd: Fix state change in case of connection timeout
* af86a8a drbd: merge_bvec_fn: properly remap bvm->bi_bdev
* f1a6540 cdc-acm: memory leak in error case
* ee9b142 genhd: check for int overflow in disk_expand_part_tbl()
* 5986bc8 Add USB_EHCI_EXYNOS to multi_v7_defconfig
* d58e913 USB: qcserial: Add support for HP lt4112 LTE/HSPA+ Gobi 4G Modem
* e6e9495 usb: gadget: at91_udc: move prepare clk into process context
* e2eb980 usb: renesas_usbhs: gadget: fix NULL pointer dereference in ep_disable()
* 1a199fe USB: cdc-acm: check for valid interfaces
* 7e73b00 md/raid5: fetch_block must fetch all the blocks handle_stripe_dirtying wants.
* b51e392 ALSA: hda - Add new GPU codec ID 0x10de0072 to snd-hda
* d7e73a7 ALSA: hda - Fix wrong gpio_dir & gpio_mask hint setups for IDT/STAC codecs
* 046a9bf ALSA: snd-usb-caiaq: fix stream count check
* 9e31ed5 ALSA: fireworks: fix an endianness bug for transaction length
* 61654b8 ALSA: hda - using uninitialized data
* 721b64b ALSA: hda/realtek - Add new Dell desktop for ALC3234 headset mode
* 4c95046 ALSA: hda/realtek - New codec support for ALC256
* a8302062 ALSA: hda/realtek - New codec support for ALC298
* 6c300cb1 ALSA: usb-audio: extend KEF X300A FU 10 tweak to Arcam rPAC
* 989eae7 i2c: designware: Fix falling time bindings doc
* c444aea i8k: Add support for Dell Latitude E6440
* 1a5773a misc: genwqe: check for error from get_user_pages_fast()
* 27be783 driver core: Fix unbalanced device reference in drivers_probe
* ccf8296 x86, vdso: Use asm volatile in __getcpu
* ef44baf x86_64, vdso: Fix the vdso address randomization algorithm
* 032e45d kvm: x86: drop severity of "generation wraparound" message
* cec145a KVM: s390: Fix ipte locking
* 31408f1 KVM: s390: flush CPU on load control
* c3e724b KVM: s390: Fix size of monitor-class number field
* d3105d5 kvm: x86: mask out XSAVES
* 09e365b KVM: x86: em_ret_far overrides cpl
* c4a5254 KVM: x86: support XSAVES usage in the host
* 1f92632 x86: export get_xsave_addr
* 1cafdf5 HID: Add a new id 0x501a for Genius MousePen i608X
* 4fe49b1 HID: add battery quirk for USB_DEVICE_ID_APPLE_ALU_WIRELESS_2011_ISO keyboard
* e0c4b58 HID: i2c-hid: Do not free buffers in i2c_hid_stop()
* 8ccb93d HID: roccat: potential out of bounds in pyra_sysfs_write_settings()
* e788b6d HID: i2c-hid: prevent buffer overflow in early IRQ
* db8bf51 HID: i2c-hid: fix race condition reading reports
* 8bb664f HID: wacom: fix freeze on open when autosuspend is on
* 15c1c0a HID: wacom: re-add accidentally dropped Lenovo PID
* 7e4cec4 HID: yet another buggy ELAN touchscreen
* fa5e474 blk-mq: Fix uninitialized kobject at CPU hotplugging
* 3a6d400 blk-mq: Fix a race between bt_clear_tag() and bt_get()
* d04e14a blk-mq: Avoid that __bt_get_word() wraps multiple times
* b041392 blk-mq: Fix a use-after-free
* 00de3a6 blk-mq: use 'nr_cpu_ids' as highest CPU ID count for hwq <-> cpu map
* 8c6aa9c iommu/vt-d: Fix dmar_domain leak in iommu_attach_device
* e7a4ae8 iommu/vt-d: Fix an off-by-one bug in __domain_mapping()
* 49b9926 UBI: Fix double free after do_sync_erase()
* 85ce61f UBI: Fix invalid vfree()
* c7ba2d7 pstore-ram: Allow optional mapping with pgprot_noncached
* dedfc0e pstore-ram: Fix hangs by using write-combine mappings
* f2b80ae brcmfmac: Fix ifidx for rx data by msgbuf.
* efdb9b9 PCI: Restore detection of read-only BARs
* 2b81cff Bluetooth: Fix accepting connections when not using mgmt
* ad976d1 Bluetooth: Fix controller configuration with HCI_QUIRK_INVALID_BDADDR
* 0de8cd6 Bluetooth: Clear LE white list when resetting controller
* 1836823 Bluetooth: Fix check for direct advertising
* f3d02a6 Bluetooth: Fix LE connection timeout deadlock
* bff7d3f Bluetooth: 6lowpan: fix skb_unshare behaviour
* 767d883 Bluetooth: ath3k: Add support of MCI 13d3:3408 bt device
* ad23351 powerpc: add little endian flag to syscall_get_arch()
* 5c7308f powerpc/perf/hv-24x7: Use per-cpu page buffer
* 27f1f15 powerpc/powernv: Switch off MMU before entering nap/sleep/rvwinkle mode
* 6a7c1a4 powerpc/book3s: Fix partial invalidation of TLBs in MCE code.
* 4b43ad9 powerpc: Fix bad NULL pointer check in udbg_uart_getc_poll()
* a7c3ff2 ktest: Fix make_min_config to handle new assign_configs call
* 3b4a99e ASoC: dwc: Ensure FIFOs are flushed to prevent channel swap
* e41e3bb ASoC: pcm512x: Trigger auto-increment of register addresses on i2c
* c50176d ASoC: tlv320aic31xx: Fix off by one error in the loop stucture.
* 877fd33 ASoC: max98090: Fix ill-defined sidetone route
* bc87f9e ASoC: sigmadsp: Refuse to load firmware files with a non-supported version
* d4527a1 ASoC: eukrea-tlv320: Fix of_node_put() call with uninitialized object
* 26487e2 ath5k: fix hardware queue index assignment
* fd6fc29 iwlwifi: add new device IDs for 3165
* 3ce710b iwlwifi: mvm: update values for Smart Fifo
* e7fd25d iwlwifi: dvm: fix flush support for old firmware
* 2129c43 swiotlb-xen: pass dev_addr to swiotlb_tbl_unmap_single
* 2a8ba64 swiotlb-xen: call xen_dma_sync_single_for_device when appropriate
* e725243 swiotlb-xen: remove BUG_ON in xen_bus_to_phys
* 46b29c3 swiotlb-xen: pass dev_addr to xen_dma_unmap_page and xen_dma_sync_single_for_cpu
* 7bb9bcd can: peak_usb: fix memset() usage
* 2eecaeb can: peak_usb: fix cleanup sequence order in case of error during init
* 0d3b349 ath9k: fix BE/BK queue order
* 4ad54f0 ath9k_hw: fix hardware queue allocation
* 234b25a ocfs2: fix the wrong directory passed to ocfs2_lookup_ino_from_name() when link file
* 8f0613e ocfs2: fix journal commit deadlock
* c75b302 drivers/rtc/rtc-isl12057.c: fix masking of register values
* e376bf2 rtc: omap: fix missing wakealarm attribute
* 8b31123 rtc: omap: fix clock-source configuration
* 7d9c386 drivers/rtc/rtc-sirfsoc.c: move hardware initilization earlier in probe
* e609d3f Linux 3.18.2
* 3c6babf Btrfs: fix fs corruption on transaction abort if device supports discard
* 9d15399 Btrfs: make sure logged extents complete in the current transaction V3
* 115f914 Btrfs: do not move em to modified list when unpinning
* 37ea7a1 btrfs: fix wrong accounting of raid1 data profile in statfs
* d77fe80 Btrfs: make sure we wait on logged extents when fsycning two subvols
* d7fad54 eCryptfs: Remove buggy and unnecessary write in file name decode routine
* bbeb37e eCryptfs: Force RO mount when encrypted view is enabled
* 41ba2ab udf: Check component length before reading it
* 53fbe4c udf: Verify symlink size before loading it
* a6a4afa udf: Verify i_size when loading inode
* 1a927fa udf: Check path length when reading symlink
* 9cc010c exit: pidns: alloc_pid() leaks pid_namespace if child_reaper is exiting
* 2f4f9b9 mm/CMA: fix boot regression due to physical address of high_memory
* 522a816 ncpfs: return proper error from NCP_IOC_SETROOT ioctl
* fa06c84 crypto: af_alg - fix backlog handling
* 3d7c0c1 audit: restore AUDIT_LOGINUID unset ABI
* dbe0ca0 audit: don't attempt to lookup PIDs when changing PID filtering audit rules
* 1110f35 audit: use supplied gfp_mask from audit_buffer in kauditd_send_multicast_skb
* b95660c userns: Unbreak the unprivileged remount tests
* 57f8552 userns: Allow setting gid_maps without privilege when setgroups is disabled
* 4a7215f userns: Add a knob to disable setgroups on a per user namespace basis
* 54b8ced userns: Rename id_map_mutex to userns_state_mutex
* 39d3003 userns: Only allow the creator of the userns unprivileged mappings
* 335f060 userns: Check euid no fsuid when establishing an unprivileged uid mapping
* b9b97d5 userns: Don't allow unprivileged creation of gid mappings
* d5c3ebc userns: Don't allow setgroups until a gid mapping has been setablished
* d9a7591 userns: Document what the invariant required for safe unprivileged mappings.
* e726c9a groups: Consolidate the setgroups permission checks
* 462c8c0 umount: Disallow unprivileged mount force
* fa0bad3 mnt: Update unprivileged remount test
* 80d4d83 mnt: Implicitly add MNT_NODEV on remount when it was implicitly added by mount
* 16811f0 thermal: Fix error path in thermal_init()
* 877c27d mnt: Fix a memory stomp in umount
* 9e2a8e6 mac80211: free management frame keys when removing station
* 4286afc mac80211: fix multicast LED blinking and counter
* 83a67ff mac80211: avoid using uninitialized stack data
* 0a6626a mac80211: copy chandef from AP vif to VLANs
* a481fd1 KEYS: Fix stale key registration at error path
* f3d4175 x86/microcode/intel: Fish out the stashed microcode for the BSP
* d239198 x86, microcode: Reload microcode on resume
* 44c4db3 x86, microcode: Don't initialize microcode code on paravirt
* 97d0906 x86, microcode, intel: Drop unused parameter
* 6a76bc2 x86, microcode, AMD: Do not use smp_processor_id() in preemtible context
* 9c0f826 isofs: Fix unchecked printing of ER records
* 743fce2 x86/tls: Don't validate lm in set_thread_area() after all
* afe83db x86/asm/traps: Disable tracing and kprobes in fixup_bad_iret and sync_regs
* 8f8c0ad ARM: mvebu: fix ordering in Armada 370 .dtsi
* 6e9c89c ARM: mvebu: remove conflicting muxing on Armada 370 DB
* a35da78 ARM: mvebu: disable I/O coherency on non-SMP situations on Armada 370/375/38x/XP
* 57aefed ARM: mvebu: make the coherency_ll.S functions work with no coherency fabric
* 9658243 ARM: tegra: Re-add removed SoC id macro to tegra_resume()
* 3faf430 drm/tegra: gem: dumb: pitch and size are outputs
* f324cda arm64: bpf: lift restriction on last instruction
* 516e433 arm64: Add COMPAT_HWCAP_LPAE
* ffcc89d dm thin: fix a race in thin_dtr
* 2409f51 dm thin: fix missing out-of-data-space to write mode transition if blocks are released
* 52259b6 dm thin: fix inability to discard blocks when in out-of-data-space mode
* 5226f88 dm space map metadata: fix sm_bootstrap_get_nr_blocks()
* 734a3fb dm cache: fix spurious cell_defer when dealing with partial block at end of device
* 7a9cdc4 dm cache: dirty flag was mistakenly being cleared when promoting via overwrite
* 4df99e3 dm cache: only use overwrite optimisation for promotion when in writeback mode
* 6425e7b dm crypt: use memzero_explicit for on-stack buffer
* 3c737ac dm bufio: fix memleak when using a dm_buffer's inline bio
* 6fac18d dcache: fix kmemcheck warning in switch_names
* a8897f2 nfs41: fix nfs4_proc_layoutget error handling
* 243cc95 f2fs: fix possible data corruption in f2fs_write_begin()
* 8744de7 f2fs: avoid returning uninitialized value to userspace from f2fs_trim_fs()
* 83b12ed scsi: correct return values for .eh_abort_handler implementations
* 2e36a01 regulator: anatop: Set default voltage selector for vddpu
* 9d91d6e megaraid_sas: dndinaness related bug fixes
* 803bb7e megaraid_sas: corrected return of wait_event from abort frame path
* 1c45bf43 mmc: sdhci-pci-o2micro: Fix Dell E5440 issue
* bc70ec2 mmc: block: add newline to sysfs display of force_ro
* 8d5112b mmc: omap_hsmmc: Fix UHS card with DDR50 support
* 31b5495 mmc: dw_mmc: avoid write to CDTHRCTL on older versions
* 39a6759 mfd: tc6393xb: Fail ohci suspend if full state restore is required
* ff1589b mfd: twl4030-power: Fix regression with missing compatible flag
* 82c236b clocksource: arch_timer: Fix code to use physical timers when requested
* 0fb5df0 brcmfmac: Fix bitmap malloc bug in msgbuf.
* ead468d x86, kvm: Clear paravirt_enabled on KVM guests for espfix32's benefit
* a1f3f3d x86_64, switch_to(): Load TLS descriptors before switching DS and ES
* 7cc556d x86/tls: Disallow unusual TLS segments
* b9372b8 x86/tls: Validate TLS entries to protect espfix
* b6d20ed isofs: Fix infinite looping over CE entries
* 39ca484 Linux 3.18.1
* 72e9a6c ALSA: usb-audio: Don't resubmit pending URBs at MIDI error recovery
* bf5f983 ALSA: hda - Fix built-in mic at resume on Lenovo Ideapad S210
* a12df59 ALSA: hda - Add EAPD fixup for ASUS Z99He laptop
* 6c1fbff deal with deadlock in d_walk()
* 679829c move d_rcu from overlapping d_child to overlapping d_alias
* 3fd3a62 rtlwifi: rtl8192ce: Fix missing interrupt ready flag
* 9cd1d3e rtlwifi: rtl8192ce: Fix kernel crashes due to missing callback entry
* 9297b37 rtlwifi: rtl8192ce: Fix editing error that causes silent memory corruption
* 4b1c83d netlink: use jhash as hashfn for rhashtable
* 01da9f8 net: fix suspicious rcu_dereference_check in net/sched/sch_fq_codel.c
* 21ac2de xen-netfront: use correct linear area after linearizing an skb
* 7efe8f1 tcp: fix more NULL deref after prequeue changes
* ab12ec4 net: sctp: use MAX_HEADER for headroom reserve in output path
* e7b7e0c2 net: mvneta: fix race condition in mvneta_tx()
* 9823d71 net: mvneta: fix Tx interrupt delay
* 6c2f1fe mips: bpf: Fix broken BPF_MOD
* 3e496d4 openvswitch: Fix flow mask validation.
* 435dcf6 gre: Set inner mac header in gro complete
* 8407165 Fix race condition between vxlan_sock_add and vxlan_sock_release
* b2776bf Linux 3.18

