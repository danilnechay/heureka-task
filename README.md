# heureka-task
Task for applicant

# Purpose: 

We need one microservice. The service will parse messages from a queue in RabbitMQ and store certain parts of them in a database. 
The messages are JSON objects encoded in a binary format and represent an offer entity. 
We need to extract the values under the keys `legacy` and `attributes` from the message and store them in the DB.

# Attachments:

* A mock message that should be consumed from RabbitMQ.
* We prepared for you docker-compose with hints how to run RMQ and PostgreSQL locally.


# Requirements:

* Showcase all your best skills.

* Dockerize the application

* Tests

* Anything else that comes to mind

# Deliverables:

* Source code for the microservice.

* Docker and Docker-compose files.

* A README or documentation detailing how to run the solution, decisions made, and any other relevant information.

* Push your solution to a public GitHub repository. Share the link to the repository with us.
