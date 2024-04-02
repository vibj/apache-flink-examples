Working examples of apache flink

1 . Creating a project 

```
mvn archetype:generate -DarchetypeGroupId=org.apache.flink \
    -DarchetypeArtifactId=flink-quickstart-java \
    -DarchetypeVersion=1.19.0 \
    -DgroupId=stream-examples \
    -DartifactId=word-count-example \
    -Dversion=0.1 \
    -Dpackage=org.cleverstep \
    -DinteractiveMode=false
```