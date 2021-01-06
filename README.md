# quarkus-orm-panache project

## Running the application in dev mode

```shell script
./mvnw compile quarkus:dev
```

## Packaging and running the application

```shell script
./mvnw package
```
```shell script
./mvnw package -Dquarkus.package.type=uber-jar
```

The application is now runnable using `java -jar target/quarkus-orm-panache-1.0.0-SNAPSHOT-runner.jar`.

## Creating a native executable

```shell script
./mvnw package -Pnative
```

```shell script
./mvnw package -Pnative -Dquarkus.native.container-build=true
```

You can then execute your native executable with: `./target/quarkus-orm-panache-1.0.0-SNAPSHOT-runner`