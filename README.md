
Example repository for Gradle project with Nexus publishing configuration.

To publish:
1. ```mv example_gradle.properties gradle.properties```
2. fill gradle.properties with username and password of user enabled to publish on Nexus
3. build with ```./gradlew build clean```
4. publish with ```./gradlew publish```