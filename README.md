# Motion Toast - A Beautiful Toast Library for Android Kotlin 🤩🔥 

[![platform](https://img.shields.io/badge/platform-Android-yellow.svg)](https://www.android.com)
[![API](https://img.shields.io/badge/API-21%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=21)
[![GitHub license](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![GitHub stars](https://img.shields.io/github/stars/SpikeySanju/MotionToast?style=social)
![GitHub forks](https://img.shields.io/github/forks/SpikeySanju/MotionToast?label=Fork&style=social)
![Repo size](https://img.shields.io/github/repo-size/SpikeySanju/MotionToast?style=social)
![GitHub follow](https://img.shields.io/github/followers/SpikeySanju?label=Follow&style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/sanjay_spikey?label=Twitter&style=social)


A Beautiful Multipurpose Motion Toast Library in Android using Kotlin 😍

![GitHub Cards Preview](https://github.com/Spikeysanju/Video_templates/blob/master/Github%20Card.png)

## Preview - Motion Toast 🌟 
![gif](https://github.com/Spikeysanju/Video_templates/blob/master/Motion%20Toast.gif)

## Preview - Color Motion Toast 🌈
![gif](https://github.com/Spikeysanju/Video_templates/blob/master/Toast%20Types-5.png)

## Preview - Dark Toast 🌈
![gif](https://github.com/Spikeysanju/Video_templates/blob/master/Dark%20Toast.png)

## Preview - Dark Color Toast 🌈
![gif](https://github.com/Spikeysanju/Video_templates/blob/master/Dark%20Color%20Toast.png)


# Types of Toast Style ❤️


<table style="width:100%">
  <tr>
    <th>1. Motion Toast </th>
    <th>2. Color Motion Toast</th> 
    <th>3. Dark Toast </th>
    <th>4. Dark Color Toast</th> 
  </tr>
  <tr>
    <td><img src = "https://github.com/Spikeysanju/Video_templates/blob/master/Toast%20Types-3.png"/></td> 
    <td><img src = "https://github.com/Spikeysanju/Video_templates/blob/master/Toast%20Types-5.png"/></td>
    <td><img src = "https://github.com/Spikeysanju/Video_templates/blob/master/Dark%20Toast.png"/></td> 
    <td><img src = "https://github.com/Spikeysanju/Video_templates/blob/master/Dark%20Color%20Toast.png"/></td> 
   
  </tr>
</table>

## About

A Beautiful Multipurpose Motion Toast Library in Android using Kotlin. 

## Dependency Project Level

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:



```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

```

## Dependency App Level

Add dependency in your app module

```
	dependencies {
	        implementation 'com.github.Spikeysanju:MotionToast:1.3.2' 
	}

```
## Five Toast Types 🖐🏼
```
        1. TOAST_SUCCESS
        2. TOAST_ERROR
        3. TOAST_WARNING
        4. TOAST_INFO
        5. TOAST_DELETE
```

## Toast Duration ⌛️ 
```
        1. LONG_DURATION // 4 Seconds
        2. SHORT_DURATION // 2 Seconds
       
```

## Usage 

# Sample Code for - Motion Toast 🌟 

### Success Toast
```
 MotionToast.createToast(this,"Upload Completed!",
                MotionToast.TOAST_SUCCESS,
                MotionToast.GRAVITY_BOTTOM,
                MotionToast.LONG_DURATION,
                ResourcesCompat.getFont(this,R.font.helvetica_regular))
                
```

### Error Toast
```
 MotionToast.createToast(this,"Profile Update Failed!",
                    MotionToast.TOAST_ERROR,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  
```
### Warning Toast
```
MotionToast.createToast(this,"Please fill all the details!",
                    MotionToast.TOAST_WARNING,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

        
```

### Info Toast
```
       MotionToast.createToast(this,"This is information toast!",
                    MotionToast.TOAST_INFO,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```
### Delete Toast
```
       MotionToast.createToast(this,"Delete all history!",
                    MotionToast.TOAST_DELETE,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```

# Sample Code for - Color Motion Toast 🌈

### Success Toast
```
 MotionToast.createColorToast(this,"Upload Completed!",
                MotionToast.TOAST_SUCCESS,
                MotionToast.GRAVITY_BOTTOM,
                MotionToast.LONG_DURATION,
                ResourcesCompat.getFont(this,R.font.helvetica_regular))
                
```

### Error Toast
```
 MotionToast.createColorToast(this,"Profile Update Failed!",
                    MotionToast.TOAST_ERROR,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  
```
### Warning Toast
```
MotionToast.createColorToast(this,"Please fill all the details!",
                    MotionToast.TOAST_WARNING,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

        
```

### Info Toast
```
       MotionToast.createColorToast(this,"This is information toast!",
                    MotionToast.TOAST_INFO,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```
### Delete Toast
```
       MotionToast.createColorToast(this,"Delete all history!",
                    MotionToast.TOAST_DELETE,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```

# Sample Code for - Dark Toast 🌚🖤 

### Success Toast
```
 MotionToast.darkToast(this,"Upload Completed!",
                MotionToast.TOAST_SUCCESS,
                MotionToast.GRAVITY_BOTTOM,
                MotionToast.LONG_DURATION,
                ResourcesCompat.getFont(this,R.font.helvetica_regular))
                
```

### Error Toast
```
 MotionToast.darkToast(this,"Profile Update Failed!",
                    MotionToast.TOAST_ERROR,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  
```
### Warning Toast
```
MotionToast.darkToast(this,"Please fill all the details!",
                    MotionToast.TOAST_WARNING,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

        
```

### Info Toast
```
       MotionToast.darkToast(this,"This is information toast!",
                    MotionToast.TOAST_INFO,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```
### Delete Toast
```
       MotionToast.darkToast(this,"Delete all history!",
                    MotionToast.TOAST_DELETE,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```

# Sample Code for - Dark Color Toast 🌚🖤🌈

### Success Toast
```
 MotionToast.darkColorToast(this,"Upload Completed!",
                MotionToast.TOAST_SUCCESS,
                MotionToast.GRAVITY_BOTTOM,
                MotionToast.LONG_DURATION,
                ResourcesCompat.getFont(this,R.font.helvetica_regular))
                
```

### Error Toast
```
 MotionToast.darkColorToast(this,"Profile Update Failed!",
                    MotionToast.TOAST_ERROR,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  
```
### Warning Toast
```
MotionToast.darkColorToast(this,"Please fill all the details!",
                    MotionToast.TOAST_WARNING,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

        
```

### Info Toast
```
       MotionToast.darkColorToast(this,"This is information toast!",
                    MotionToast.TOAST_INFO,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```
### Delete Toast
```
       MotionToast.darkColorToast(this,"Delete all history!",
                    MotionToast.TOAST_DELETE,
                    MotionToast.GRAVITY_BOTTOM,
                    MotionToast.LONG_DURATION,
                    ResourcesCompat.getFont(this,R.font.helvetica_regular))  

```


# Donation
If this project help you reduce time to develop, you can give me a cup of coffee :) 

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/paypalme2/spikeysanju)


## License
```
MIT License

Copyright (c) 2020 Spikey Sanju

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
