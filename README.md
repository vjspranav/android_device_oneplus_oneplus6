to build you need to modify the buildinfo.sh in build/tools
echo "ro.build.version.release=$PLATFORM_VERSION"
echo "ro.build.version.security_patch=$PLATFORM_SECURITY_PATCH"
to
echo "ro.build.version.release_orig=$PLATFORM_VERSION"
echo "ro.build.version.security_patch_orig=$PLATFORM_SECURITY_PATCH"

to remove twrp app
https://gerrit.omnirom.org/#/c/android_bootable_recovery/+/27694/

to add vibration
https://gerrit.omnirom.org/#/c/android_bootable_recovery/+/31021/
TW_USE_LEDS_HAPTICS := true

to fix screen shot color
https://gerrit.omnirom.org/#/c/android_bootable_recovery/+/31042/
