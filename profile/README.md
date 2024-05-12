# DOCS

Schema of the project shows separstion of the microservices  and how those services communicate.


## SAGA documentation

SAGA was implemented with an orchestrator as our mode of organization. Detailed description of the orchestrator is presented in "Order service and orchestrator" mentioned later on.

All the services are described in the linked readme files below with the orchestrator, hotel and flight services having their own databases. Database schemas are presented in those readme files.

 - [RabbitMQ Broker](https://github.com/VeryGoodTravel/vgt-broker/blob/main/README.md)
 - [SAGA messages format and serialization](https://github.com/VeryGoodTravel/vgt-saga-serialization/blob/main/README.md)
 - [Order Service and orchestrator](https://github.com/VeryGoodTravel/vgt-saga-orders/blob/main/README.md)
 - [Payment Service](https://github.com/VeryGoodTravel/vgt-saga-payment/blob/main/README.md)
 - [Hotel Service](https://github.com/VeryGoodTravel/vgt-saga-hotel/blob/main/README.md)
 - [Flight Service](https://github.com/VeryGoodTravel/vgt-flight-hotel/blob/main/README.md)

SAGA transaction follows the following diagram:


 ## Frontend documentation
 - [Web application](https://github.com/VeryGoodTravel/vgt-web-app/blob/main/docs/docs.md)

## Backend documentation
 - [API](https://github.com/VeryGoodTravel/vgt-api/blob/docs/Docs/README.md)
