# spring-cloud-microservice
Learning microservice using spring cloud and spring boot

Here I have added services as submodules. Following are the service's repo :
1. api-gateway : Spring cloud gateway
2. config-repo : Centralized configuration repository
3. currency-conversion-service : microservice
4. currency-exchange-service : microservice
5. limits-service : microservice
6. naming-server : Eureka service registry
7. spring-cloud-config-server

- Resilience4j is implemented in currency-exchange-service.
- Zipkin distributed tracing server used by currency-exchange-service, currency-conversion-service, api-gateway.
- Dockerfile is added in currency-exchange-service.
- docker-compose is configured for currency-exchange-service, naming-server. Their images are also available in krishan5 docker account.
