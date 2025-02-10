# Kotlin Spring Boot REST API Demo

A simple REST API built with Kotlin and Spring Boot.

## Prerequisites

- JDK 17 or later
- Gradle

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/prageethmgunathilaka/SSPS.git
cd SSPS
```

2. Build the project:
```bash
./gradlew build
```

3. Run the application:
```bash
./gradlew bootRun
```

The application will start on port 8080.

## API Endpoints

### Hello World Endpoint

```
GET /api/hello
```

Response:
```json
{
    "message": "Hello, World!"
}
```

## Testing the API

You can test the API using curl:

```bash
curl http://localhost:8080/api/hello
```

Or using a web browser by visiting:
```
http://localhost:8080/api/hello
```

## Technology Stack

- Kotlin
- Spring Boot
- Gradle
- Spring Web