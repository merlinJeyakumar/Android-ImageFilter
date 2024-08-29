<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037638/90bc848c-d396-11e5-98d0-572a3e902576.png">
</p>

# Image Filters

![](https://img.shields.io/badge/Platform-Android-brightgreen.svg)
![](https://img.shields.io/crates/l/rustc-serialize.svg)
![](https://img.shields.io/badge/version-0.1.2_beta-blue.svg)

------ 
Image Filter is an Android Libary that lets you to Filtering any image.
You can report any issue on issues page. **Note: If you speak Arabic, you can submit issues with Arabic language and I will check them. :)**

## Fork of net.alhazmy13.ImageFilters

## Installation
------
Download AAR > https://github.com/merlinJeyakumar/Android-ImageFilter/releases/tag/version_next

# Usage
------ 
All you need is to pass a `Bitmap` obejct and the filter type
```java
       ImageFilter.applyFilter(bitmap, ImageFilter.Filter.GOTHAM);
```
## Filter types
### Gray
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037677/6060dfe4-d397-11e5-8d50-0cf960914a8b.png" width="200">
</p>
```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.GRAY);
```

### Relief
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037676/605da3c4-d397-11e5-93cb-22a4895e59e2.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.RELIEF);
```

### Average blur
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037708/0cb05126-d398-11e5-9b70-09cc415ac791.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.AVERAGE_BLUR,BLUR_SIZE);
```

### OIL
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037707/0cafb996-d398-11e5-9610-48467208441b.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.OIL);
```

### NEON
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037747/b98cf624-d398-11e5-8b46-88bd6b85ddf4.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.NEON,COLOR_R,COLOR_G,COLOR_B);
```

### Pixelate
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037748/b9958280-d398-11e5-9152-da23c247d87c.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.PIXELATE,PIXEL_SIZE);
```

### TV
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037746/b98875ae-d398-11e5-8c10-421667e3a624.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.TV);
```

### Invert Color
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037744/b929e188-d398-11e5-9064-da0939ae1f77.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.INVERT);
```

### Block
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037745/b9855cd4-d398-11e5-8369-62544c531134.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.BLOCK);
```

### Old
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037798/d89c4fbe-d399-11e5-978a-098ac7b80215.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.OLD);
```

### Sharpen
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13060884/9f46da0c-d445-11e5-99f3-f94d6c836109.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.SHARPEN);
```

### Light
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13060890/9f761970-d445-11e5-9408-ae8463c713b3.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.LIGHT,CENTER_X,CENTER_Y,RADIUS);
```

### Lomo
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13060883/9f17e6a2-d445-11e5-8db1-351e21827df3.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.LOMO);
```

### HDR
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13060889/9f6f41ea-d445-11e5-91f6-cddf9f2e01c1.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.HDR);
```

### Gaussian Blur
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13060887/9f6e3c5a-d445-11e5-9e01-edf3022ef59d.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.GAUSSIAN_BLUR,SIGMA);
```

### Soft Glow
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13060885/9f6af842-d445-11e5-9725-9bcdf7699ea4.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.SOFT_GLOW);
```

### Sketch
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13060888/9f6eb130-d445-11e5-9a7a-e052213aad38.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.SKETCH);
```

### Motion Blur
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13060886/9f6c03a4-d445-11e5-9771-36bf3e20591f.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.MOTION_BLUR,X,Y);
```

### Gotham
<p align="left">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13037688/af70d198-d397-11e5-824b-17fc4035ac80.png" width="200">
  <img src="https://cloud.githubusercontent.com/assets/4659608/13060882/9ee4bcb4-d445-11e5-8521-4f6b0080a7c6.png" width="200">
</p>

```java
ImageFilter.applyFilter(bitmap, ImageFilter.Filter.GOTHAM);
```

## Credits 
* [Jhlabs](http://www.jhlabs.com/ip/filters/)  
* [NDK Image Filters](https://github.com/ragnraok/android-image-filter)
* [OpenCV](http://docs.opencv.org/2.4/modules/imgproc/doc/filtering.html)

## License
------ 
    Copyright 2015 alhazmy

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    

