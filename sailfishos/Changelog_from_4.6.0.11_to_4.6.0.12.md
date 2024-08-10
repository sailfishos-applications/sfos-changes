============================================
SAILFISH OS
Changelog from 4.6.0.11 to 4.6.0.12
2024-06-06
============================================

# PACKAGES MODIFIED

### appsupport11-system-privileged
- Updated : 11.0.0.74.46.1-1.5.1.jolla -- 11.0.0.74.46.2-1.6.1.jolla
- [appsupport] Call roundtrip until an apps buffers are released when it's being closed. 
- [appsupport] Fully remove freeform windowing feature.

### appsupport11-system-unprivileged
- Updated : 11.0.0.74.46.1-1.5.1.jolla -- 11.0.0.74.46.2-1.6.1.jolla
- [appsupport] Call roundtrip until an apps buffers are released when it's being closed.
- [appsupport] Fully remove freeform windowing feature.

### audiosystem-passthrough
- Updated : 1.3.0-1.4.7.jolla -- 1.3.1-1.6.1.jolla
- [af] Add support for android.media.IAudioFlingerService.

### droid-config-xqcc54
- Updated : 1.0.7-1.5.1.jolla -- 1.0.11-1.6.1.jolla
- [configs] Re-enable Android side fingerprint process.
- [configs] Enable fingerprint support.
- [sparse] Allow input group to access selected paths in LED sysfs.
- [udev] Add symlinks for bsg subsystem nodes.
- [configs] Remove custom ngfd configuration.
- [sparse-13] Remove apexd.rc which is moved to droid-hal.
- [configs] Disable second SIM slot in AppSupport.

### droid-config-xqdc54
- Updated : 1.0.7-1.5.1.jolla -- 1.0.12-1.6.1.jolla
- [configs] Add custom vibrator durations.
- [sparse] Allow input group to access selected paths in LED sysfs.
- [udev] Add symlinks for bsg subsystem nodes.
- [configs] Add configuration for battery charging control.
- [configs] Remove custom ngfd configuration.
- [sparse-13] Remove apexd.rc which is moved to droid-hal.
- [configs] Fix updating boot_a partition.
- [configs] Disable second SIM slot in AppSupport.

### droid-hal-pdx225
- Updated : 1.0.1-1.3.1.jolla -- 1.0.2-1.4.1.jolla
- [dhd] Package patched apexd.rc for Android >= 12.
- [hybris-patches] Fix remaining vibrator permissions.
- [hybris-patches] Patch apexd path in apexd.rc, disable forced reboot.
- [hybris-patches] Remove obsolete common-kernel patch.

### droid-hal-pdx235
- Updated : 1.0.1-1.3.1.jolla -- 1.0.2-1.4.1.jolla
- [dhd] Package patched apexd.rc for Android >= 12.
- [hybris-patches] Fix remaining vibrator permissions.
- [hybris-patches] Patch apexd path in apexd.rc, disable forced reboot.
- [hybris-patches] Remove obsolete common-kernel patch.

### droid-system-pdx225
- Updated : 1.0.0-1.1.1.jolla -- 1.0.1-1.3.1.jolla
- [murray] Update to latest upstream version from 2024-05-21.

### droid-system-pdx225-xqcc54
- Updated : 1.0.0-1.1.1.jolla -- 1.0.1-1.3.1.jolla
- [murray] Update to latest upstream version from 2024-05-21.

### droid-system-pdx235
- Updated : 1.0.0-1.1.1.jolla -- 1.0.1-1.3.1.jolla
- [zambezi] Update to latest upstream version from 2024-05-21.

### droid-system-pdx235-xqdc54
- Updated : 1.0.0-1.1.1.jolla -- 1.0.1-1.3.1.jolla
- [zambezi] Update to latest upstream version from 2024-05-21.

### jolla-alarm-ui
- Updated : 0.2.20-1.6.3.jolla -- 0.2.22-1.8.1.jolla
- [alarm-ui] Call calendar app viewEvent d-bus method with notebook uid.
- [alarm-ui] Update closed icons package name.

### jolla-calendar
- Updated : 1.1.15-1.11.1.jolla -- 1.1.15.1-1.13.1.jolla
- [calendar] Add required notebook uid to viewEvent() d-bus method.

### ngfd-plugin-droid-vibrator
- Updated : 1.4.0-1.3.3.jolla -- 1.4.1-1.5.1.jolla
- [native-vibrator] Add support for state path.

### ngfd-plugin-native-vibrator
- Updated : 1.4.0-1.6.3.jolla -- 1.4.1-1.8.1.jolla
- [native-vibrator] Add support for state path.

### ofono-binder-plugin
- Updated : 1.1.14-1.5.1.jolla -- 1.1.15-1.7.1.jolla
- [ofono-binder-plugin] Only handle voice call waiting by default.

### sailfish-utilities
- Updated : 0.1.21-1.8.1.jolla -- 0.1.22-1.9.1.jolla
- [sailfish-utilities] Add restart audio action.

### sdk-setup
- Updated : 1.4.88-1.15.1.jolla -- 1.4.89-1.17.1.jolla
- [sdk-make-qmltypes] Fix passing address to dbus-send.
- [sdk-setup] Fix generating QML bundle for multiline entries.

