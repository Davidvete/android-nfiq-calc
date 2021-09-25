[![](https://jitpack.io/v/Davidvete/android-nfiq-calc.svg)](https://jitpack.io/#Davidvete/android-nfiq-calc)


# android-nfiq-calc
Seamfix Android SDK that is used to calculate the NFIQ of a captured fingerprint image. Project is an Android (Kotlin) implementation of a C-based NFIQ calculator found here https://github.com/lessandro/nbis

## Usage
```kotlin
NFIQUtil.calculateNFIQUsingBitmap(context: Context, bitmap: Bitmap)
```
or

```kotlin
NFIQUtil.calculateNFIQUsingRawBytes(rawBytes: ByteArray, imageWidth: Int, imageHeight: Int)

```

## Install

This repository can be found on JitPack:

https://jitpack.io/#Davidvete/android-nfiq-calc

Add it in your root build.gradle at the end of repositories:
```
allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```

Add the dependency:
```
dependencies {
	        compile 'com.github.Davidvete:android-nfiq-calc:1.2.4'
	}
```
