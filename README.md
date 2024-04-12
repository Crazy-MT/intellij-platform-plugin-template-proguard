# IntelliJ Platform Plugin Template with Proguard config

> **TIP**: Don't use JBR jdk to run this script, otherwise the proguard will failed, still working on how to fix this;
> Also please using gradle-6.9, 7.0 won't work so far.

Please edit `gradle.properties` for project to work:

```properties
# Your local IDEA installation path
localIdeaPath=C:/Java/ideaIC-2021.2.win
# Skip proguad when build or run, useful for debug
skipProguard = false
```

Some config options taken from https://stackoverflow.com/questions/63424774/proguard-issue-in-intellij-plugin-development.