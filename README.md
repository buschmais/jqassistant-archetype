jQAssistant Archetypes
======================
This project provides Maven archetypes for [jQAssistant](http://jqassistant.org).

Single Maven module project using jQAssistant
---------------------------------------------

```
mvn archetype:generate \
  -DarchetypeGroupId=com.buschmais.jqassistant.archetype \
  -DarchetypeArtifactId=jqassistant.archetype.project \
  -DarchetypeVersion=1.1.0 \
  -DgroupId=com.example \
  -DartifactId=project \
  -Dversion=1.0.0-SNAPSHOT
```

The parameters "groupId", "artifactId" and "version" shall be replaced by the required values. The command will create a single module Maven project containing a jQAssistant plugin configuration in the file pom.xml and an example rule setup for JUnit4.
