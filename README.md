# etracker-app-analytics

This repository privides the Android library for etracker App Analytics.

## Installation

First, you have to add this repository to your `build.gradle` file:

```groovy
repositories {
	maven {
		url uri("https://maven.pkg.github.com/etracker/etracker-app-analytics-android")
		credentials {
			username = System.getenv("GITHUB_USERNAME")
			// github personal access token with packages read access
			password = System.getenv("GITHUB_TOKEN")
		}
	}
}
```

Please note that you have to provide your GitHub username and a personal access token with packages read access as environment variables since Github does not allow anonymous access to packages.

Then you can add the library to your dependencies like this:

```groovy
dependencies {
	implementation 'com.etracker:etracker-app-analytics:2.6.0'
}
```

## License

etracker-app-analytics is available under the MIT license. See the LICENSE file for more info.
