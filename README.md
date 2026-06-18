3.1
name>gradele>groovy>finish
build.gradle ( copy/paste)

main.java (paste code and run it)
gradle run

create ,html,css,logo

./gradlew prepareDocs

create repo on github
git init 
git add .
 git commit -m "first commit"
 git remote add origin <url>
 git push origin main

 goto settings>pages>main>docs>save

 build.gradele
 add selenium,testNG

 src>test>java>package>>org.test>javaclass>webpageTest(copy/paste)

 remove all code in build.gardle ,paste new code from ppt

 gradle jar
 java -jar(.\build\libs\<project-name.jar>

 
3.2
kotlin,gradle.

build.gradle.kte (copy paste code)

in main.kt (paste code)

./gradlew clean
./gradlew build
./gradlew run 

create jar file
build.gardle.kte(add code of jar file

./gradlew fat jar

goto build folder>libs<devops 3.2 ---->
copy as path 
<copy as root content>

java -jar (build/libs/dev3.2----)


4
new project>java>maven>create

pom.xml (add code below project)
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>

  <groupId>org.example</groupId>
  <artifactId>p4</artifactId>
  <version>1.0-SNAPSHOT</version>
  <packaging>jar</packaging>

  <name>p4</name>
  <url>http://maven.apache.org</url>

  <properties>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
  </properties>

  <dependencies>
    <dependency>
      <groupId>junit</groupId>
      <artifactId>junit</artifactId>
      <version>3.8.1</version>
      <scope>test</scope>
    </dependency>
  </dependencies>
  <build>
    <plugins>
      <!-- Compiler Plugin -->
      <plugin>
        <groupId>org.apache.maven.plugins</groupId>
        <artifactId>maven-compiler-plugin</artifactId>
        <version>3.8.1</version>
        <configuration>
          <source>1.8</source>
          <target>1.8</target>

        </configuration>
      </plugin>

      <!-- Jar Plugin -->
      <plugin>
        <groupId>org.apache.maven.plugins</groupId>
        <artifactId>maven-jar-plugin</artifactId>
        <version>3.2.0</version>
        <configuration>
          <archive>
            <manifest>
              <mainClass>org.example.App</mainClass>
            </manifest>
          </archive>
        </configuration>
      </plugin>
    </plugins>
  </build>
</project>



copy code in main.java
src>main>java>org.ex>main
package org.example;

public class App {
    public static void main(String[] args) {
        System.out.println("Hello from Gradle!");
    }
}

terminal

mvn clean compile
mvn package

now create jar file inside target

java -jar<copy the path of jar file>(target)

mvn clean install
gradle init --type pom
option2
yes


build.gradle
replace of plugins
also add dependencies after plugin
also add jar file end of the program

terminal
gradle clean build
java -jar (build/libs/dev--)copy








