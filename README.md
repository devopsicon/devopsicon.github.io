![DevOps](https://upload.wikimedia.org/wikipedia/commons/b/b5/Devops.svg "DevOps")

# Plan
Purpose of Real DevOps organization is to demonstrate for the benefit of open source community, best practices involved in DevOpsifying a realistic app with realistic components:
* Rest Microservices (Sales, Expenses, and Users)
* Customer Facing (Hybrid App)
* Message Bus Microservices (Files)

## Strategy
In order to achieve generalisability, we will demonstrate DevOps principles and pipelines using at least two alternate approaches for every stage.

## Tool Space
Execution Handler:
1. TravisCI
2. Jenkins

Static Code Analysis:
1. Code Climate
2. Sonar Qube

Test Coverage:
1. Jenkins Plugins
2. CodeCov

Message Bus:
1. RabbitMQ (CloudAMQP)
2. Kafka

Deployment:
1. Heroku
2. Docker

## Licensing
As none of the software components are really solving any actual problems, GPL v3 seemed appropriate to encourage it being open source forever.
