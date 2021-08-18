# How to use this template repo

- Replace `PROJECT_NAM` and `PROJECT_DESCRIPTION` with a find and replace command.
- Replace `otlin-open-source-template` with a find and replace command.
- Replace `mylib` with a find and replace command.
- Replace `mylib` folders.

## Features

- [x] Continuous-on-demand integration and deployment to maven repository.
- [x] Documentation (with versionning) website.

# PROJECT_NAME

![JVM Continuous Integration](https://github.com/bamlab/kotlin-open-source-template/workflows/JVM%20Continuous%20Integration/badge.svg)

![JVM Continuous Deployment](https://github.com/bamlab/kotlin-open-source-template/workflows/JVM%20Continuous%20Deployment/badge.svg)

## Install

![Maven Central](https://img.shields.io/maven-central/v/tech.bam.PROJECT_NAME/PROJECT_NAME-jvm)

```groovy
implementation("tech.bam.PROJECT_NAME:PROJECT_NAME:VERSION")
```

### Snapshot releases

```groovy
repositories {
    maven { url "https://oss.sonatype.org/content/repositories/snapshots" } // Add this line
}
// ...

implementation("tech.bam.PROJECT_NAME:PROJECT_NAME:VERSION-SNAPSHOT")
```

## Usage

