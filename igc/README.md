This is the driver sources for Linux v3.10

To compile, install and load:

```bash
# cd igc
# make -C /lib/modules/`uname -r`/build M=$PWD modules
# sudo cp igc.ko /lib/modules/kernel/net/ethernet
# sudo depmod
# modprobe igc
```
