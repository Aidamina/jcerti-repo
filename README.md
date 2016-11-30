# jcerti-repo

Mavenized build and repo for jcerti

https://github.com/Aidamina/jcerti

http://savannah.nongnu.org/git/?group=certi

For users of the jcerti library see:

https://github.com/Aidamina/jcerti/wiki


# Developers

Info below is for developers of the jcerti plugin

To run the build setup your github credentials in your maven settings.xml

https://github.github.com/maven-plugins/site-plugin/authentication.html

then run `mvn deploy` to trigger a build and deploy cycle

To do a test run use: 
`mvn clean deploy -Dgithub.site.dryRun=true`



