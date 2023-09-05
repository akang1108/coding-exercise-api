# coding-exercise-api

Create a REST API implementation in any language/framework to perform operations for a person resource.

Feel free to use any resources on the Internet for assistance.

## REST Endpoints to implement

1. handle creating a person with 3 fields: id, name, companyName
2. handle retrieving a person with a specific id
3. handle updating a person (name/companyName fields)
4. handle deleting a person
5. handle retrieving a list of company names and how many people are in each company. E.g. `{ "iManage": 3, "Google": 2 }`

## Datasource

Implement with simple in-memory collection object (list, or map, etc.)

## Unit testing

Create unit test for the logic implemented on the endpoint that retrieves a list of company names and number of people in each company.

## Starter code

Feel free to use the code in the repo for a starter. It is a Spring Boot project using Java 17, Maven, spring-boot-starter-web. [https://start.spring.io/](https://start.spring.io/) was used to generate.

```bash
./mvnw test
./mvnw spring-boot:run
```

Feel free to not use this code or code in another language.
