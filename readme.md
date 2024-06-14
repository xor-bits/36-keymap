```
make CONVERT_TO=promicro_rp2040 splitkb/aurora/sweep/rev1:custom
doas mount -o gid=1000,uid=1000 /dev/disk/by-label/RPI-RP2 /mnt
cp splitkb_aurora_sweep_rev1_custom_promicro_rp2040.uf2 /mnt/
```
