# StepProgressBar
A progressbar with plurality of nodes

## How to use
To get a Git project into your build:

### Step 1. Add the JitPack repository to your gradle build file

Add it in your root build.gradle at the end of repositories:
```java
	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```
### Step 2. Add the dependency
```java
	dependencies {
	        compile 'com.github.kangyang1024:StepProgressBar:1.3'
	}
```

### Step 3. in your XXX.xml
```xml
	<com.cabana.stepprogressbar.StepProgressBar
        	android:id="@+id/StepProgressBar"
        	android:layout_width="match_parent"
        	android:layout_height="wrap_content"
        	android:layout_centerInParent="true"
        	StepProgressBar:self_adaptation="true"/>
```

the screenshot 
<p><img src="https://github.com/kangyang1024/StepProgressBar/blob/master/device-2016-08-07-172541.png" width = "324" height = "576" alt="srceenshot" align=center /img></p>
