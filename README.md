# Android Canvas
![alt text](https://github.com/rshavinda/android-canvas/blob/main/Images/canvas_cover.png)

♘ Android `values` directory files can be defined both as standard resources (under res/values/), as well as direct values supplied for mappings (in styles, themes and attributes in XML files such as layouts). Here are some standard dimensions, color codes for use in Android app development. 

---
## 1) color.xml
Themable, flexible color ramps for design applications.
   - **➤ Color - Style - Material Design** <br/>
   [Material Design](https://material.io/) is a cross-platform design system from ***Google***, and it is the design system for Android.
     > Out of color ideas?   <br/>
     > [Material Design Color Palette](https://material.io/resources/color/) will assist you quickly decide which color to choose for your project. 
       <br/>
   - [x] **Or add [colour.xml](https://github.com/rshavinda/android-canvas/blob/main/Color/Material%20Design/color.xml) file in the** `res/values` **folder of your project to easily work with standard color formats (All Color Codes from Google's Material design color palette).**


      ![alt text](https://github.com/rshavinda/android-canvas/blob/main/Images/material_colours.png)
<br/>

   - **➤ Color Library** <br/>
   [HTML Color Codes](https://material.io/) library features flat design colors, Google's Material design scheme and the classic web safe color palette, all with Hex color codes and color names.
        <br/>

   ![alt text](https://github.com/rshavinda/android-canvas/blob/main/Images/html_colours.png)
   
   <br/> <br/>
   - [x] **Add [colour.xml](https://github.com/rshavinda/android-canvas/blob/main/Color/Color%20Library/color.xml) file in the** `res/values` **folder of your project to work with wide range of colours.**
     
   - [x] **Or following dependencies to your android studio project** <br/>
       <br/>
        **➤ Installation Steps** <br/>
	
       **ᐅ Step 1. Add the JitPack repository to your build file** <br/>
	       *Add the following dependency to your app `build.gradle` file:*

```groovy
	allprojects {
    	   repositories {
		...
		maven { url 'https://jitpack.io' }
   	   }
	}
```
<br/> <br/>
       **ᐅ Step 2. Add the dependency** <br/>
	       *Add the following dependency to your module `build.gradle` file:*
```groovy
 	 dependencies {
    	   implementation 'com.github.rshavinda:android-color-library:1.0.0'
  	}
```
---
## 2) dimens.xml
Dimensions file which is used to define all size dimensions used within an app. A dimension is specified with a number followed by a unit of measure. For example: *10px, 5sp*. Dimensions should be defined within `res/values/dimens.xml`.

   ### - Dimensions Style #01
 The 'space' tag represent both margins and padding properties as follows,
```xml
  <resources>
       <!-- Margins and Padding -->
       <dimen name="space_xl">32dp</dimen>
       <dimen name="space_large">24dp</dimen>
       <dimen name="space_medium">16dp</dimen> 
       <dimen name="space_small">8dp</dimen>
       <dimen name="space_xs">4dp</dimen>
  </resources>
```
   - [x] **Format 01 : [dimens.xml](https://github.com/rshavinda/android-canvas/blob/main/Dimensions/Style1/Format1/dimens.xml) ( space_xs, space_xl )** <br/>
   - [x] **Format 02 : [dimens.xml](https://github.com/rshavinda/android-canvas/blob/main/Dimensions/Style1/Format2/dimens.xml) ( space_extra_small, space_extra_large )**
<br/>
<br/>

 ### - Dimensions Style #02 :
 Margins and padding properties defined in separate sections as shown below,
```xml
  <resources>
        <!-- Margins -->
        <dimen name="margin_xxl">48dp</dimen>
        <dimen name="margin_xl">32dp</dimen>
        <dimen name="margin_large">24dp</dimen>
        <dimen name="margin_medium">16dp</dimen> 
        <dimen name="margin_small">8dp</dimen>
        <dimen name="margin_xs">4dp</dimen>

        <!-- Padding -->
        <dimen name="padding_xl">32dp</dimen>
        <dimen name="padding_large">24dp</dimen>
        <dimen name="padding_medium">16dp</dimen>
        <dimen name="padding_small">8dp</dimen>
        <dimen name="padding_xs">4dp</dimen>
  </resources>
```
   - [x] **Format 01 : [dimens.xml](https://github.com/rshavinda/android-canvas/blob/main/Dimensions/Style2/Format1/dimens.xml) ( margin_xs, padding_xl )** <br/>
   - [x] **Format 02 : [dimens.xml](https://github.com/rshavinda/android-canvas/blob/main/Dimensions/Style2/Format2/dimens.xml) ( margin_extra_small, padding_extra_large )**
        

---
## MIT License

###### Copyright (c) 2021 Rajitha Shavinda

<sub>Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:<sub>

<sub>The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.<sub>

<sub>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.<sub>
