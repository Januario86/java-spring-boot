## SpringBoot Framework

> Requisitos Básicos

1. [Java Development Kit(JDK) - 1.8 ou superior](https://www.oracle.com/java/technologies/javase-downloads.html)
2. [Intellij IDEA Community Edition ou outra de sua preferência](https://www.jetbrains.com/idea/download/)
3. [Maven 3.5.2](https://maven.apache.org/)
4. [Postman](https://www.postman.com/) 
5. [PowerShell - Opcional para execução em terminal](https://en.wikipedia.org/wiki/PowerShell)

## Desenvolvimento

cd "diretorio de sua preferencia" 

git clone https://github.com/Januario86/java-spring-boot.git


## Executar o Projeto

 mvn spring-boot:run
 
## FatJar - Engloba todas as dependencias do springBoot autoconfiguration, TomCat Embarcado, Web...

mvn clean package

cd "target"  

java -jar springboot.jar "colocar o nome do arquivo de acordo com o gerado na pasta target, EX:springboot-0.0.1-SNAPSHOT.jar"
 
## Documentação

Para referência adicional, considere as seguintes seções:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.2.6.RELEASE/maven-plugin/)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.2.6.RELEASE/reference/htmlsingle/#boot-features-developing-web-applications)

### Guias
Os seguintes guias ilustram como usar alguns recursos concretamente:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)


