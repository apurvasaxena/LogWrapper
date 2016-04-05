
Step 1. Add it in your root build.gradle at the end of repositories:
	allprojects {
		repositories {
			maven { url "https://jitpack.io" }
		}
	}
	
Step 2. Add the dependency
	dependencies {
	        compile 'com.github.apurvasaxena:LogWrapper:1.0.1'
	}


In your activity/fragment:
LogWrapper.v("I am priniting this");
