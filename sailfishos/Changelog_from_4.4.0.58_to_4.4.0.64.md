============================================================================
SAILFISH OS
Changelog from 4.4.0.58 to 4.4.0.64
2022-05-11
============================================================================
# PACKAGES MODIFIED

### apkd-l10n
- Updated : 1.145.2-1.6.1.jolla -- 1.145.3-1.7.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 38 of 38 strings translated (0 need review).
### commhistory-daemon-l10n
- Updated : 1.90.2-1.6.1.jolla -- 1.90.3-1.7.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 43 of 43 strings translated (0 need review).
### droid-config-xqbt52
- Updated : 1.8.2.5-1.10.1.jolla -- 1.8.2.10-1.13.1.jolla
- [dconf] Add key to show reboot dialog when inserting sim cards. Fixes JB#58107
- [patterns] Add VoLTE enablers to adaptation pattern. Fixes JB#58058
- [configs] Set default data profile id. JB#58008
- [configs] Add workaround for camera service crash. JB#58037
- [configs] Add possibility to define specific VOIP sink. JB#55832
- [sparse] Add a service for memory reclaim. JB#57321
- [sparse] Disable update_verifier for ports starting from Android 10. JB#57317
- [sparse] Move sysctl files to /usr/lib. Fixes JB#57254
### droid-hal-pdx213
- Updated : 1.8.4-1.6.1.jolla -- 1.9.0-1.7.4.jolla
- [kernel] Fix display brightness control. Fixes JB#57811 JB#57813
- [dhd] Immediately fail Android builds on OBS if a command fails. Fixes JB#54209 JB#57846
- [helpers] Build pulseaudio-modules-droid-jb2q for Android versions up to 10. JB#55832
- [kernel] Fix defconfig symbol wrongfully changed. JB#56192
- [kernel] Fix port lowmemorykiller driver from 4.14. JB#57685
- [helpers] Refactor utils to use mb2 --package-timeline. Contributes to JB#56780
- [kernel] Port lowmemorykiller driver from 4.14 and enable android lmk. JB#57685
- [kernel] Replace or remove invalid config symbols in hybris defconfig. JB#56192
- [localbuild] Make all build script changes persistent. JB#57413
- [localbuild] Pass local repo to zypper ahead of `ssu ar` removal. JB#57413
- [localbuild] Remove leftovers manually for now. JB#56780
- [localbuild] Switch local repo to flat dir structure. JB#57413
- [localbuild] Use mb2 --output-dir instead to deploy RPMs. JB#57413
- [localbuild] Use sdk-assistant maintain instead of sb2. JB#57413
### droid-src-sony-lena
- Updated : 1.8.4-1.5.3.jolla -- 1.9.1-1.7.1.jolla
- [hybris] mixer_paths: Use handset mic for speaker mode workaround. JB#57389
- [camera] QCamera2: mm-interface: Change media entity enumeration logic for k4.19. JB#58021
- [droid-src] frameworks: av: Fix browser crash after playing videos. Fixes JB#58022
- [hybris] device: sony: common: Proper SIM detection fix is now upstream. JB#57998
- [sony-common] Revert "init: qcrild.rc : Add vendor prefix to ril-daemon". Fixes JB#57998
### droid-system-pdx213
- Updated : 1.9.1-1.7.1.jolla -- 1.9.6-1.10.1.jolla
- [system] Enable loudspeaker echo cancellation. JB#57982
- [hybris] mixer_paths: Use handset mic for speaker mode workaround. JB#57389
- [camera] QCamera2: mm-interface: Change media entity enumeration logic for k4.19. JB#58021
- [droid-src] frameworks: av: Fix browser crash after playing videos. Fixes JB#58022
- [hybris] device: sony: common: Proper SIM detection fix is now upstream. JB#57998
- [sony-common] Revert "init: qcrild.rc : Add vendor prefix to ril-daemon". Fixes JB#57998
- [hybris] device: sony: lena: Disable sensors of tele and uwide lenses for now. JB#56689
- [hybris] init: Enable low memory killer. JB#57685
### droid-system-pdx213-xqbt52
- Updated : 1.9.1-1.7.1.jolla -- 1.9.6-1.10.1.jolla
- [system] Enable loudspeaker echo cancellation. JB#57982
- [hybris] mixer_paths: Use handset mic for speaker mode workaround. JB#57389
- [camera] QCamera2: mm-interface: Change media entity enumeration logic for k4.19. JB#58021
- [droid-src] frameworks: av: Fix browser crash after playing videos. Fixes JB#58022
- [hybris] device: sony: common: Proper SIM detection fix is now upstream. JB#57998
- [sony-common] Revert "init: qcrild.rc : Add vendor prefix to ril-daemon". Fixes JB#57998
- [hybris] device: sony: lena: Disable sensors of tele and uwide lenses for now. JB#56689
- [hybris] init: Enable low memory killer. JB#57685
### jolla-alarm-ui-l10n
- Updated : 1.98.2-1.7.1.jolla -- 1.98.3-1.8.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 31 of 33 strings translated (2 need review).
### jolla-calendar-l10n
- Updated : 1.249.2-1.8.1.jolla -- 1.249.3-1.9.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 139 of 139 strings translated (0 need review).
### jolla-camera
- Updated : 1.2.16.2-1.8.1.jolla -- 1.2.16.3-1.9.1.jolla
- [jolla-camera] Restart camera upon error (xperia 10 III). Fixes JB#58037
### jolla-camera-l10n
- Updated : 1.218.2-1.8.1.jolla -- 1.218.3-1.9.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 73 of 73 strings translated (0 need review).
### jolla-clock-l10n
- Updated : 1.162.2-1.6.1.jolla -- 1.162.3-1.7.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 47 of 48 strings translated (0 need review).
### jolla-contacts-l10n
- Updated : 1.187.2-1.7.1.jolla -- 1.187.3-1.8.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 60 of 60 strings translated (0 need review).
### jolla-devicelock-l10n
- Updated : 1.48.2-1.5.1.jolla -- 1.48.3-1.6.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 7 of 7 strings translated (0 need review).
### jolla-email-l10n
- Updated : 1.293.2-1.7.1.jolla -- 1.293.5-1.8.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 233 of 233 strings translated (0 need review).
- [l10n JB#32057] Commit from Jolla localisation by user jahonen.: 233 of 233 strings translated (0 need review).
- [l10n JB#32057] Commit from Jolla localisation by user jahonen.: 233 of 233 strings translated (0 need review).
### jolla-gallery-facebook-l10n
- Updated : 1.74.3-1.5.1.jolla -- 1.74.4-1.6.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 14 of 14 strings translated (0 need review).
### jolla-gallery-l10n
- Updated : 1.172.2-1.8.1.jolla -- 1.172.3-1.9.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 17 of 17 strings translated (0 need review).
### jolla-messages-l10n
- Updated : 1.199.2-1.8.1.jolla -- 1.199.3-1.9.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 88 of 88 strings translated (0 need review).
### jolla-settings-l10n
- Updated : 1.145.2-1.7.1.jolla -- 1.145.3-1.8.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 22 of 22 strings translated (0 need review).
### jolla-settings-sailfishos-l10n
- Updated : 1.139.2-1.8.1.jolla -- 1.139.3-1.9.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 53 of 53 strings translated (0 need review).
### jolla-settings-system-l10n
- Updated : 1.556.5-1.12.1.jolla -- 1.556.6-1.13.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 631 of 631 strings translated (0 need review).
### libgbinder-radio
- Updated : 1.4.8-1.4.1.jolla -- 1.4.10-1.5.1.jolla
- [gbinder-radio] Tweaked completion callback criteria. JB#58006
- [gbinder-radio] Added IMS types. JB#57425
### libglibutil
- Updated : 1.0.61-1.12.1.jolla -- 1.0.62-1.13.1.jolla
- [glibutil] Added gutil_strlen0()
- [glibutil] Added gutil_strv_find_last() and gutil_strv_remove_dups()
- [glibutil] Fixed a few weird unit test issues
- [glibutil] JB#33786
- [license] Freshened up copyright
### lipstick-jolla-home-qt5-l10n
- Updated : 1.428.2-1.8.1.jolla -- 1.428.3-1.9.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 262 of 262 strings translated (0 need review).
### mlsdb-data
- Updated : 0.1.5-1.9.1.jolla -- 0.1.6-1.10.1.jolla
- [mlsdb] Update Mozilla Location DB offline data to 2022-03-22. JB#57070
### ofono
- Updated : 1.28+git3.1-1.12.1.jolla -- 1.28+git3.2-1.13.1.jolla
- [ims] D-Bus access control for org.ofono.IpMultimediaSystem. JB#57408
- [ims] Disable IMS registration by default
- [ims] Extend org.ofono.IpMultimediaSystem D-Bus API. JB#57999
- [ims] Tweak the treatment of the default Registration value
- [watch] Added reg_tech watch. JB#57999
### ofono-binder-plugin
- Updated : 1.0.2-1.1.1.jolla -- 1.1.1-1.2.1.jolla
- Binaries added : libofonobinderpluginext - 1.1.1-1.2.1.jolla, libofonobinderpluginext-devel - 1.1.1-1.2.1.jolla
- [ofono-binder] Allow lte value for MaxNonDataMode. JB#58069
- [ofono-binder] Fix startup with IRadioConfig 1.2 missing. JB#57298
- [ofono-binder] Make data profile ids configurable. JB#58008
- [build] Make sure strip is defined
- [ext] Debian packaging for libofonobinderpluginext. JB#57495
- [ext] Don't invoke virtual method from a slot finalizer
- [ext] Removed binder_ext_slot_plugin_name
- [ofono-binder] Added IMS state registration tracker object. JB#57425
- [ofono-binder] Documented extPlugin config option
- [ofono-binder] Extension for voice calls. JB#57724
- [ofono-binder] Fixed conversion of vec<string> to char**
- [ofono-binder] Housekeeping
- [ofono-binder] IMS control extension. JB#57495
- [ofono-binder] Prevent infinite recursion
- [ofono-binder] Refactored SMS extension interface. JB#57425
- [ofono-binder] Send SMS over IMS when we can. JB#57425
- [ofono-binder] Support for plugin extensions. JB#57495
- [ofono-binder] Tweaked SMS extension interface. JB#57425
- [unit] More unit tests
- [ofono-binder] Added ofono_ims_driver. JB#57408
### qmf-eas-plugin-l10n
- Updated : 1.110.2-1.7.1.jolla -- 1.110.3-1.8.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 106 of 106 strings translated (0 need review).
### qt5
- Updated : 5.6.3+git46.1-1.16.2.jolla -- 5.6.3+git46.2-1.17.1.jolla
- [qtbase] Protect QNetworkAccessManager on duplicated state changes. JB#57985
### sailfish-browser-l10n
- Updated : 1.262.8-1.15.1.jolla -- 1.262.9-1.16.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 162 of 162 strings translated (0 need review).
### sailfish-components-contacts-qt5-l10n
- Updated : 1.198.2-1.7.1.jolla -- 1.198.3-1.8.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 158 of 158 strings translated (0 need review).
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 158 of 161 strings translated (0 need review).
### sailfish-components-filemanager-l10n
- Updated : 1.99.4-1.7.1.jolla -- 1.99.5-1.8.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 65 of 65 strings translated (0 need review).
### sailfish-components-webview-qt5-l10n
- Updated : 1.83.4-1.11.1.jolla -- 1.83.5-1.12.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 123 of 123 strings translated (0 need review).
### sailfish-office-l10n
- Updated : 1.156.2-1.7.1.jolla -- 1.156.3-1.8.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 86 of 86 strings translated (0 need review).
### sailfish-utilities
- Updated : 0.1.14-1.5.11.jolla -- 0.1.16-1.6.1.jolla
- [sailfish-utilities] Add a Restart Fingerprint button. Fixes JB#57941
- [sailfish-utilities] Updated project file for easier development.
- [sailfish-utilities] Include license file as %license. JB#55991
### sailfishsilica-qt5-l10n
- Updated : 1.156.3-1.6.1.jolla -- 1.156.6-1.7.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 49 of 107 strings translated (0 need review).
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 49 of 49 strings translated (0 need review).
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 87 of 87 strings translated (0 need review).
- [l10n JB#32057] Commit from Jolla localisation by user jahonen.: 49 of 107 strings translated (0 need review).
- [l10n JB#32057] Commit from Jolla localisation by user jahonen.: 49 of 107 strings translated (0 need review).
### sailjail-permissions
- Updated : 1.0.99-1.30.2.jolla -- 1.1.0-1.31.1.jolla
- [permissions] Allow Location to access sensors to make compass work. Fixes JB#58000
### simkit-l10n
- Updated : 1.59.3-1.5.1.jolla -- 1.59.4-1.6.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 14 of 14 strings translated (0 need review).
### voicecall-ui-jolla
- Updated : 1.14.38-1.5.1.jolla -- 1.14.38.1-1.6.1.jolla
- [voicecall-ui] Combine desktop files. Fixes JB#54944
- [voicecall-ui] Combine desktop files. Fixes JB#58109
### voicecall-ui-jolla-l10n
- Updated : 1.301.2-1.8.1.jolla -- 1.301.3-1.9.1.jolla
- [l10n JB#32057] Commit from Jolla localisation by user sleleiva.: 250 of 250 strings translated (0 need review).
### xulrunner-qt5
-  Updated : 78.15.1+git24.1-1.30.1.jolla -- 78.15.1+git24.2-1.31.1.jolla
- [sailfishos][embedlite] Drop radio and checkbox max size restriction. Fixes JB#57693
