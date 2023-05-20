# my-java-webapp
## Maven Command used to create this Project is:

 mvn -B archetype:generate                                  \
-DarchetypeGroupId=org.apache.maven.archetypes              \
-DarchetypeArtifactId=maven-archetype-webapp                \
-DarchetypeVersion=1.3  -DgroupId=com.mycompany.app         \
-DartifactId=myapp                                          \
-Dversion=1.0-SNAPSHOT

## Then created a directory named "images" inside the src/main/webapp directory of my Maven project. 
![image](https://github.com/Devops-Projects-From-Scrach/My-Java-Web-Apps/assets/91256009/c9664d2a-1faf-45fe-91b7-20cb0e0d2e71)

## Placed a image files image.jpg inside the images directory.
![image](https://github.com/Devops-Projects-From-Scrach/My-Java-Web-Apps/assets/91256009/78c2a239-c57e-42f0-a648-f4170409adae)
## Then included the image path using img src tag in index.jsp file

## My index.jsp file looks like this after modification.
![index](https://github.com/Devops-Projects-From-Scrach/My-Java-Web-Apps/assets/91256009/6421a9d3-5d89-4202-b94a-4bf8aa23c8e3)

## Now your having a java-web-application ready, Now you can build it using maven
mvn clean package 

## After executing the above maven command inside Maven Project where pom.xml is present a war file will be created inside a Target directory. 
![target](https://github.com/Devops-Projects-From-Scrach/My-Java-Web-Apps/assets/91256009/39e3df14-53f1-4882-86a7-52868852d225)
## You can see war file inside Target directory.
![war](https://github.com/Devops-Projects-From-Scrach/My-Java-Web-Apps/assets/91256009/313981e7-3e9d-409e-941d-6e4045bc71fb)


## Output of the war file when deployed on any application server like tomcat will be as below.
![output](https://github.com/Devops-Projects-From-Scrach/My-Java-Web-Apps/assets/91256009/d1604229-77f0-408f-a1e4-e75584a89c26)


