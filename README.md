TomcatHelloWorldApp Sample @shomrai
====================================

This project contains a simple Servlet application.

## Building with Maven

This project can be built with Maven.
Use:

1. Execute full Maven build:
    ```bash
    $ mvn clean install
    ```

2. To push the application to Bluemix using the cf command line tool:
    ```bash
    $ cf push <appname> -p target/TomcatHelloWorldApp.war
    ```
