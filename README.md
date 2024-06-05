
### Install GraalVM & set the environment variable

```
export GRAALVM_HOME=/Users/XXX/java/17.0.11-graal
export JAVA_HOME=$GRAALVM_HOME
```

### Compile the native image

```
./gradlew nativeCompile
```
