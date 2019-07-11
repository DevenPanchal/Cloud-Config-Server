## CONFIG SERVER 

### Notes:
* This Project acts as the configuration microservice for the [POC's](https://gitlab.research.att.com/deven/poc-properties-configuration) part 3
* Advantage: Centralized but Microservices Paradigm, Versioning, Externalized Configuration
* This needs to be running before the POC runs.
* This Config Server runs on port 7776
* This Config server needs to clone continuously from Github. Please make sure the network provides uninterrupted connectivity and cloning ability from Github.

### Compile: 
	mvn clean install
### Run: 
    java -jar config-server-0.0.1-SNAPSHOT.jar
    
