eclipse-icon-enlarger
=====================

Scales Eclipse icons (PNG and GIF) to double their size for QHD laptops.

Maven
==============

This is an [Apache Maven](http://maven.apache.org/) project and can be built (after installation of maven) using the following command
	
	mvn clean install

This will produce (by default; on windows):

	$HOME\.m2\repository\davidlevy\eclipse-icon-enlarger\0.0.1-SNAPSHOT\eclipse-icon-enlarger-0.0.1-SNAPSHOT.jar

Which can then be run:

	java -jar eclipse-icon-enlarger-0.0.1-SNAPSHOT.jar <eclipse install directory>
