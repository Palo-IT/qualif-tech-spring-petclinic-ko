# <a href="http://palo-it.com/">Palo-IT</a> Spring PetClinic Sample Application KO

## What is this project for ?
This project is for practical qualification test. The candidate have to fix it in the TestDrivenDevelopement way.
Techno : Spring-core, Spring-data, JPA, JDBC, SQL, JPQL ...

## What does it look like?
The original spring-petclinic has been deployed here on cloudfoundry: http://gopetclinic.cfapps.io/

## Understanding the Spring Petclinic application with a few diagrams
<a href="https://speakerdeck.com/michaelisvy/spring-petclinic-sample-application">See the presentation here</a>

## Working with Petclinic in Eclipse/STS

### prerequisites
The following items should be installed in your system:
* Maven 3 (http://www.sonatype.com/books/mvnref-book/reference/installation.html)
* git command line tool (https://help.github.com/articles/set-up-git)
* Eclipse with the m2e plugin (m2e is installed by default when using the STS (http://www.springsource.org/sts) distribution of Eclipse)

Note: when m2e is available, there is an m2 icon in Help -> About dialog.
If m2e is not there, just follow the install process here: http://eclipse.org/m2e/download/


### Steps:

1) In the command line
```
git clone https://github.com/Palo-IT/qualif-tech-spring-petclinic-ko
```
2) Inside Eclipse
```
File -> Import -> Maven -> Existing Maven project
```
3) Fix the project
```
Fix the project in the TestDrivenDevelopement way
```
4) Run petclinic locally
```
mvn tomcat7:run
You can then access petclinic here: http://localhost:9966/petclinic/
```
