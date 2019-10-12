[![platform](https://img.shields.io/badge/platform-android-green.svg )](http://developer.android.com/index.html)
[![Android Arsenal]( https://img.shields.io/badge/Android%20Arsenal-Material--Resources--Library-green.svg?style=flat )]( https://android-arsenal.com/details/1/7688)
[![JitPack](https://img.shields.io/github/tag/asyl/ArcAnimator.svg?label=maven)](https://jitpack.io/#mohammadima3oud/Material-Resources-Library)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![API](https://img.shields.io/badge/API-19%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=19)


<table>
	<tbody>
		<tr>
			<td align="center">Timer UI</td>
			<td align="center">Login UI</td>
            <td align="center">Fitness UI</td>
		</tr>
		<tr>
			<td align="center">
				<img src="Images/Timer UI.jpg" alt="Timer UI"/>
			</td>
			<td align="center">
				<img src="Images/Login UI.jpg" alt="Login UI"/>
			</td>
			<td align="center">
				<img src="Images/Fitness UI.jpg" alt="Fitness UI"/>
			</td>
		</tr>
	</tbody>
</table>

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
    implementation 'com.github.mohammadima3oud:Material-Resources-Library:1.0.0'
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

## Checkout My Libraries

* **[Android-Intent-Library](https://github.com/mohammadima3oud/Android-Intent-Library):** A library which will save you a lot of time from writing the same intent creation code. it consist of many intent creation codes like Share, Contacts, Email and etc, which you can easily use.
* **[Material-Resources-Library](https://github.com/mohammadima3oud/Material-Resources-Library):** A list of most useful resources for designing android apps such as all material colors and dimens, 180 Gradient background + html, social, flat, fluent, metro colors.
* **[Complete-Google-Map-API-Tutorial](https://github.com/mohammadima3oud/Complete-Google-Map-API-Tutorial):** Learn How to use Google Map API for Android from Basic to Advance with complete examples.
* **[DropSignIn](https://github.com/mohammadima3oud/DropSignIn):** Sign In UI Design
* **[BlueSignIn](https://github.com/mohammadima3oud/BlueSignIn):** Sign In and Sign Up Ui Design

## Donations

This project needs you! If you would like to support this project's further development, the creator of this project or the continuous maintenance of this project, feel free to donate. Your donation is highly appreciated. Thank you!

**PayPal**

* **[Donate $5](https://www.paypal.me/mohammadima3oud/5)**: Thank's for creating this project, here's a tea (or some juice) for you!
* **[Donate $10](https://www.paypal.me/mohammadima3oud/10)**: Wow, I am stunned. Let me take you to the movies!
* **[Donate $15](https://www.paypal.me/mohammadima3oud/15)**: I really appreciate your work, let's grab some lunch!
* **[Donate $25](https://www.paypal.me/mohammadima3oud/25)**: That's some awesome stuff you did right there, dinner is on me!
* **[Donate $50](https://www.paypal.me/mohammadima3oud/50)**: I really really want to support this project, great job!
* **[Donate $100](https://www.paypal.me/mohammadima3oud/100)**: You are the man! This project saved me hours (if not days) of struggle and hard work, simply awesome!
* **[Donate $2799](https://www.paypal.me/mohammadima3oud/2799)**: Go buddy, buy Macbook Pro for yourself!

Of course, you can also choose what you want to donate, all donations are awesome!


## Changelog
* **1.0.0**
    * Initial release


## License

    Copyright 2019 mohammadima3oud

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
