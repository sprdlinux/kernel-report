* 5fa57fc usb: gadget: f_audio_source:replace deprecated API
* b703e35 net: ipv6: fix build failure if IPV6_ROUTE_INFO config is enabled
* 2102d8d sync: Fix memory corruption in sync_timeline_signal().
* 018490d xt_qtaguid: use sock_gen_put() instead of xt_socket_put_sk()
* 1958359 android: base-cfg: disable ALARM_DEV
* ecb9f50 staging: Remove logger and alarm-dev from android Makefile
* a884fbb staging: Remove the Android alarm-dev driver
* 89a5706 staging: Remove the Android logger driver
* 3a3804b clk: debugfs: Support frequency stats accounting
* deb1413 fixup! proc: make oom adjustment files user read-only
* 1ba6b2f proc: make oom adjustment files user read-only
* 6f9f6c4 Revert "Grants system server access to /proc/<pid>/oom_adj for Android applications."
* 9598442 power: Remove HAS_WAKELOCK config and document WAKELOCK
* b9bdea5 input: evdev: fix double free in evdev_release
* 2939146 android: base-cfg: turn off /dev/mem and /dev/kmem
* 5425728 seccomp: arm64: Fix compile time errors
* cf9e868 android: base-cfg: enable ARMV8_DEPRECATED and subfeatures
* 02710a9 arm64: kconfig: move emulation option under kernel features
* 7540dad arm64: Emulate SETEND for AArch32 tasks
* 68b703b arm64: Consolidate hotplug notifier for instruction emulation
* d11d7e5 arm64: Track system support for mixed endian EL0
* 93f2230 arm64: Fix up /proc/cpuinfo
* c5650ea arm64: fix return code check when changing emulation handler
* 203077a arm64: Trace emulation of AArch32 legacy instructions
* cbefb97 arm64: Emulate CP15 Barrier instructions
* f2e97ae arm64: Port SWP/SWPB emulation support from arm
* ab12a80 arm64: Add framework for legacy instruction emulation
* f02f9ac arm64: Add AArch32 instruction set condition code checks
* fe5bff0 arm64: Add support for hooks to handle undefined instructions
* b27413f Revert "arm64: copy conditional instruction tests from arm"
* 9e7934b Revert "arm64: ptrace: add is_wide_instruction() macro"
* 6e81856 Revert "arm64: add undefined instruction handler hooks"
* 170bb23 Revert "arm64: kernel: check mode for get_user in undefinstr"
* bf1902c Revert "arm64: a backwards compatible config option"
* 7341ee6 Revert "arm64: emulate the swp/swpb instruction"
* 0f41c62 Revert "arm64: fix a warning and a typo in SWP emulation"
* 0abe600 Revert "arm64: add fault handling to SWP emulation"
* b5f5ddc Revert "arm64: fix SWP instruction emulation"
* 32777fa Revert "arm64: optionally set CP15BEN in SCTLR"
* b91b580 Revert "arm64: make SCTLR compat config depend on CONFIG_ARMV7_COMPAT"
* 4ddb001 Revert "arm64: enable deprecated SETEND instruction in SCTLR compat config"
* 843f764 Revert "arm64: cpuinfo: ARMv7 compatable cpuinfo option"
* b3458b3 Revert "arm64: report vfpv3 instead of vfpv3d16"
* a359d37 Revert "arm64: restrict effects of ARMV7_COMPAT_CPUINFO to ARMv7 tasks"
* 424fc12 Revert "android: base-cfg: enable ARMV7_COMPAT"
* 2789aba kbuild: make it possible to specify the module output dir
* 2a76853 xt_qtaguid: Use sk_callback_lock read locks before reading sk->sk_socket
* 80ee94e xt_qtaguid: fix broken uid/gid range check
* 2f56ebc usb: gadget: check for accessory device before disconnecting HIDs
* 5542e34 staging: android: ashmem: add missing include
* e768e79 usb: gadget: android: Save/restore ep0 completion function
* f3ebc8d usb: u_ether: Fix compile errors
* bb2a9e7 usb: gadget: Add Uevent to notify userspace
* a45cf2d usb: gadget: configfs: Add usb_function ptr to fi struct
* 60ad761 selinux:  Remove obsolete selinux_audit_data initialization.
* ea8ccc9 usb: gadget: mtp/ptp: Migrate functions to the USB_FUNCTION interface
* 96f8bcf pstore: selinux: add security in-core xattr support for pstore and debugfs
* d9aff13 pstore: add pmsg
* d336da2 pstore: handle zero-sized prz in series
* 242e607 pstore: remove superfluous memory size check
* 0fb7895 pstore: use scnprintf
* cc310c6 prctl: make PR_SET_TIMERSLACK_PID pid namespace aware
* a8fe56b prctl: fix misplaced PR_SET_TIMERSLACK_PID case
* 9f6cbc0 Make suspend abort reason logging depend on CONFIG_PM_SLEEP
* cbc1628 power: Add check_wakeup_reason() to verify wakeup source irq
* 722c110 power: Adds functionality to log the last suspend abort reason.
* a4515fc prctl: adds the capable(CAP_SYS_NICE) check to PR_SET_TIMERSLACK_PID.
* 017b518 prctl: adds PR_SET_TIMERSLACK_PID for setting timer slack of an arbitrary thread.
* 53b5e2f cgroup: Add generic cgroup subsystem permission checks
* 63351df Fix compile errors in accordance with changes from 3.14 to 3.18
* 3d3c5e9 Revert "ARM: Blacklist GCC 4.8.0 to GCC 4.8.2 - PR58854"
* e2a0412 net: support marking accepting TCP sockets
* ba3d8d3 net: core: Support UID-based routing.
* d631512 add seccomp syscall for compat task
* 501a08a cpufreq: stats: hold reference on global cpufreq
* a7f9ba3 wlan: Add get_wake_irq functionality
* 134e3e0 include: linux: cgroup: Fix compiler warning
* ec390ea video: adf: fix wrong bitops in adf_modeinfo_to_fb_videomode()
* 440dd72 cpufreq: interactive: only boost tunable affected cpus
* 4461760 net: ipv6: allow choosing optimistic addresses with use_optimistic
* fbc48224 cpufreq: interactive: don't skip waking up speedchange_task if target_freq > policy->cur
* a11623d arch: arm64: force -fno-pic
* 92ee040 staging: binder: Change binder mutex to rtmutex.
* 701112f memcg: add permission check
* 1647425 cgroup: refactor allow_attach function into common code
* 3cf53d8 net: ipv6: Add a sysctl to make optimistic addresses useful candidates
* a8e63b3 cpufreq: Avoid using global variable total_cpus
* 5bc08b2 power: Avoids bogus error messages for the suspend aborts.
* 923b5e2 arm64: add seccomp support
* 17fa577 arm64: add SIGSYS siginfo for compat task
* f3db62e asm-generic: add generic seccomp.h for secure computing mode 1
* f459f3d arm64: ptrace: allow tracer to skip a system call
* 945fb68 arm64: ptrace: add PTRACE_SET_SYSCALL
* a77185d USB: f_rndis: fix compile error
* e773897 USB: gadget: rndis: Add module parameter for DL max packets per xfer
* 0e8b24f ndis: Add debug support to disable RNDIS Multipacket Feature
* e298eec RNDIS: Add Data aggregation (multi packet) support
* 3c96d69 USB: gadget: u_ether: Fix data stall issue in RNDIS tethering mode
* cc0be22 usb: gadget: prevent change of Host MAC address of 'usb0' interface
* 25c9b92 usb: u_ether: Add workqueue as bottom half handler for rx data path
* fa70b2a android: base-cfg: enable ARMV7_COMPAT
* ad5ad9e arm64: restrict effects of ARMV7_COMPAT_CPUINFO to ARMv7 tasks
* 15f481c arm64: report vfpv3 instead of vfpv3d16
* 6cd119d arm64: cpuinfo: ARMv7 compatable cpuinfo option
* d19e0cf arm64: enable deprecated SETEND instruction in SCTLR compat config
* 7d48015 arm64: make SCTLR compat config depend on CONFIG_ARMV7_COMPAT
* 2ec6f25 arm64: optionally set CP15BEN in SCTLR
* 569ffcc arm64: fix SWP instruction emulation
* 4bdf4d3 arm64: add fault handling to SWP emulation
* 2ef02d4 arm64: fix a warning and a typo in SWP emulation
* 43f5334 arm64: emulate the swp/swpb instruction
* b028141 arm64: a backwards compatible config option
* 2bbb3c1 arm64: kernel: check mode for get_user in undefinstr
* f0bb4ad arm64: add undefined instruction handler hooks
* 6fdf4dc arm64: ptrace: add is_wide_instruction() macro
* 995c13f arm64: copy conditional instruction tests from arm
* 2a59e96 arm64: process: dump memory around registers when displaying regs
* bd7f859 cpufreq: interactive: make common_tunables static
* 957224b android: base-cfg: enforce the needed XFRM_MODE_TUNNEL (for VPN)
* 408a31cb arm64: check for upper PAGE_SHIFT bits in pfn_valid()
* 9025d68 cpu: add generic support for CPU feature based module autoloading
* 83d452a cpufreq: fix sleeping in atomic context when realloc freq_table for all_time_in_state
* 7502d79 cpufreq: Persist cpufreq time in state data across hotplug
* c5ecbca usb: Add support for rndis uplink aggregation
* 06e9c64 Add flags parameter to get_country_code template
* 174e565 mm: fix prctl_set_vma_anon_name
* 34c2b57 USB: rndis: Free the rndis response queue during REMOTE_NDIS_RESET_MSG
* e67ea60 firmware loader: fix pending_fw_head list corruption
* 3fdffbe firmware: Avoid deadlock of usermodehelper lock at shutdown
* 4bd2ceb staging: android: ashmem: Avoid deadlock with mmap/shrink
* 9980b92 ext4: Add support for FIDTRIM, a best-effort ioctl for deep discard trim
* dabbfc9 usb: gadget: f_audio_source: Fixed USB Audio Class Interface Descriptor
* e46ad82 usb: gadget: f_audio_source: change max ISO packet size
* 95d843a video: adf: Cleanup sw_sync timeline at adf_device_destroy
* 732ae14 HID: steelseries: validate output report details
* 19c82ec usb: gadget: f_accessory: Enabled Zero Length Packet (ZLP) for acc_write
* c43c190 input: Made keyreset more robust
* 1eb355d SELinux: Enable setting security contexts on rootfs inodes.
* 21bf695 net: wireless: Increase scan entry expiration to fit new scan time
* 52486d5 power: Add property CHARGE_COUNTER_EXT and 64-bit precision properties
* fe22fe0 cpufreq: interactive: prevents the frequency to directly raise above the hispeed_freq from a lower frequency.
* 9985a18 netfilter: fix seq_printf type mismatch warning
* 8adb162 arm64: Fix correct dtb clean-files location
* 1115e79 android: base-cfg: disable LOGGER
* 116806e net: Use fwmark reflection in PMTU discovery.
* 63003d5 net: ipv6: autoconf routes into per-device tables
* 5ee56ca input: Changed keyreset to act as a wrapper for keycombo.
* aa703c2 input: add keycombo, a general key combo driver.
* 12a3346 fiq_debugger: Add fiq_watchdog_triggered api
* e8365a3 pstore/ram: Add ramoops_console_write_buf api
* 73cdbd6 fiq_debugger: Call fiq_debugger_printf through a function pointer from cpu specific code
* 138525a video: adf: fbdev: add stubs for kernels without ADF_FBDEV
* d2f2a67 video: adf: memblock: map buffer for dma
* b92003e Power: Changes the permission to read only for sysfs file /sys/kernel/wakeup_reasons/last_resume_reason
* 456beea nf: Remove compilation error caused by e8430cbed3ef15fdb1ac26cfd020e010aa5f1c35
* e05ce93 video: adf: use rb_erase in adf_obj_destroy.
* 44100a6 nf: IDLETIMER: time-stamp and suspend/resume handling.
* 9e23e2a of: fix CONFIG_CMDLINE_EXTEND
* e139164 fiq_debugger: add ARM64 support
* 3764f68 fiq_debugger: split arm support into fiq_debugger_arm.c
* be8534f fiq_debugger: use pt_regs for registers
* 2b2a677 fiq_debugger: allow compiling without CONFIG_FIQ_GLUE
* a2f8613 fiq_debugger: rename debug->fiq_debugger
* 2a2f434 fiq_debugger: move into drivers/staging/android/fiq_debugger/
* 52bb695 cpufreq: interactive: remove compilation error from commit 49cc72365fb7ee87762a7ccc6a32ef68627216c5
* b122ae0 cpufreq: interactive: turn boost_pulse off on boost off
* 1e1dbb23 cpufreq: interactive: restructure CPUFREQ_GOV_LIMITS
* 3e4354d video: adf: adf_memblock_export symbol should be exported
* f277492 video: adf: add buffer padding quirk
* abc738a video: adf: document adf_format_validate_yuv's origin
* 58e1706 ARM64: copy CONFIG_CMDLINE_EXTEND from ARM
* be745aa of: Support CONFIG_CMDLINE_EXTEND config option
* 231f5b9 video: adf: ensure consistent alignment on userspace facing structs
* f6d3f13 video: adf: replace fbdev helper's open flag with refcount
* 082d89f ARM64: add option to build Image.gz/dtb combo
* e09b94b xt_qtaguid: Fix boot panic
* e0bffd5 netfilter: Build fixups - kuid/kguid changes & xt_socket_get/put_sk
* f6dc942 net: kuid/kguid build fixes
* 0ac99d5 cpufreq: interactive: hold reference on global cpufreq kobject if needed
* ca84dab Linux 3.14
* 1faf754 cpufreq: interactive: Use generic get_cpu_idle_time() from cpufreq.c
* 54393d1 video: adf: export the adf_attachment_allow symbol to modules.
* 70d8b60 power: wakeup_reason: rename irq_count to irqcount
* bae9fa3 Power: Add guard condition for maximum wakeup reasons
* 6754df8 android: base-cfg: enable DM_VERITY (used for secureboot)
* a333311 drivers: usb: gadget: 64-bit related type fixes
* d4b98f8 netfilter: xt_qtaguid: 64-bit warning fixes
* 9b98710 Staging: android: binder: More offset validation.
* 137ef7e POWER: fix compile warnings in log_wakeup_reason
* 582c3df Power: add an API to log wakeup reasons
* 4bb4055 android: configs: add systrace support to recommended configs
* c674ed8 video: adf: use %zu when printing size_t
* 0d89057 video: adf: fix compat ioctls calling ioctl with wrong cmd
* bd2fc65 video: adf: use ADF_IOCTL_TYPE in compat ioctl definitions
* 000c2ef fix false disconnect due to a signal sent to the reading process
* fac8460 tcp: add a sysctl to config the tcp_default_init_rwnd
* 33919bf netfilter: xt_IDLETIMER: Revert to retain the kernel API format.
* 52d5ab8 android: configs: update 3.10 options
* 68dc2b2 android: configs: Add CONFIG_NETFILTER_XT_TARGET_IDLETIMER
* 4aa678d cpufreq: interactive: fix NULL pointer dereference at sysfs ops
* f7e4bbf video: adf: define constants for device-custom ioctls
* fb75488 android: configs: add IPV6 ROUTE INFO
* ebd34f4 cpufreq: interactive: fix compiling warnings
* 15e2d47 android: configs: add TIMER_STATS back, helps with sysrq t.
* 96cb730 android: configs: Add HIDRAW to recommended set
* 3ec67d6 android: configs: require TCPMSS, remove SCHED_TRACER and TIMER_STATS
* e07d6ba android: configs: Reorder config fragments, update README
* 43bb66b ARM: fiq_glue: Add custom fiq return handler api.
* 9e17c5b netfilter: xt_qtaguid: fix memory leak in seq_file handlers
* 345fdfc video: adf: fix fbdev blank -> dpms state mapping
* 05d422c video: adf: validate dpms state passed to blank
* 84f8d61 video: adf: fix ADF_MAX_ATTACHMENTS declaration
* d7fcd8a video: adf: remove PAGE_SIZE from userspace-facing header
* 182ac05 video: adf: make device node names less hierarchical
* 7f865d1 ARM: Fix "Make low-level printk work" to use a separate config option
* 8dfddd3 ARM: Fix dtb list when DTB_IMAGE_NAMES is empty
* 529b597 net: move PPPoLAC and PPPoPNS headers to uapi
* 3d8e37a usb: gadget: f_accessory: move userspace interface to uapi
* 3c01be96 usb: gadget: f_mtp: move userspace interface to uapi
* d2615e7 input: misc: keychord: move header to uapi
* a0f2505 drivers: switch: remove S_IWUSR from dev_attr
* 1c75f08 usb: gadget: android: Remove device if probe fails
* 44b7128 video: adf: expose adf_modeinfo_set_{name,vrefresh} to drivers
* 97f49d0 video: adf: set default interface dpms_state to OFF
* 909b572 video: adf: make dpms_state sysfs attribute writable
* 6fc901f video: adf: add helpers for validating custom formats
* 0e10934 cpufreq: interactive: delete timers for GOV_START
* 0276747 cpufreq: Interactive: Implement per policy instances of governor
* 240fa8c cpufreq: interactive: Move definition of cpufreq_gov_interactive downwards
* 0c5b507 cpufreq: interactive: Remove unnecessary cpu_online() check
* 3cc6b90 video: adf: add informational flags to interfaces
* d8a902a video: adf: add fbdev compatibility helper
* f4cc9c0 video: adf: add supported formats to adf_overlay_engine_data
* 46a5cfb video: adf: support "simple" buffers
* edea5a7 video: adf: add memblock helper
* f3fc3d7 video: add atomic display framework
* 79c1931 USB: remove duplicate out endpoint creation in MTP mode
* 674607d cpufreq: interactive: fix show_target_loads and show_above_hispeed_delay
* 964e307 mm: add a field to store names for private anonymous memory
* 916e182 power_supply: kill android-battery driver
* d33f66d add extra free kbytes tunable
* fa56598 ARM: kgdb: ignore breakpoint instructions from user mode
* 9f8d0b5 netfilter: xt_qtaguid: 3.10 fixes
* 5e31262 misc: uidstat: Remove use of obsolete create_proc_read_entry api
* 9a4389e netfilter: xt_quota2: 3.10 fixes.
* dbd113e net: activity_stats: Stop using obsolete create_proc_read_entry api
* 3bbbc0b pstore: Update Documentation/android.txt
* e213ad0 mmc: core: Remove stray CONFIG_EXPERIMENTAL dependencies
* 111bba7 selinux: binder: Fix COMMON_AUDIT_DATA_INIT compile issue
* 816a0d9 netfilter: xt_qtaguid: fix bad tcp_time_wait sock handling
* 1c9fcf4 usb: gadget: android: 3.10 fixes
* bba071b usb: gadget: android: move init to late_initcall for now
* cb6f699 usb: gadget: android: Fixes and hacks to make android usb gadget compile on 3.9
* 1c545be usb: gadget: Fix android gadget driver build
* 2896b29 HACK: usb: gadget: Fix enumeration on boot
* a78ae7a usb: gadget: android: Fixes and hacks to make android usb gadget compile on 3.8
* c7ce15a ARM: decompressor: Flush tlb before swiching domain 0 to client mode
* 627bad8 mmc: block: Remove call to mmc_blk_set_blksize
* c2e4747 ARM: fiq_debugger: Update tty code for 3.9
* 74fe9a5 ARM: fiq_debugger: Use kmsg_dumper to dump kernel logs
* d2f3196 ARM: fiq_debugger: Fix to compile on 3.7
* bdcd44a usb: otg: otg-wakelock: Fix build for 3.7
* c69c747 cpufreq: interactive: resched timer if max freq raised
* 1ca94b1 cpufreq: interactive: fix race on cpufreq TRANSITION notifier
* 067c9aa epoll: use freezable blocking call
* 781d3f4 cpufreq: interactive: avoid underflow on active time calculation
* e44df65 cpufreq: interactive: reduce chance of zero time delta on load eval
* b97155d cpufreq: interactive: handle errors from cpufreq_frequency_table_target
* 7ea3d3a android: configs: no MODULES for base, no SIP for recommended
* f187b7a android: configs: Reorder config fragments
* 3138b80 android: configs: Enable KSM support by default
* 9784620 android: configs: Add Logitech unifying receivers to recommended
* 6b78c8f misc: uidstat: avoid create_stat() race and blockage.
* c01980e mmc: Add tracepoints of mmc block operations
* bad385c lowmemorykiller: make default lowmemorykiller debug message useful
* 73e652f ARM: fault: assume no context when IRQs are disabled during data abort.
* fe07fa4 cpufreq: interactive: fix uninitialized spinlock
* f744ad1 android: configs: Initial commit of Android config fragments
* c75bf46 trace/events: fix gpu event timestamp formatting
* 1307afc ARM: convert build of appended dtb zImage to list of dtbs
* 6abd648 netfilter: qtaguid: rate limit some of the printks
* 047672d cpufreq: interactive: base above_hispeed_delay on target freq, not current
* 8510234 ARM: add config option to build zImage/dtb combo
* e447502 cpufreq: interactive: fix crash on error paths in get_tokenized_data
* 65b737a cpufreq: interactive: add io_is_busy interface
* 23400cd cpufreq: interactive: allow arbitrary speed / delay mappings
* 6f6f99a trace: add non-hierarchical function_graph option
* 0438cf8 trace: Add an option to show tgids in trace output
* 1058a5c Add security hooks to binder and implement the hooks for SELinux.
* 0153a50 input: misc: keychord: log when keychord triggered
* 090b879 trace/events: add gpu trace events
* 42b09eb power: android-battery: push uevent whenever charge source changes
* 4354a91 power: android-battery: remove ac and usb supplies
* 6952a6d6 netfilter: xt_qtaguid: Allow tracking loopback
* fc740ec netfilter: xt_qtaguid: extend iface stat to report protocols
* 7450369 cpufreq: interactive: fix race on governor start/stop
* e227c9c netfilter: xt_qtaguid: remove AID_* dependency for access control
* 6e0e613 cpufreq: interactive: fix deadlock on spinlock in timer
* 67dd6bf cpufreq: interactive: don't handle transition notification if not enabled
* 221eb7f cpufreq: interactive: init default values at compile time
* bf717f1 cpufreq: interactive: default go_hispeed_load 99%, doc updates
* e1eedab cpufreq: interactive: fix race on timer restart on governor start
* b19a7fb cpufreq: interactive: fix racy timer stopping
* 97a5a11 cpufreq: interactive: fix boosting logic
* 04cc788 cpufreq: interactive: add timer slack to limit idle at speed > min
* 6f5f010 hardlockup: detect hard lockups without NMIs using secondary cpus
* b6b0a06 cpufreq: interactive: specify duration of CPU speed boost pulse
* 07a570f cpufreq: interactive: adjust load for changes in speed
* c4c4a1a cpufreq: interactive: remove load since last speed change
* 8554e8e cpufreq: interactive: allow arbitrary speed / target load mappings
* d690f0d cpufreq: interactive: apply above_hispeed_delay to each step above hispeed
* a65b783 cpufreq: interactive: change speed according to current speed and target load
* 4e57312 cpufreq: interactive: trace actual speed in target speed decisions
* 3711323 usb: gadget: accessory: Fix section mismatch (again)
* 0089219 netfilter: qtaguid: Don't BUG_ON if create_if_tag_stat fails
* 15f73a9 cpufreq: interactive: kick timer on idle exit past expiry
* 242ba48 cpufreq: interactive: use deferrable timer by default
* 7edb570 cpufreq: interactive: pin timers to associated CPU
* e128a41 ARM: fiq_debugger: fix uninitialised spin_lock.
* f27ba81 ARM: fiq_debugger: lock between tty and console writes
* 9bc9706 sync: add Documentation/sync.txt
* b068cc6 power: android-battery: Allow changing current in charging state
* 51b4fc8 staging:iio:events: Don't copy data to user-space with a locked spinlock.
* f230dcd power: android-battery: Battery health check only when connected to charger
* d575027 netfilter: xt_qtaguid: fix error exit that would keep a spinlock.
* 47a0d82 power: android-battery: use freezable workqueue for monitor
* f68c7ef mm: vmscan: Add a debug file for shrinkers
* 2324671 power: android-battery: Fix battery alarm timer not modified at suspend
* 1a5e756 power: android-battery: leave full/not-charging status when charger re-sensed
* f5f4ced power: android-battery: Add state locking
* 30a9fdc power: android-battery: add charge timeouts and recharge logic
* d4854b0 cpufreq: interactive: run at fraction of hispeed_freq when load is low
* c034ef7 staging: android: lowmemorykiller: Add config option to support oom_adj values
* ec0ab3f cpufreq: interactive: always limit initial speed bump to hispeed
* 07eafd9 USB: gadget: f_audio_source: New gadget driver for audio output
* 41bda8a USB: gadget: f_accessory: Add support for HID input devices
* 9632d13 USB: gadget: Add ACCESSORY_SET_AUDIO_MODE control request and ioctl
* 0c10673 w1: ds2482: Manage SLPZ pin sleep state
* b094216 netfilter: xt_qtaguid: report only uid tags to non-privileged processes
* 46547e0 power: android-battery: use 1/10th deg C units for temperature
* ca3f549 power: android-battery: Add USB and AC battery power supplies
* 185e045 power: android-battery: Provide fake values when fuel gauge missing
* e5105fc ARM: disable preemption in machine_shutdown
* 04a64c1 netfilter: xt_IDLETIMER: Rename INTERFACE to LABEL in netlink notification.
* 41c580c power: android_battery: nn.n temperature format for /d/android-power
* 30a7240 power: android_battery: fix negative temperature display
* 03966a9 power: android: switch to nn.n format for temperature readings
* 2b52afc power: android: battery monitor polling with wakeup alarms
* 11ac0e8 power: android: add /d/android-power
* 359bc16 power: android battery: add generic android battery driver
* 948f4f0 ARM: fiq_debugger: add process context reboot command
* 633e92c power: power_supply: add POWER_SUPPLY_PROP_CHARGE_ENABLED
* 13ffee0 cpufreq: interactive: remove input_boost handling
* e5fe0ea cpufreq: interactive: handle speed up and down in the realtime task
* 7844b0e cpufreq: interactive: keep freezer happy when not current governor
* 8d48af8 cpufreq: interactive: take idle notifications only when active
* eae725d power: power_supply: add POWER_SUPPLY_PROP_USB_OTG
* 011c4c7 power: power_supply: move POWER_SUPPLY_PROP_USB_HC to type 'int' order
* 4ae7328 power_supply: Add custom property for USB High Current mode
* ba778b8 usb: gadget: accessory: Fix section mismatch
* 2c0fb4c gpio_input: convert from wakelocks to wakeup sources
* 34bc030 usb: gadget: android: Add FunctionFS
* 195382b PM / Suspend: Print wall time at suspend entry and exit
* b071a80 usb: gadget: android: Fix product name
* 9c3b060 cpufreq: interactive: fixup trace of string params
* f204afd cpufreq: interactive: restart above_hispeed_delay at each hispeed load
* c5c7f4d usb: gadget: composite: Fix corruption when changing configuration
* e7051b4 debug: add parameters to prevent entering debug mode on errors
* 8bbe0d9 usb: otg: otg-wakelock: Fix build for 3.4
* 7bf5a6e trace: power: add trace_clock_set_parent
* cb0d1ec netfilter: xt_qtaguid: start tracking iface rx/tx at low level
* 643e385 netfilter: xt_IDLETIMER: Add new netlink msg type
* 59bba74 Include if_pppolac.h and if_pppopns.h into header-y target
* 13d423b security: Add proper checks for Android specific capability checks
* 4a88058 cpufreq-interactive: Compile fixup
* 123f74a cpufreq: interactive: add boost pulse interface
* c4bc080 cpufreq: interactive: set floor for boosted speed
* 07f4f87 cpufreq: interactive: Add sysfs boost interface for hints from userspace
* b9c1d7e cpufreq: interactive: remove unused target_validate_time_in_idle
* dbbe568 cpufreq: interactive: Boost frequency on touchscreen input
* cb38019 cpufreq: interactive: Separate speed target revalidate time and initial set time
* 9ce1c92 cpufreq: interactive: base hispeed bump on target freq, not actual
* 58bc042 cpufreq: interactive: adjust code and documentation to match
* 99055c9 cpufreq: interactive: configurable delay before raising above hispeed
* a394232 cpufreq: interactive: don't drop speed if recently at higher load
* 1792e5f cpufreq: interactive: set at least hispeed when above hispeed load
* 15cf471 cpufreq: interactive: apply intermediate load to max speed not current
* e8006db cpufreq interactive governor: event tracing
* 9a9906b netfilter: xt_qtaguid: fix ipv6 protocol lookup
* 3cedb6c netfilter: qtaguid: initialize a local var to keep compiler happy.
* db6d34f ARM: etm: Add sysfs entry to enable return stack if supported
* bdc1ab9 ARM: etm: Add sysfs entry to disable branch_output flag
* 16c2bcd ARM: etm: Add sysfs entry to set context-id-size
* 43f9919 ARM: etm: Add sysfs entry to enable timestamps if supported
* a76f3da ARM: etm: Check arch version and disable data tracing for ptm
* d2bed0a ARM: etm: Wait for etm/ptm(s) to stop before requesting PowerDown
* ddaeb65 usb: gadget: adb: Only enable the gadget when adbd is ready
* cfb0acf ARM: fiq_debugger: fix multiple consoles and make it a preferred console
* c884ce0 kdb: support new lines without carriage returns
* 77ce792 ARM: fiq_debugger: add support for kgdb
* 3696393 ARM: fiq_debugger: add debug_putc
* b3de636 ARM: fiq_debugger: add support for reboot commands
* 9653fa0 ARM: fiq_debugger: fix compiling for v3.3
* 96c556f usb: gadget: adb: do not set error flag when dequeuing req
* afe609f usb: gadget: adb: allow freezing in adb_read
* d588b95 usb: gadget: accessory: Add Android Accessory function
* ee02367 usb: gadget: adb: Add ADB function
* 88fe098 usb: gadget: mtp: Add MTP/PTP function
* 9047fe4 usb: gadget: Add Android Composite Gadget driver
* 0386973 usb: otg: otg-wakelock: fix build for 3.3
* 76abd55 usb: otg: Temporarily grab wakelock on charger and disconnect events
* 274ba2d HID: Add input_register callback.
* 71a389b fuse: Freeze client on suspend when request sent to userspace
* 9956451 hid-multitouch: Filter collections by application usage.
* 11cee2b net: Only NET_ADMIN is allowed to fully control TUN interfaces.
* 0ca1fb7 bridge: Have tx_bytes count headers like rx_bytes.
* 201bc39 netfilter: ipv6: fix crash caused by ipv6_find_hdr()
* 917596c netfilter: fixup the quota2, and enable.
* e78618c netfilter: adding the original quota2 from xtables-addons
* 9ed0e95 USB: OTG: Take wakelock when VBUS present
* 8468092 netfilter: add xt_qtaguid matching module
* eaac37e net: wireless: change the expire time about each entry of scan results
* 9486c0a net: wireless: Add CONFIG_WIFI_CONTROL_FUNC option
* 006b934 net: wireless: Add get_country_code functionality to platform
* dd0aa6b network: wireless: Add get_mac_addr functionality to platform
* 76a8527 ARM: etm: Power down etm(s) when tracing is not enabled
* 5ecc7ec ARM: etm: Support multiple ETMs/PTMs.
* 385e006 ARM: etm: Return the entire trace buffer if it is empty after reset
* 3994a5c ARM: etm: Add some missing locks and error checks
* ae815d2 ARM: etm: Configure data tracing
* 8f800a7 ARM: etm: Allow range selection
* baee56b ARM: etm: Don't try to clear the buffer full status after reading the buffer
* 18d547c ARM: etm: Don't limit tracing to only non-secure code.
* e2f5eed ARM: etm: Don't require clock control
* 34fc6c8 mmc: sdio: Fix sdio_reset_comm for sync
* 3563816 fix sdio.c
* 118c205 net: PPPoPNS and PPPoLAC update to use PPP_MRU instead of PPP_MRU
* ccf633b net: Reorder incoming packets in PPPoLAC and PPPoPNS.
* efb5961 cpufreq: interactive: New 'interactive' governor
* 6b7343f ARM: Call idle notifiers
* f0cf66d Move x86_64 idle notifiers to generic
* 85139a9 staging: remove Greg's TODO, now obsolete.
* 6c01d69 ARM: Add generic fiq serial debugger
* 1ca159e ARM: Add fiq_glue
* 38bd652 net: Fix CONFIG_RPS option to be turned off
* e84594a net: activity_stats: Add statistics for network transmission activity
* ae57804 staging: android: lowmemorykiller: Fix task_struct leak
* 1a2a1b8 sched: Add a generic notifier when a task struct is about to be freed
* 5646b78 wlan: Extract generic wlan platform data from tiwlan specific header
* 2255e42 block: genhd: Add disk/partition specific uevent callbacks for partition info
* f0ce0ee proc: smaps: Allow smaps access for CAP_SYS_RESOURCE
* 0772b6e serial_core: Add wake_peer uart operation
* 1fb6ede rfkill: Introduce CONFIG_RFKILL_PM and use instead of CONFIG_PM to power down
* 6a3db02 net: Replace AID_NET_RAW checks with capable(CAP_NET_RAW).
* 7985836 security: Add AID_NET_RAW and AID_NET_ADMIN capability check in cap_capable().
* 9b2fc55 net: PPPoPNS and PPPoLAC fixes.
* e7e501c net: add PPP on PPTP Network Server (PPPoPNS) driver.
* f119bc2 net: add PPP on L2TP Access Concentrator (PPPoLAC) driver.
* a42d6db fs: block_dump: Don't display inode changes if block_dump < 2
* fee4e83 tiwlan: Add abstract wifi control functions support
* b794617 mmc: block: Improve logging of handling emmc timeouts
* b07da91 ARM: Add 'card_present' state to mmc_platfrom_data
* 075d97f Recreate asm/mach/mmc.h include file
* cc84bb6 mmc: Add "ignore mmc pm notify" functionality
* b3d57f9 mmc: sdio: Fix enable_hs and enable_wide in sdio_reset_comm()
* 59a77cf mmc: sdio: Add high speed support to sdio_reset_comm()
* 25a68bf mmc: sdio: Claim host in sdio_reset_comm()
* 2c84417 mmc: mmcblk: Add support for deferred SD bus resume
* c4cda98 mmc: core: Hold a wake lock accross delayed work + mmc rescan
* 12e626d mmc: sd: Add retries in re-detection
* 65a213f mmc: sd: When resuming, try a little harder to init the card
* acdaebe mmc: Add new API call 'sdio_reset_comm' for resetting communication with an SDIO device
* 59d1a8e trout: Add functions for WiFi
* 488ad4b mmc: Add concept of an 'embedded' SDIO device.
* 9faee23 mmc: sd: Add new CONFIG_MMC_PARANOID_SD_INIT for enabling retries during SD detection
* 46f230f mmc: Add status IRQ and status callback function to mmc platform data
* 06bf8b1 input: keychord: Add keychord driver
* a8b7f81 input: Add keyreset driver.
* 014a453 input: misc: gpio_event: remove early suspend
* 811868b Input: Generic GPIO Input device.
* ec4fa93 Grants system server access to /proc/<pid>/oom_adj for Android applications.
* 7114169 misc: uidstat: Adding uid stat driver to collect network statistics.
* c7c3ec4 net: socket ioctl to reset connections matching local address
* b23a0e3 sysfs_net_ipv4: Add sysfs-based knobs for controlling TCP window size
* db0e079 Paranoid network.
* 2e8e5a0 ashmem: Add shmem_set_file to mm/shmem.c
* c2ff66b Add android_aid.h
* fd10c98 Input: evdev - Add ioctl to block suspend while event queue is not empty.
* 311d4b0 HACK: input: evdev: disable EVIOCREVOKE
* d6620cf switch: switch class and GPIO drivers.
* 012ce32 PM / Sleep: Add wake lock api wrapper on top of wakeup sources
* a4616e0 Revert "locking: Remove deprecated smp_mb__() barriers"
* bf47433 panic: Add board ID to panic output
* 2cc932a ARM: add option to flush console before reboot
* 00e6d24 cpuidle: governor: menu: don't use loadavg
* 84b8945 sched: Enable might_sleep before initializing drivers.
* 0e5a766 ARM: Make low-level printk work
* 8564367 [docs] android: Add android config documentation to boot framework.
* 36144dc [ARM] Optionally flush entire dcache from v6_dma_flush_range
* aa49fa8 mm: Add min_free_order_shift tunable.
* 0ddfd45 [ARM] armv6 dcc tty driver
* d4dcc857 ARM: smp: implement arch_trigger_all_cpus_backtrace using IPI
* 7e0e701 power: Add option to log time spent in suspend
* ac20546 [ARM] process: Add display of memory around registers when displaying regs.
* 4f0d286 drivers: power: Add watchdog timer to catch drivers which lockup during suspend.
* 163a416 mmc_block: Allow more than 8 partitions per card
* c8e2b5b mtd: nand: Allow NAND chip ids to be included standalone.
* f945a12 Make /dev/mem configurable, as we don't want it.
* b2776bf Linux 3.18
