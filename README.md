# PlayFramework Demo
Demo project implementing LightBend Playframework

## Pre-requisite
1. jdk 8+
2. Scala
3. sbt

## Creating a New Application
LightBend Play framework expects a particular project structure.
If one already has scala installed, one can use giter8 template
similar to maven archetype, to create a new Play project.
In a command prompt type the following command

```bash
sbt new playframework/play-scala-seed.g8
```
Once a project is created, to check the project is created correctly,
type the following in the command prompt.

```bash
sbt run
```

In a browser enter http://localhost:9000/ to view the welcome page.


