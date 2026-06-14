# QuickTask API 📝

A simple Task Management REST API built with Spring Boot and MySQL.

## Tech Stack
- Java 22
- Spring Boot 4.1.0
- Spring Data JPA
- Hibernate
- MySQL
- Lombok
- Maven

## Features
- ✅ Create a task
- ✅ Get all tasks
- ✅ Update a task
- ✅ Delete a task
- ✅ Priority levels (HIGH, MEDIUM, LOW)
- ✅ Exception Handling

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /tasks | Get all tasks |
| POST | /tasks | Create a new task |
| PUT | /tasks/{id} | Update a task |
| DELETE | /tasks/{id} | Delete a task |

## Sample Request Body

```json
{
  "title": "Fix bug",
  "description": "Login issue",
  "completed": false,
  "priority": "HIGH"
}
```
## Live API
Base URL: https://quicktask-api-production.up.railway.app

Test it: https://quicktask-api-production.up.railway.app/tasks

## How to Run
1. Clone the repo
2. Create MySQL database: `quicktask_db`
3. Update `application.properties` with your MySQL credentials
4. Run as Spring Boot App in STS
5. Test APIs using Postman on `http://localhost:8080`
