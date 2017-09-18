bq Aquaris 5 HD - CyanogenMod 11 (Android 4.4.4)
==============

### Compilation guide:

     * repo init -u git://github.com/CyanogenMod/android.git -b cm-11.0

     * repo sync 

     * git clone https://github.com/cakehonolulu/android_device_bq_Aquaris5HD device/bq/Aquaris5HD

     * . build/envsetup.sh

     * cd device/bq/Aquaris5HD/

     * . setup-makefiles.sh

     * croot

     * brunch Aquaris5HD

### What's working:

 * Sound
 * CPU Frequency Scaling
 * No Hard-Reboots
 * Graphics
 * Storage

### What's not working:

 * Battery meter
 * WI-FI
 * Camera not showing in Launcher
 
### What is not tested:

 * SIM1/2 RIL [Data Connection and Calls] (Not tested)
 * Camera (Not tested)
 * HWComposer (Not tested)

### Thanks to:

 * Pablito2020
 * pawitp
 * dhacker29
 * sultanxda
 * chrmhoffmann
 * kashifmin
 * andreya108
 * andr7e
