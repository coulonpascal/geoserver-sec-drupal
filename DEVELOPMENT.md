Notes to document the development process
=========================================

Creating a new release
----------------------

Steps to create a new release:

* Set the version number in pom.xml (Node /project/version)
* Commit the changed pom.xml
* Run `./build-jar.sh` to build the new release JAR
* Create a tag for this version number in git
* Push the commit and the tag to github.
* Provide a download for the JAR file
