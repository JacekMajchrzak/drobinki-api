# Microservice from drobinki.api responsible for service discovery. Use Netflix Eureka.

##Running the service discovery application
1. Open a command line window or terminal.
1. Start the service-discovery application: java -jar discovery-service-0.0.1-SNAPSHOT.jar.
1. A Netflix Eureka console will be available at http://localhost:8761.

##Docker
To build image:
'''
docker build -f Dockerfile -t drobinki.api-discovery:0.0.1 . 
'''
To run image:
'''
docker run -p 8761:8761 drobinki.api-discovery:0.0.1
'''