# clone-stuff
```
rm -rf vendor/qcom/opensource/commonsys-intf/display
rm -rf hardware/qcom-caf/sdm845/media
rm -rf hardware/qcom-caf/sdm845/audio
rm -rf hardware/qcom-caf/sdm845/display
git clone https://github.com/beryllium-sdm845/device_xiaomi_beryllium.git device/xiaomi/beryllium
git clone https://github.com/beryllium-sdm845/android_kernel_xiaomi_sdm845-1.git kernel/xiaomi/sdm845
git clone https://github.com/beryllium-sdm845/device_xiaomi_sdm845-common.git device/xiaomi/sdm845-common
git clone https://github.com/beryllium-sdm845/vendor_xiaomi.git vendor/xiaomi
git clone https://github.com/aex-tmp/platform_vendor_qcom_opensource_display-commonsys-intf.git vendor/qcom/opensource/commonsys-intf/display
git clone https://github.com/aex-tmp/platform_hardware_qcom_display.git -b 12.x-caf-sdm845 hardware/qcom-caf/sdm845/display
git clone https://github.com/aex-tmp/platform_hardware_qcom_media.git -b 12.x-caf-sdm845  hardware/qcom-caf/sdm845/media
git clone https://github.com/aex-tmp/platform_hardware_qcom_audio.git -b 12.x-caf-sdm845  hardware/qcom-caf/sdm845/audio

```

# dot-clone-stuff
```
git clone https://github.com/beryllium-sdm845/dot_device_xiaomi_beryllium.git device/xiaomi/beryllium
git clone {New kernel Soon} kernel/xiaomi/sdm845
git clone https://github.com/beryllium-sdm845/dot_device_xiaomi_beryllium-common.git device/xiaomi/sdm845-common
git clone https://github.com/beryllium-sdm845/dot_vendor_xiaomi.git vendor/xiaomi
```
