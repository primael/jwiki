# jwiki
[![Build Status](https://travis-ci.org/fastily/jwiki.svg?branch=master)](https://travis-ci.org/fastily/jwiki)
![JDK-1.8+](https://upload.wikimedia.org/wikipedia/commons/7/75/Blue_JDK_1.8%2B_Shield_Badge.svg)
[![MediaWiki 1.27+](https://upload.wikimedia.org/wikipedia/commons/2/2c/MediaWiki_1.27%2B_Blue_Badge.svg)](https://www.mediawiki.org/wiki/MediaWiki)
[![License: GPL v3](https://upload.wikimedia.org/wikipedia/commons/8/86/GPL_v3_Blue_Badge.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)

Programmatically accessing [Wikipedia](https://en.wikipedia.org/wiki/Main_Page)/[MediaWiki](https://www.mediawiki.org/wiki/MediaWiki) via the [API](https://en.wikipedia.org/w/api.php) is hard ☹️.  I thought it didn't have to be, so I made it easy 😀.  jwiki lets you perform all sorts of crazy API calls with 1️⃣ line of Java.  

Yes, **one** line.  

It's so easy that _anyone_ (including your grandma 👵🏻) can write an application that works with MediaWiki.

Not convinced?  Try out the [examples](https://github.com/fastily/jwiki/wiki/Examples).

## Download
jwiki is [on jcenter](https://bintray.com/fastily/maven/jwiki).

#### Maven
```xml
<dependency>
  <groupId>fastily</groupId>
  <artifactId>jwiki</artifactId>
  <version>1.5.0</version>
  <type>pom</type>
</dependency>
```

#### Gradle
```groovy
compile 'fastily:jwiki:1.5.0'
```

## Build
Build and publish jwiki on your local machine with
```bash
./gradlew build publishToMavenLocal
```

## Resources
* [Examples](https://github.com/fastily/jwiki/wiki/Examples)
* [Javadocs](https://fastily.github.io/jwiki/docs/jwiki/)

## Feedback
Please use [issues](https://github.com/fastily/jwiki/issues) for bug reports and/or feature requests.  If you like jwiki and find it useful, please give it a ⭐ on GitHub!