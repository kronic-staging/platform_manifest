### AOSiP

Get your build environment setup from https://github.com/akhilnarang/scripts
Then
```
mkdir aosip
cd aosip
repo init -u https://github.com/AOSIP/platform_manifest.git -b n-oms
repo sync
```
To build
```
. build/envsetup.sh
lunch
(Choose your device from menu)
time make -jX kronic
(X being number of threads your CPU can take)
```
Do a ```make clobber``` every once in a while
