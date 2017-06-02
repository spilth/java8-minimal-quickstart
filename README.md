# Java 8 Minimal Quickstart

This is a Maven Archetype for starting a minimal Java 8 project. It includes the following:

- Configured to compile against Java 1.8
- Fixes warnings that Maven generates by default

# Usage

To create a new project using this archetype:

```bash
$ mvn archetype:generate -B -DarchetypeGroupId=org.spilth -DarchetypeArtifactId=java8-minimal-quickstart -DgroupId=com.example -DartifactId=helloworld -Dversion=1.0.0
$ cd helloworld
$ mvn package
```

For a less verbose way to use this archetype please check out [savant](http://spilth.org/projects/savant/).
