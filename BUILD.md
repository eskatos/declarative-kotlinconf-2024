# Building the slides

The build requires a JDK 17 with JavaFX bundled.

```shell
# Produce HTML slides
./gradlew :slides:asciidoctorRevealJs

# Produce HTML slides continuously
./gradlew --continuous :slides:asciidoctorRevealJs

# Produce PDF slides
./gradlew :slides:kotlinConfPdf
```
