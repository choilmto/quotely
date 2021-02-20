# Quotely README

## Building the project

`mvn clean compile assembly:single` builds the project

## Running the project

`java -jar target/quotely-1.0-SNAPSHOT-jar-with-dependencies.jar [ARGS]` runs the project. `[ARGS]` is the
language specified, either English or Russian.

## Running the test suite

`mvn test` runs the test suite.