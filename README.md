Atomic-OS
==================

Getting Started
---------------
To initialize your local repository using the our trees, use a command like this:

    repo init -u https://github.com/namdeptrai2003/platform_manifest-6.git -b n-mr2

Then to sync up:
---------------
    repo sync --force-sync --force-broken --no-clone-bundle -jxxx (ur choice dude)


Finally to build:
-----------------

```bash
  . build/envsetup.sh
  lunch aos_devicecodename-userdebug
  mka atomic
```
Credits
-------
* [**AOSP-JDC (Base)**](https://github.com/AOSP-JF-MM)
* [**LineageOS**](https://github.com/LineageOS)
* [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
* [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)
* [**SlimRoms**](https://github.com/SlimRoms)
* [**Nitrogen Project**](https://github.com/nitrogen-project)
* [**Pure Nexus**](https://github.com/PureNexusProject)
* [**OmniROM**](https://github.com/omnirom/)

