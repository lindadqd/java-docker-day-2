# Java Docker Day 2 Exercise

## Learning Objectives

- Create a Spring Application with the usual end points
- Practice deploying the Spring Application to a Docker Container
- Use a separate container to host a PostgreSQL database
- Use docker-compose to orchestrate creating and running your containers

## Instructions

1. Fork this repository
2. Clone your fork to your machine
3. Open the project in IntelliJ

## Core

Create an API with the usual GET/PUT/POST/DELETE endpoints, the API could serve user data for a Micro-Blogging platform (something like Twitter) or you could reuse a previous exercises API endpoints. Either way the code will need to be in this repo for us to see it.

Work out some sensible tables for a basic version of this that will allow a single user to use the platform to make posts etc. 

Your API should connect to PostgreSQL database instance that will run in a local container.

Create a `jar` file for the completed application.

Use `docker-compose` to create the appropriate images and orchestrate running them together, it should also manage the connection details for the database.

To assess this we will clone your repository, and use your `docker-compose.yml` file to generate the appropriate images and run them.

## Extension

Add the correct commands to ensure that the data in the database persists between runs of docker compose. How far can you get in automating the whole process of building the containers?

