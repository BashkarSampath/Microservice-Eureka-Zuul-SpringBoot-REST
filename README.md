# Microservice-Eureka-Zuul-SpringBoot-REST
Change the port number of the "SpringBoot" app for multiple instances and load balancing using zuul.

Sequence of execution: Eureka Server App - Zuul Server App - Spring Boot Rest Server App (change the port and launch multiple instances)

For the route of these insances please refer to "zuulhost:port/actuator/routes" 
and to make requests to the rest endpoint use 
"zuulhost:port/<the route displaced by actuator>/<endpoint>"
