## Project-Xiaomi-Yuechu-dev - Personal extras
<img align="right" width="180" height="180" src="https://github.com/Project-Xiaomi-Yuechu-dev/.github/blob/main/profile/XiaomiCivi3.png">

This organization contains repositories to build AOSP ROMs for Xiaomi Civi 3 (yuechu) with personal additions and modifications over [xiaomi-mediatek-devs](https://github.com/xiaomi-mediatek-devs) and [XagaForge](https://github.com/XagaForge) trees.

### Repositories
* [**Device Tree (yuechu)**](https://github.com/Project-Xiaomi-Yuechu-dev/android_device_xiaomi_yuechu.git) (`android_device_xiaomi_yuechu`)
* [**Kernel Tree (mt6895)**](https://github.com/Project-Xiaomi-Yuechu-dev/android_kernel_xiaomi_mt6895) (`android_kernel_xiaomi_mt6895`)
* [**Vendor Tree (yuechu)**]
* [**MIUI Camera (yuechu)**]

Repositories such as `android_hardware_mediatek`, `android_hardware_xiaomi` and `android_device_mediatek_sepolicy_vndr` remain unmodified and can be used directly from the  [XagaForge](https://github.com/XagaForge) or [xiaomi-mediatek-devs](https://github.com/xiaomi-mediatek-devs) organization.


### External patches
* [compat: expose android.hardware.sensors@1.0-convert as shared lib](https://review.lineageos.org/c/400894)
* [sensors: Add a sensors 2.0 -> 1.0 subhal wrapper](https://github.com/bengris32/android_hardware_lineage_interfaces/commit/cacfae73e44d18f8bba2bbe327d5c0d5cbafe4f1)
* [vendor: Add fastboot packages build](https://github.com/AresOS-UDC/vendor_lineage/commit/19afe7c7e98c9ff5f57c57d09edfa954142e65b6) (Only required if you choose to build fastboot packages using our method)
