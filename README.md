# coding-exercise-api

- Implement REST APIs in any language/framework
- Feel free to use any resources on the Internet for assistance.

## REST Endpoints to implement

1. handle creating a person with 3 fields: id, name, companyName
2. handle retrieving a person with a specific id
3. handle updating a person
4. handle deleting a person
5. handle retrieving a list of company names and how many people are in each company. Example response: `{ "iManage": 3, "Google": 2 }`

## Datasource

Implement with simple in-memory collection object (list, or map, etc.)

## Unit test

Create unit test for REST endpoint #5 (num of people in each company)

## Starter code

Optional: feel free to use the code in the repo for a starter. 
It is a Spring Boot project using Java 17, Maven, spring-boot-starter-web. 
[https://start.spring.io/](https://start.spring.io/) was used to generate.

```bash
./mvnw test
./mvnw spring-boot:run
```
