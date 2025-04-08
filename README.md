# Coding Exercise

- Implement REST APIs in any language/framework
- Feel free to use any resources on the Internet for assistance.

## Implement 3 REST API endpoints

1. endpoint that creates a person with 3 fields 
   - id
   - name
   - companyName
2. endpoint that retrieves a person with a specific id
3. endpoint that retrieves a map of company names and how many people are in each company

Example response

```json
{ 
   "iManage": 3, 
   "Google": 2 
}
```

## Datasource

Implement with simple in-memory collection object (list, map, dictionary, etc.)

## Testing

Create a test for REST endpoint #3 (num of people in each company)

## Starter code

- Feel free to use the code in the repo for a starter (completely optional)
- It is a Spring Boot project using Java 17, Maven, spring-boot-starter-web.
- [https://start.spring.io/](https://start.spring.io/) was used to generate.

```bash
./mvnw test
./mvnw spring-boot:run
```
