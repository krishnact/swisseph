# swisseph
This is just just a copy of swisseph-2.01.00-java-src-01.zip from http://th-mack.de/international/download/.

The license seems to pretty open. Please visit http://th-mack.de/international/download/ to see small license related text.

I put it so that it is possible to use this package with maven. 
How to use?

Add jitpack repostitory in your pom.xml:
```xml
	<repositories>
		<repository>
			<id>jitpack.io</id>
			<url>https://jitpack.io</url>
		</repository>
	</repositories>
```
And then add dependency:
```xml
		<dependency>
			<groupId>com.github.krishnact</groupId>
			<artifactId>swisseph</artifactId>
			<version>-SNAPSHOT</version>
		</dependency>
```
