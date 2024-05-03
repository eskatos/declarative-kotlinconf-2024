# Developer-first Gradle builds

## Build

The build requires a JavaFX enabled JDK 17.

```shell
# Produce HTML slides
./gradlew :slides:asciidoctorRevealJs

# Produce HTML slides continuously
./gradlew --continuous :slides:asciidoctorRevealJs

# Produce PDF slides
./gradlew :slides:kotlinConfPdf
```
