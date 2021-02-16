# JavaCalculatorApp
A Java Calculator app with sample test cases
- create a maven project ->
 - Catalog: All catalogs
 - filter: maven.archetype.webapp
  
- to run the application ->
 - right click on project -> 
   - run as ->  maven build ->
     - goal: clean verify
     - goal: clean install

- TO build a WAR file
- got to pom.xml and add the following code

- add this line near 1st line
-     <packaging>war</packaging>


-      <plugin>
-         <artifactId>maven-war-plugin</artifactId>
-         <version>2.4</version>
-          <configuration>
-              <failOnMissingWebXml>false</failOnMissingWebXml>
-          </configuration>
-      </plugin>
