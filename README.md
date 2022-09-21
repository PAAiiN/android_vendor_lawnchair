## Lawnchair AOSP based build system
All credits go to the [Lawnchair Team](https://github.com/LawnchairLauncher). <br/>
Quickstep enablement is done with the help of QuickSwitch Magisk module made by [Skittles9823](https://github.com/skittles9823).

## Getting started
<b>1. Clone this repository to your AOSP build root's</b>
- `git clone *link -b *branch vendor/lawnchair` * example

<b>2. Import vendor/lawnchair/lawnchair.mk</b>
- `$(call inherit-product, vendor/lawnchair/lawnchair.mk)` * inherit-product
- `$(call inherit-product-if-exists, vendor/lawnchair/lawnchair.mk)` * inherit-product-if-exists

**3. Remove existing launcher from the build**
https://github.com/psionicprjkt/android_vendor_lawnchair/blob/cca8061f88464fa4136248bd2449ebe20a374d82/Android.bp#L10
