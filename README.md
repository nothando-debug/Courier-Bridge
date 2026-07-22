# Courier-bridge

Courier Bridge is a Java-based parcel tracking and courier integration system designed to manage shipments through a single REST API.

The system will allow users to create shipments, generate tracking numbers, record delivery status history, and standardise updates received from different courier providers.

## Project Goals

* Create and manage shipments
* Generate unique tracking numbers
* Track shipment status
* Record a complete delivery history
* Integrate multiple simulated courier providers
* Convert different courier statuses into one standard format
* Prevent duplicate shipment updates
* Provide clear API documentation and automated tests

## Planned Tech Stack

* Java 21
* Spring Boot
* Spring Web
* Spring Data JPA
* PostgreSQL
* Maven
* JUnit 5
* Mockito
* Swagger / OpenAPI
* Postman

## Current Status

The project is currently in the planning and setup stage.

The next steps are:

1. Define the minimum viable product
2. Write user stories and acceptance criteria
3. Design the shipment workflow
4. Plan the database structure
5. Create the Spring Boot application

## Initial Shipment Workflow

`CREATED → BOOKED → COLLECTED → IN_TRANSIT → OUT_FOR_DELIVERY → DELIVERED`

## Project Scope

The first version will focus on backend development and systems integration.

Features such as authentication, a frontend, live GPS tracking, real courier APIs and notifications may be considered after the main workflow is complete.
