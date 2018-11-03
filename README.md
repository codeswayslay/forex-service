# FOREX SERVICE
Spring boot microservice for simulating forex provider.

Wonderful demonstration of the versatility of the Spring Boot.

Works by providing conversion rates to the [currency-service client](https://github.com/teamlead-agbaje/currency-service).

Once running, it connects to the [eureka-naming-server](https://github.com/teamlead-agbaje/eureka-naming-server), which acts as a load-balancer. This way, you don't have to keep hard-coding URIs and ports - eureka handles that. Fabolous stuff!
