Downloads JDK & JRE from download.oracle.com by first walking possible combinations of available version/build numbers.
Once a version/build is found, subsequent attempts in the same family are primed to avoid walking the entire tree again.
 
version=<x> represents the highest attempted version number while walking the tree.
build=<y> represents the highest attempted build number while walking the tree.

Adjust "BASE" to control which versions are downloaded.  A value of 8 corresponds to Java-v1.8.x
Likewise a value of "6 7 8" equates to Java-v1.6.x, Java-v1.7.x, Java-v1.8.x

Adjust "PLATFORMS" to match the architecture platforms you wish to download.

Reference URLS:
https://gist.github.com/P7h/9741922
http://download.oracle.com/otn-pub/java/jdk/8u40-b26/jre-8u40-windows-x64.exe
http://download.oracle.com/otn-pub/java/jdk/8u40-b27/jdk-8u40-macosx-x64.dmg



