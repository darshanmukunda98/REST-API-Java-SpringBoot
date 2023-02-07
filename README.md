
# REST-API-Java-SpringBoot

This is an attempt to build my own REST API using Spring Boot. I have used [Building REST services with Spring](https://spring.io/guides/tutorials/rest/) as a guide.




## API Reference

#### Get all employees

```http
  GET /employees
```
#### Get employees by id

```http
  GET /employees/{id}
```


#### POST item

```http
  POST /employees
```

| Body | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `name`      | `JSON` | **Required**. name of employee to add. |
| `role`      | `JSON` | **Required**. role of employee to add. |

#### PUT item

```http
  PUT /employees/{id}
```

| Body | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `name`      | `JSON` | **Required**. name of employee to add. |
| `role`      | `JSON` | **Required**. role of employee to add. |




## Documentation

[Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

