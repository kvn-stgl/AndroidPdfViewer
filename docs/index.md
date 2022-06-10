## Android PDF Viewer

This is a fork of [TalbotGooday/AndroidPdfViewer](https://github.com/TalbotGooday/AndroidPdfViewer). Since the original one is not maintained, I forked this and added some customizations I need like [this one](https://github.com/muthuraj57/AndroidPdfViewer/commit/1b5e635f3eea5d9b4e55cdaa26c4c740058b6b5a).

## Installation

Add to _build.gradle_:
```groovy
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```
Add the dependency
```groovy
implementation 'com.github.muthuraj57:AndroidPdfViewer:Tag'
```
