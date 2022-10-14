# Linux-6.0.1 kernel for allwinner t113-s3 (MangoPi Dual)

### compile
```
make mangopi_dual_t113_defconfig
make zImage dtbs modules -jx
```

### output file 
```
arch/arm/boot/zImage
arch/arm/boot/dts/sun8i-t113-mangopi-dual.dtb
```
