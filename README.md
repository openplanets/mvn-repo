mvn-repo
========

Quick fix Maven repo for third party jars and prototype projects.

To use add:

```xml
  <repositories>
  <repository>
		<id>repo</id>
		<url>https://github.com/openplanets/mvn-repo/raw/master/releases</url>
	</repository>
  </repositories>

to your pom and reference the projects as:

<dependency>
  <groupId>uk.gov.nationalarchives.droid</groupId>
	<artifactId>droid-core-interfaces</artifactId>
	<version>6.0</version>
</dependency>
<dependency>
	<groupId>nz.govt.natlib.metadata-extractor</groupId>
	<artifactId>arc-adapter</artifactId>
	<version>3.5</version>
</dependency>
<dependency>
	<groupId>edu.harvard.jhove</groupId>
	<artifactId>jhove</artifactId>
	<version>1.8</version>
</dependency>
```

For more general instructions on use see http://blog.rueedlinger.ch/2012/09/use-github-as-maven-remote-repository

These aren't the original instructions but are the clearest and most up to date, for reference these are the instructions I used last year:

http://cemerick.com/2010/08/24/hosting-maven-repos-on-github/

which are more complete.