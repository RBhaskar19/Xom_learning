# Ez Learning

> e-learning web application made using Java 8, Spring Boot, MySql and Materialize


## Start the Application

To start the application locally with the default profile (dev) run this command at the /ez-learning folder
```shell
./mvnw spring-boot:run
```

---

## General Info

This application started as an academic project in August 2019, developed for the Business Applications Development II course at Isil, Lima, Perú.

It's an e-learning platform where you can explore courses, teachers, and register to take as many courses as you like.

---

## Technologies

Uses [Thymeleaf](https://www.thymeleaf.org/) as the template engine for the Frontend, which was styled using [Materialize](https://materializecss.com/).

The backend is developed in Java 8, using [Spring Boot](https://spring.io/projects/spring-boot) with Spring MVC, Spring JPA and Spring Security dependencies.

It has 2 application profiles, one for development and one for production. The dev profile uses an in memory [H2 Database](https://www.h2database.com/), while the production one uses [MySql](https://www.mysql.com/). Both of them use Sql versioning with [Flyway](https://flywaydb.org/).

The web application is hosted in [Heroku](https://www.heroku.com/), while the MySql database is hosted in a [AWS RDS](https://aws.amazon.com/rds/) instance.

---
