

# Animated Bottom Bar


## What is this component about?

This component that mimics the new Animated Bottom Bar with sleek animations.

**(currently under active development, expect to see new releases almost daily)**

## Features

* This library offers ton of customisations that you can do to Bottom Navigation Bar.
* Choose your background style and tab mode.
* each tab has it's own colors
* supports badges with complete customization

## Download

Based on your IDE you can import library in one of the following ways

Download [the latest JAR][mavenAarDownload] or grab via Maven:

```xml
<dependency>
  <groupId>com.ashokvarma.android</groupId>
  <artifactId>bottom-navigation-bar</artifactId>
  <version>2.2.0</version>
  <type>pom</type>
</dependency>
```
or Gradle:
```groovy
implementation 'com.ashokvarma.android:bottom-navigation-bar:2.2.0'
```
or Ivy:
```xml
<dependency org='com.ashokvarma.android' name='bottom-navigation-bar' rev='2.2.0'>
  <artifact name='$AID' ext='pom'/>
</dependency>
```

## Migration from V1 to V2
1. BadgeItem has been changed to TextBadgeItem
2. New ShapeBadgeItem implementation changed.
3. hideText replaced with new modes. To use those mode should be set to MODE_FIXED_NO_TITLE / MODE_SHIFTING_NO_TITLE 

