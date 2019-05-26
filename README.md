# Material-Resources-Library
A list of most useful resources for designing android apps such as all material colors and dimens, 180 Gradient background + html, social, flat,fluent, metro colors.
you can use colors with java, kotlin, xml.


## What does this library include?
* All Material Colors (https://www.materialui.co/colors)
* All Flat Colors (https://www.materialui.co/flatuicolors)
* All Social Colors (https://www.materialui.co/socialcolors)
* All Material Dimens
* All HTML Colors (https://www.materialui.co/htmlcolors)
* All Fluent Colors (https://fluentcolors.com)
* All Metro Colors (https://www.materialui.co/metrocolors)
* 19 Material Gradient Background
* All WebGradient Gradient Backgrounds (https://webgradients.com/)
* 100+ Material Themes(Styles) that are divided into Light, Dark, FullScreen and NoActionBar styles


## How to include
Add the repository to your project **build.gradle**:

```Gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```

And add the library to your module **build.gradle**:

```Gradle
dependencies {
    implementation 'com.github.ma3udmohammadi:Material-Resources-Library:1.0.0'
}
```

## Usage

* ### Material Colors:
  [material][color name]
  ```
  materialOrange50
  materialOrange100
  ...
  materialOrange200
  materialOrange900
  ```
  
  ```
  materialOrangeA100
  materialOrangeA200
  materialOrangeA300
  materialOrangeA400
  ```
  
  ```
  materialPrimaryOrange
  materialPrimaryDarkOrange
  materialAccentOrange
  ```
  
  Example:
  ```
  android:background="@color/materialOrange500"
  ```

* ### Flat Colors:
  [flat][color name]
  ```
  flatTurquoise
  flatGreensea
  ...
  flatConcrete
  flatAsbestos
  ```
  
  Example:
  ```
  android:background="@color/flatAmethyst"
  ```
* ### Fluent Colors:
  [fluent][color name]
  ```
  fluentFFB900
  fluentFF8C00
  ...
  fluent847545
  fluent7E735F
  ```
  
  Example:
  ```
  android:background="@color/fluent00B7C3"
  ```
  
* ### Social Colors:
  [social][color name]
  ```
  socialFacebook
  socialMessenger
  ...
  socialTwitter
  socialLinkedIn
  ```
  
  Example:
  ```
  android:background="@color/socialDribble"
  ```
  
* ### Metro Colors:
  [metro][color name]
  ```
  metroLime
  metroGreen
  ...
  metroMauve
  metroSienna
  ```
  
  Example:
  ```
  android:background="@color/metroAmber"
  ```
  
* ### HTML Colors:
  [html][color name]
  ```
  htmlGainsboro
  htmlLightGray
  ...
  htmlSilver
  htmlDarkGray
  ```
  
  Example:
  ```
  android:background="@color/htmlAquamarine"
  ```
  
* ### Themes:
  [AppTheme][color name](Dark)(.)(NoActionBar)
  ```
  AppThemeRed
  AppThemeRed.NoActionBar
  AppThemeRedDark
  AppThemeRedDark.NoActionBar
  ...
  ```
  Example:
  ```
  inside androidManifest.xml
  android:theme="@style/AppThemeAmber"
  ```
  
* ### Dimens:
  Example:
  ```
  android:textSize="@dimen/typography_headline"
  ```

## Changelog
* **1.0.0**
    * Initial release


## License

    Copyright 2019 ma3udmohammadi

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
