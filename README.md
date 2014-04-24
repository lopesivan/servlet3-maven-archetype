#servlet3-maven-archetype

Project provides Maven archetype for creating plain simple Servlet 3 based webapplication

```bash
mvn archetype:create \
    -DgroupId=com.mycompany.app \
    -DartifactId=my-webapp \
    -DarchetypeArtifactId=maven-archetype-webapp
```


##Installation

Clone this repository

```bash
$ git clone https://github.com/maciejwalkowiak/servlet3-maven-archetype.git
```

Install it to local Maven repository

```bash
$ cd servlet3-maven-archetype
$ mvn install
```

Create project based on this archetype

```bash
$ mvn archetype:generate \
    -DarchetypeGroupId=pl.maciejwalkowiak \
    -DarchetypeArtifactId=servlet3-webapp-archetype \
    -DarchetypeVersion=1.0
```

Run project:

```bash
$ mvn tomcat7:run
```
