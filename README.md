[ ![Download](https://api.bintray.com/packages/lemarit/lemarit/dnsjava/images/download.svg) ](https://bintray.com/lemarit/lemarit/dnsjava/_latestVersion)

# A fork of the dnsjava project

This repository contains a fork of the [dnsjava](https://sourceforge.net/projects/dnsjava/) project, based on the [github mirror](https://github.com/dnsjava/dnsjava/) of the project.

## Setup

To make use of this project you have to add the following repository to your build.gradle File:

```
repositories {
	maven { url "https://dl.bintray.com/lemarit/lemarit" }
}
```

Afterwards you can simply add the dependency with this line:

```
compile 'com.lemarit:dnsjava:2.1.9'
```
