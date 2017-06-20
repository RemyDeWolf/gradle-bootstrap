# gradle-bootstrap
Provide minimum files to create a gradle project from scratch.



Uses the “application” plugin to produce a command-line application implemented using Java, use JUnit.

    ./gradlew init --type java-application

Use a different test framework

    ./gradlew init --type java-application --test-framework spock
    ./gradlew init --type java-application --test-framework testng

Uses the “java” plugin to produce a library Jar , use JUnit.

    ./gradlew init --type java-library

    ./gradlew init --type java-library --test-framework spock
    ./gradlew init --type java-library --test-framework testng

Uses the “scala” plugin to produce a library Jar, use ScalaTest.

    ./gradlew init --type scala-library

Uses the groovy plugin to produce a groovy-application, use Spock.

    ./gradlew init --type groovy-application

Uses the groovy plugin to produce a groovy-library, use Spock.

    ./gradlew init --type groovy-library

