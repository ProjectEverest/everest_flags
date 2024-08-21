# Build Flags

### Maintainer name for Everest

```
EVEREST_MAINTAINER := "XYZ"
```

### Adding Blur support

```
TARGET_SUPPORTS_BLUR := true
```

### For UDFPS devices

```
TARGET_HAS_UDFPS := true

EXTRA_UDFPS_ANIMATIONS := true
```

### Build GAPPS\Vanilla

```
WITH_GAPPS := true\false
```

### Pixel Launcher Recent Blur(Enabled by Default)

```
TARGET_USES_BLUR_RECENT := false
```


### Quick switch (add more than one Launcher in build)

```
TARGET_PREBUILT_LAWNCHAIR_LAUNCHER := true

TARGET_DEFAULT_PIXEL_LAUNCHER := true
```

## Configs

- [TouchScreen and KeyHandler](https://github.com/ProjectEverest-Devices/android_device_oneplus_sm8350-common/commit/eb2e657793689ad2d438d26f1567759f2841a24c)
- [SmartPixel](https://github.com/ProjectEverest-Devices/android_device_oneplus_sm8350-common/commit/0dc555a5a95e6248f7ee81940062e1140e501146)
- [Disable SmartPixel On UDFPS](https://github.com/ProjectEverest-Devices/android_device_oneplus_sm8350-common/commit/0365948a19b50c7b254764dd149a85558d29c3f0)
- [ScreenOff UDFPS](https://github.com/ProjectEverest-Devices/android_device_realme_lunaa/commit/e4c40f6f605a21c86fe1bd5ffe71e7b9083a6300)
