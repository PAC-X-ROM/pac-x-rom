Credits
-------
* [**PAC-ROM**](https://github.com/PAC-ROM)
* [**JDCTeam**](https://github.com/AOSP-JF-MM)
* [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
* [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)
* [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
* [**Nitrogen Project**](https://github.com/nitrogen-project)
* [**OmniROM**](https://github.com/omnirom/)
* [**AOSPA**](https://github.com/aospa/)


How to Build?
-------------

To initialize your local repository using the PAC-X-ROM trees, use a 
command like this:

```bash
  repo init -u https://github.com/PAC-X-ROM/pac-x-rom.git -b pac-9.0
```
  
Then to sync up:
----------------

```bash
  repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
Finally to build:
-----------------

```bash
  . build/envsetup.sh
  lunch aosp_device_codename-userdebug
  mka pac -j$(nproc --all)
```

######Support Our Sites, We have created many different ways for you to follow us. Please visit us and support our work and efforts.
Links will be Up Soon

