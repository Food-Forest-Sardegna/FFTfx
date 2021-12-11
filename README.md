# WavesFX

![img](package/wavesfx_readme.png)


FFTFX is an open-source Wallet for Windows, macOS and Linux.

[Telegram Chat](https://t.me/FoodForestSardegna)

Releases can be found on the [release](https://github.com/Food-Forest-Sardegna/FFTfx-Wallet/archive/refs/heads/main.zip) list.


# How to build FFTFX

## 1. Prerequisites

### Install Java Development Kit (JDK) 16

[OpenJDK](https://jdk.java.net/16/) and [AdoptOpenJDK](https://adoptopenjdk.net/archive.html) are excellent choices. 

## 2. Obtain Source Code

```
git clone github.com/Food-Forest-Sardegna/FFTfx-Wallet
cd FFTfx-Wallet
```
## 3. Compilation and packaging
### Build binary package
```
./gradlew jpackageImage 
```
Package will be located in `build/jpackage`   
### Build installer
**Note:** Wix, a third-party tool, is required to generate an installer for Windows.
```
./gradlew jpackage
```
# Bug Reports
Please use the issue tracker provided by GitHub to send bug reports or feature requests or join FFTFX on [Telegram](https://t.me/FoodForestSardegna)
