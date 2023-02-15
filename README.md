# javafx11-archetype
Maven archetype to create JavaFX applications with Java 11

Here are the instructions to publish the archetype on Maven:

STEP 1 (GitHub repo)
- update the archetype as you need
- make sure to update the external "pom.xml" file by increasing the version number in:
    * <version>X.Y.Z</version>
    * <tag>tdp-javafx-archetype-X.Y.Z</tag>
- commit and push the repo

STEP 2
- open the terminal, go the the project folder, and type "mvn clean deploy"

