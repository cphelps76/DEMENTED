![demented](https://cloud.githubusercontent.com/assets/2730592/15449450/c0d25a0e-1f43-11e6-9c5f-113eec62807f.png)

DEMENTED AOSP 6.0

Sync and Build:
---------------

In terminal enter:

    {x}   repo init -u git://github.com/cphelps76/DEMENTED_manifest.git -b mm6.0
    {x}   repo sync
    {x}   prebuilts/misc/linux-x86/ccache/ccache -M 50G
    {x}   . build/envsetup.sh && brunch "device"

Devices Currently Supported:
----------------------------

This list is always subject to change:

    {x}   find7
    {x)   flo
