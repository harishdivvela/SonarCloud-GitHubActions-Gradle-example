# SonarCloud Github Actions with gradle
This is an example how to use SonarCloud GithubActions via gradle script.
It demonstrates how you can utilize the full feature set of Sonarcloud.io.

This repository is based on https://github.com/SonarSource/sq-com_example_java-gradle-travis

## Prequisites
1. SonarCloud.io account
2. github repository which builds with gradle

## Sonar Authentication
As we do not want to put our SonarCloud token into our repository, you should provide it
via a GitHub secret named `SONAR_TOKEN`. For more information please take a look at the
GitHub Actions Dokumentation

## Provided Actions

We provide two Actions:

- main.yml which is a single Java Version and OS build
- crossversion.yml which supports crossversion builds on multiple OS and JDK versions
