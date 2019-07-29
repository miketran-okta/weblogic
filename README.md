# Setup WebLogic

This guide outlines instructions on how to setup a basic WebLogic server.

- Download the install at https://www.oracle.com/technetwork/middleware/weblogic/downloads/wls-main-097127.html.  I recommend the "Generic" install.
- Ensure you have a Java JDK installed.  If not, you can download it from https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html

- Install WebLogic

```
java -jar wls1036_generic.jar 
```

- Accept all the install defaults and opt out of the Security Notifications
- At the end of the installation you will be promoted to run through the configuration setup to create a new WebLogic Domain.  Run through that setup and accept all the default configurations.

- Start WebLogic

```
cd <Middleware_Home>/user_projects/domains/base_domain/bin
./startWebLogic.sh
```

- Access the administration console at http://localhost:7001
