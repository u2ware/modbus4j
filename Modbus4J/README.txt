=============================================================================
Add the following snippet to any project's pom that depends on your project:

	<repositories>
	    <repository>
	        <id>bacnet4j-mvn-repo</id>
	        <url>https://raw.github.com/u2ware/modbus4j/mvn-repo/</url>
	    </repository>
	</repositories>

	<dependencies>
  		<dependency>
  			<groupId>com.infiniteautomation</groupId>
  			<artifactId>modbus4j</artifactId>
  			<version>2.1.1</version>
	  	</dependency>
	</dependencies>

reference: 
	https://github.com/github/maven-plugins
	http://stackoverflow.com/questions/14013644/hosting-a-maven-repository-on-github

enjoy!!!
=============================================================================

Build Via the Ant Targets, maven will automatically download and install libraries from web and modbus4j-maven-local repository included in project.

modbus4J.jar requires: (See pom.xml)

A discussion forum for this package can be found at http://mango.serotoninsoftware.com/forum/forums/show/11.page. 