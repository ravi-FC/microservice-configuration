Config Server is used when we have common data then we can put here and in our project creater One microservice with name ConfigServer and other microservices are our config client add one syntax
"
  spring:
    config:
      import: "optional:configserver:http://localhost:portno.ofConfigServer
"
now the configuration is completed and we can remove code redundancy in different microservices
