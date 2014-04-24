#servlet3-maven-archetype

Project provides Maven archetype for creating plain simple Servlet 3 based webapplication

##Installation

Clone this repository

```bash
$ git clone https://github.com/lopesivan/servlet3-maven-archetype.git
```

Install it to local Maven repository

```bash
$ cd servlet3-maven-archetype
$ mvn install
```

Create project based on this archetype

```bash
$ mvn archetype:generate \
    -DarchetypeGroupId=project._42algoritmos \
    -DarchetypeArtifactId=servlet3-webapp-archetype \
    -DarchetypeVersion=1.0.1
```

Run project:

```bash
$ mvn tomcat7:run
```
