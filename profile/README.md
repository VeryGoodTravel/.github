# DOCS

Schema of the project [at the end of this doument](#vis) shows separation of the microservices and how those services communicate.


## SAGA documentation

SAGA was implemented with an orchestrator as our mode of organization. Detailed description of the orchestrator is presented in "Order service and orchestrator" mentioned bellow.

All the services are described in the linked readme files bellow with the orchestrator, hotel and flight services having their own databases. Database schemas are presented in those readme files.

 - [RabbitMQ Broker](https://github.com/VeryGoodTravel/vgt-broker/blob/main/README.md)
 - [SAGA messages format and serialization](https://github.com/VeryGoodTravel/vgt-saga-serialization/blob/main/README.md)
 - [Order Service and orchestrator](https://github.com/VeryGoodTravel/vgt-saga-orders/blob/main/README.md)
 - [Payment Service](https://github.com/VeryGoodTravel/vgt-saga-payment/blob/main/README.md)
 - [Hotel Service](https://github.com/VeryGoodTravel/vgt-saga-hotel/blob/main/README.md)
 - [Flight Service](https://github.com/VeryGoodTravel/vgt-saga-flight/blob/main/README.md)

SAGA transaction flow is presented by the schema bellow:

![SAGA flow chart](https://github.com/VeryGoodTravel/.github/blob/main/profile/saga.svg)

 ## Frontend documentation
 - [Web application](https://github.com/VeryGoodTravel/vgt-web-app/blob/main/docs/docs.md)
 - [Acceptance tests for web application in Selenium](https://github.com/VeryGoodTravel/vgt-selenium-tests)

## Backend documentation
 - [API](https://github.com/VeryGoodTravel/vgt-api/blob/docs/Docs/README.md)

# <a name="vis">Visualization</a>

![Project schema](https://github.com/VeryGoodTravel/.github/blob/main/profile/components.svg)
