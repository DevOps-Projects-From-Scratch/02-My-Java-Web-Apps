# my-java-webapp
## Maven Command used to create this Project is:

 mvn -B archetype:generate                                  \
-DarchetypeGroupId=org.apache.maven.archetypes              \
-DarchetypeArtifactId=maven-archetype-webapp                \
-DarchetypeVersion=1.3  -DgroupId=com.mycompany.app         \
-DartifactId=myapp                                          \
-Dversion=1.0-SNAPSHOT

## Then created a directory named "images" inside the src/main/webapp directory of my Maven project.  

## Placed a image files image.jpg inside the images directory.

## Then included the image path using img src tag in index.jsp file.

### <img src="image path" alt="Lable">

## This is how my index.jsp looks like after modifications:

### <html>
### <body>
### <h1>Congratulations You Have Successfully Deployed Your Applications.</h1>
### <img src="images/image.jpg" alt="Logo">
### </body>
### </html>


## Now your having a java-web-application ready, Now you can build it using maven

mvn clean package 

## After executing the above maven command inside Maven Project where pom.xml is present a war file will be created inside a Target directory. 




