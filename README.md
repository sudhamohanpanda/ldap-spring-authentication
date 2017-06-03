# ldap-spring-authentication
Simple ldap authentication using Spring boot, Spring security and ldap.

Prerequisite: 
  1. Installed and run apache directory server on local with port 10389
  2. import file initial.ldif file
  
 Clone and run project:  
    1. git clone 
    2. mvn clean install
    3. mvn spring-boot:run
    
Open http://localhost:8080/ in browser
It will prompt for username password, enter smp and smp123 respectively.

It's a working example. To run this start apacheDS on 10389 port and import/create using apache directory studio using \initial\src\main\resources\test-server.ldif  
hit http://localhost:8080/ it will prompt UI to enter username password. Enter ben benspass
You will get a page with "Welcome to the home page!"
