# AndroidBug5497Workaround

AndroidBug5497Workaround解决方案(改良, 修复Bug, 增加是否监听调整)

<pre>
WorkAround workAround = new WorkAround(this);
workAround.addOnGlobalLayoutListener(); // 添加监听
workAround.reMoveOnGlobalLayoutListener(); // 取消监听</pre>

How to

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

gradle
maven
sbt
leiningen
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}Copy
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.Deepblue1996:AndroidBug5497Workaround:1.0'
	}
