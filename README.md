# TWRP for the Samsung Galaxy J6

TWRP device tree for Samsung Galaxy J6 (`j6lte`), based on the TWRP AOSP 12.1 manifest.

## Build
```bash
source build/envsetup.sh
lunch twrp_j6lte-eng
mka recoveryimage
```
The recovery image is `out/target/product/j6lte/recovery.img`.
