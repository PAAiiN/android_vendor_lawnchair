# Lawnchair AOSP based build system

## Disclaimer
- All credits go to the Lawnchair team.
- Quickstep enablement is done with the help of QuickSwitch Magisk module made by [Skittles9823](https://github.com/skittles9823).

## Getting started
**1. Clone this repository to your AOSP build root's**
- git clone https://github.com/psionicprjkt/psionic-vendor_lawnchair vendor/lawnchair

**2. Import vendor/lawnchair/lawnchair.mk**
- `$(call inherit-product, vendor/lawnchair/lawnchair.mk)` * inherit-product
- `$(call inherit-product-if-exists, vendor/lawnchair/lawnchair.mk)` * inherit-product-if-exists

**3. Remove existing launcher from the build**
- Check Android.bp
- https://github.com/psionicprjkt/psionic-vendor_lawnchair/blob/7e7356939ff52294624f1c865439a3bdd7870af4/Android.bp#L10

**4. It's done, now continue your android build**
