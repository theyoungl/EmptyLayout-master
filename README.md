Step 1. AAdd it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}Copy
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.mraben:EmptyLayout:v1.0'
	}
