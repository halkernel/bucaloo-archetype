# bucaloo-archetype
Custom maven archetype for making project creation using spring + spock easy.
You can find the dependencies inside the [pom.xml](https://github.com/halkernel/bucaloo-archetype/blob/master/pom.xml):

> spring-boot-starter-web
> spring-boot-starter-validation
> spring-boot-starter-data-jpa
> spring-boot-starter-test
> h2
> jacoco-maven-plugin
> spock-core
> groovy-all
> cglib-nodep
> http-builder


## Installing
```shell
mvn archetype:create-from-project
mvn /target/generated-sources/archetype
mvn clean install
```


## Using
```shell
mvn archetype:generate                    \
-DarchetypeGroupId=org                    \
-DarchetypeArtifactId=bucaloo-archetype   \
-DarchetypeVersion=1.0.0                  \
-DgroupId=org.testing.project             \
-DartifactId=testing-project
```

