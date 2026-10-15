# Simple HTML Maven Project

## Project structure
- `pom.xml` - Maven build configuration
- `src/main/webapp/index.html` - Website page
- `src/main/webapp/css/style.css` - Page styling

## Build
Install a JDK and Maven, then run from this directory:

    mvn clean package

This generates `target/simple-html-maven.war`.

## Run
Deploy the WAR to Apache Tomcat and open:

    http://localhost:8080/simple-html-maven/

You can also open `src/main/webapp/index.html` directly in a browser to preview the page without Maven or Tomcat.
