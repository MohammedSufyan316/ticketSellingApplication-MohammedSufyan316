# Project ticketselling

## Purpose

This is code associated with DePaul SE452 group project for ticket sales program.
[Prototype](https://app.moqups.com/1zIpZ8l9DC2ShQhs4aCoKQK6kA0BC7y1/view/page/ad64222d5)

## Project Members

| Member | Area | Saying        |
| ------ | ---- |---------------|
| Mohammed Sufyan Khan Osmani | Event management for organizers |               |
| Pradhyum Patel | User Interface |               |
| Rolando Cuba | Database(s) |               |
| Suhwan Kim | Marketing and communication | Hi-yo Silver! |
| William Berthouex | Backend components |               |

## Conflict Resolution

Vote to select what the majority chose.

## Communication Mechanism

Use Discord for meetings and decisions, and upload code to GitHub.
Meet weekly on Sundays.

## Decisions Made

| # | Area                  | Decision                        | Alternative | Rationale                                             |
|---|-----------------------|---------------------------------|-------------|-------------------------------------------------------|
| 1 | IDE                   | Members use IDE of their choice | -           | It is not necessary for everyone to use the same IDE. |
| 2 | Dependency Management | Maven                           | -           | Group preferred Maven                                 |

# 🎟️ Ticket Selling App

Full-stack app with Spring Boot (Java 21), Angular, and H2 DB.

---

## 🔧 Backend (Spring Boot)

1. Run in root folder:
2. mvn spring-boot:run
3. Access API at: http://localhost:8080

### View H2 DB:

1. Go to: http://localhost:8080/h2-console
2. JDBC URL: jdbc:h2:mem:ticketsellingtest
3. Username: sa | Password: password

## 🌐 Frontend (Angular)
1. Go to frontend:
2. cd src\main\java\edu\depaul\ticketselling\userinterface
3. npm install
4. ng serve
5. App runs at: http://localhost:4200