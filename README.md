# Material Colors - An Android Material Design Colors Library

An android library that provides material design colors. These colors library makes a developers work easy.

# Example

Screenshots Coming Soon!!

```xml

<TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="RED 400"
        android:padding="10dp"
        android:text_color="@color/black"
        android:background="@color/red_400"/>

```

# Getting Started

### Dependency Project Level

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:



``` groovy
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

```

### Dependency App Level

Add dependency in your app module

``` groovy

	def colors_version = "1.0.0"
	
	dependencies {
	        implementation "com.github.keithchad:materialcolors:$colors_version"
	}

```

# Special Thanks

Special Thanks goes to [Material Design Color Palette](https://www.materialpalette.com/)
