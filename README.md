# PR staging for openwrt/openwrt

| From (this fork) | To (upstream) | PR | Description |
|---|---|---|---|
| pr/2512-kernel-symvers-6.18 | openwrt/openwrt openwrt-25.12 | openwrt-25.12: backport kernel.mk Module.symvers.tmp 6.18 workaround | Cherry-pick of main 666fee6f48; without it, external kernel modules built against kernel 6.18 on the 25.12 base emit an empty Module.symvers |
| (planned, gated on PR #23161) | openwrt/openwrt main | qualcommbe: ipq53xx: add GL.iNet GL-BE9300 support | Device DTS, base-files, factory/sysupgrade images and stock-restore for the Flint 3; submitted after the ipq53xx subtarget series merges, coordinated with the out-of-tree port maintainer. Board-2.bin containers go to the ipq-wifi repo alongside |
