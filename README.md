# EditPhoto

android library EditPhoto. Image Editor for Android


# Demo 

[<img src="https://lh3.googleusercontent.com/18yJQaRq3oWz_04_gkpD5t_hLHVWDN3FsNSXDfU4bFYcJg9nr5msqUBrG2EgN8v7Bg=h512">]

# Project

Icon | Name | Link Google Play
------------ | ------------ | -------------
[<img src="/store/ic_launcher.png">](https://play.google.com/store/apps/details?id=com.hoanganhtuan95ptit.camdoc_productivity) | [CamDoc - Document Scanner, PDF Scanner App 2018](https://play.google.com/store/apps/details?id=com.hoanganhtuan95ptit.camdoc_productivity) | [<img src="/store/Store.png">](https://play.google.com/store/apps/details?id=com.hoanganhtuan95ptit.camdoc_productivity)


# ️Features 
* Crop with 
```java
((EditPhotoActivity) getActivity()).addFragmentToStack(CropFragment.create(inputUrl, this));
```
* Filter with 
```java
((EditPhotoActivity) getActivity()).addFragmentToStack(FilterFragment.create(inputUrl, this));
```
* Rotate with 
```java
((EditPhotoActivity) getActivity()).addFragmentToStack(RotateFragment.create(inputUrl, this));
```
* Saturation with 
```java
((EditPhotoActivity) getActivity()).addFragmentToStack(SaturationFragment.create(inputUrl, this));
```
* Brightness with 
```java
((EditPhotoActivity) getActivity()).addFragmentToStack(BrightnessFragment.create(inputUrl, this));
```
* Contrast with 
```java
((EditPhotoActivity) getActivity()).addFragmentToStack(ContrastFragment.create(inputUrl, this));
```


# Download

* Step 1. Add it in your root build.gradle at the end of repositories:
```java
    allprojects {
        repositories {
          ...
          maven { url 'https://jitpack.io' }
        }
    }
```
* Step 2. Add the dependency
```java
    dependencies {
        compile 'com.github.hoanganhtuan95ptit:EditPhoto:1.0.1'
    }
```

# Using

* Java

```java
        switch (type) {
            case Crop:
                ((EditPhotoActivity) getActivity()).addFragmentToStack(CropFragment.create(inputUrl, this));
                break;
            case Filter:
                ((EditPhotoActivity) getActivity()).addFragmentToStack(FilterFragment.create(inputUrl, this));
                break;
            case Rotate:
                ((EditPhotoActivity) getActivity()).addFragmentToStack(RotateFragment.create(inputUrl, this));
                break;
            case Saturation:
                ((EditPhotoActivity) getActivity()).addFragmentToStack(SaturationFragment.create(inputUrl, this));
                break;
            case Brightness:
                ((EditPhotoActivity) getActivity()).addFragmentToStack(BrightnessFragment.create(inputUrl, this));
                break;
            case Contrast:
                ((EditPhotoActivity) getActivity()).addFragmentToStack(ContrastFragment.create(inputUrl, this));
                break;
        }
```
# Thank 

 Name | Library
------------ | -------------
Yalantis | [UCrop](https://github.com/Yalantis/uCrop) 
