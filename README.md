# Replication Package for the "Refactoring Test Smells With JUnit 5: Why Should Developers Keep Up-to-Date?" paper

The list of projects that automate tests using JUnit 5 library can be found in the article. Further details are available in the projects.csv file.

Considering that you have a project, or projects, already cloned to your machine, to find JUnit 5 features to a single project, use the following command line:
```java -jar JUnit5ImportsAnalyzer.jar "path/to/project/root/directory"```

Should you execute the JUnit5ImportsAnalyzer tool to several projects, then this is the command line:
```java -jar JUnit5ImportsAnalyzer.jar -multipleProjects "path/to/projects/root/directory"```

Or you can directly use the tool from its repository in your IDE, available at https://github.com/easy-software-ufal/JUnit5ImportsAnalyzer

Our JUnit5ImportsAnalyzer logs are available in the JUnit5ImportsAnalyzer logs directory.

tsDetect tool usage can be found at https://testsmells.org/pages/testsmelldetector.html

Our tsDetect logs are available in the tsDetect logs directory.
