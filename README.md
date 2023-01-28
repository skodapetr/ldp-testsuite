# Test Suite for the Linked Data Platform 1.0

## Requirements
- [Java] 17, 18

## How to run
First you need to build the project from source:
```
./mvnw package
```

Now you can run the testsuite using ```ldp-testsuite-0.2.4-shaded.jar``` located in ```target``` directory.
You can list available commands and configuration using:
```
java -jar ./target/ldp-testsuite-0.2.4-shaded.jar -h
```


For example to test local server running at port 5000 with basic test you can run:
```
java -jar ./target/ldp-testsuite-0.2.4-shaded.jar --server http://localhost:5000 --basic 
```

## Credits
This project is a fork of the [W3C LDP testsuite](http://w3c.github.io/ldp-testsuite).
In addition, changes from [trellis-ldp](https://github.com/trellis-ldp/ldp-testsuite) [were adopted](https://github.com/skodapetr/ldp-testsuite/pull/1).

[Java]: <http://www.oracle.com/technetwork/java/javase/downloads/index.html>

