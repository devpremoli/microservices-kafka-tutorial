# Microservices with Spring Boot & Apache Kafka
### Tutorial

Check out the tutorial on YouTube:

[![Microservices with Spring Boot & Apache Kafka](https://img.youtube.com/vi/HYBtWRPikgo/0.jpg)](https://www.youtube.com/watch?v=HYBtWRPikgo)


# Running Project
- Run all the services
```bash
docker-compose up --build
```
- POSTMAN
  - GET http://localhost:8181/books
  - GET http://localhost:8282/authors
  - GET http://localhost:8383/notifications

- Observe in Postman that total number of elements keeps on increasing as new events occur