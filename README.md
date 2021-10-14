# Replication Package for the "Refactoring Test Smells With JUnit 5: Why Should Developers Keep Up-to-Date?" paper

The list of projects that automate tests using JUnit 5 library can be found ih the file usedProjects.xls

Considering that you have a project, or projects, already cloned to your machine, to find JUnit 5 features to a single project, use the following command line:
```java -jar sniffer.jar "path/to/project/root/directory"```

Should you execute the sniffer tool to several projects, then this is the command line:
```java -jar sniffer.jar -multipleProjects "path/to/projects/root/directory"```

Our Sniffer logs are available in the SnifferLogs directory.

tsDetect tool usage can be found at https://testsmells.org/pages/testsmelldetector.html

Our tsDetect logs are available in the tsDetectLogs directory.
