# RK3228A TV box (R329Q)

Build an ARM 32-bit EmuELEC image for the R329Q board using the RK322x legacy
kernel and bootloader:

```sh
PROJECT=Rockchip DEVICE=RK322X ARCH=arm DISTRO=EmuELEC UBOOT_SYSTEM=rk322x make image
```

The image includes the `rk3229-r329q.dtb` device tree. Verify the board's RAM,
storage type, and Wi-Fi module before flashing; R329Q board revisions can use
different components.
