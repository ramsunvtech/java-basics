# Java Basics

## Install Java

```
# download and Install Java manually
java -version
```

## Install and Setup Maven

```
brew install maven # For Mac
scoop install maven # For Windows
mvn -version # Check version
mvn install # Install POM XML Dependencies
mvn dependency:tree
mvn clean compile
mvn test
```

## Run Test

```
mvn test
```

## Generate Docs

```
mvn javadoc:javadoc
```

## Check Coverage Report

```
mvn verify
```