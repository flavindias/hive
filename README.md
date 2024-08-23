# hive

To download the postgres jdbc connector use the following command

```
mvn dependency:copy -Dartifact="org.postgresql:postgresql:42.7.3" && \                                                                                             
export POSTGRES_LOCAL_PATH=`mvn help:evaluate -Dexpression=settings.localRepository -q -DforceStdout`/org/postgresql/postgresql/42.7.3/postgresql-42.7.3.jar
```
