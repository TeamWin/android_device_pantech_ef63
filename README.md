# android_device_pantech_ef63
Tree for building TWRP for PANTECH SKY VEGA IRON 2

## Kernel Sources

https://github.com/chautruongthinh/android_kernel_pantech_msm8x74/tree/lineage-15.1

## To compile

export ALLOW_MISSING_DEPENDENCIES=true

. build/envsetup.sh && lunch omni_ef63-eng

mka recoveryimage

## Device specifications
=======================================

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Quad-core 2.3 GHz Krait 400
CHIPSET | Qualcomm Snapdragon 801
GPU     | Adreno 330
Display | 5.3" Full HD Super AMOLED Display (1920 x 1080)
Memory  | 3GB RAM
Storage | 32GB
MicroSD | Up to 256 GB
Battery | 3,220 mAh
Dimensions | 144.2 x 73.5 x 7.9mm - 152g(Black), 153g(White)
Camera  | 13M wide OIS / 2.1M FULL HD

## Device picture

![SKY VEGA IRON 2](http://pantech.co.kr/cmm/fms/getImage.do?atchFileId=FILE_000000000008005&fileSn=1 "SKY VEGA IRON2")

Copyright 2016, TekCafe Team
