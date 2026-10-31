# smartParking — backend

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-6db33f)](https://spring.io/projects/spring-boot)
![Java](https://img.shields.io/badge/Java-21-ed8b00)
![Status](https://img.shields.io/badge/status-early%20stage-orange)

Backend service for a **connected (IoT) parking** project: the server side that manages parking spaces, reservations and related data. Companion to the [ParkWise](https://github.com/GAUSS-TPAC/ParkWise) application.

> **Status:** early-stage scaffold. The Spring Boot application and its build are set up (JPA, Security, Validation, OpenFeign, PostgreSQL); business endpoints are being added.

## Tech stack

Spring Boot 3 · Java 21 · Spring Data JPA · Spring Security · Spring Validation · Spring Cloud OpenFeign · PostgreSQL.

## Run

```bash
git clone https://github.com/GAUSS-TPAC/smartParking.git && cd smartParking
# configure your PostgreSQL connection in src/main/resources/application.properties
./mvnw spring-boot:run        # http://localhost:8080
```

## Related

- [ParkWise](https://github.com/GAUSS-TPAC/ParkWise) — the connected-parking application (reservation and payment).

## License

MIT.
