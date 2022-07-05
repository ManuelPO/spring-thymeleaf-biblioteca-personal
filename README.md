Just execute
`mvn spring-boot:run`

Then launch browser and go to `http://localhost:8080`.

## How to access to the database
Open http://localhost:8080/h2-console

* drive: org.h2.Driver
* JDBC URL: jdbc:h2:file:./target/h2db/db/demo;AUTO_SERVER=TRUE;DB_CLOSE_DELAY=-1
* username: demo
* password: (empty)

## Users

* admin:123
* luis: 123
* jma: 123
* nonactiveuser:123 (this user will not work just because active field is disabled)

## Roles

* `ROLE_ADMIN` (for admin user)
* `ROLE_USER` (for emingora user)


