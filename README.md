# Social Brain — Android releases

Public mirror for Social Brain's Android beta APK builds. The product's
source code lives in a private repository; this repo exists solely so the
release APK is downloadable by anyone visiting the landing page, without
requiring GitHub repo access.

Each release here corresponds 1:1 to a tagged release in the private source
repo, built via its `release-android.yml` CI workflow (debug-signed release
build, `apksigner`-verified before publish).

**This is a beta build**, distributed outside the Play Store. Android will
show an "install from unknown sources" warning — that's expected for any APK
not from the Play Store, not a sign anything is wrong.
