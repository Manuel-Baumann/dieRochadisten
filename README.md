# Die Rochadisten
A full-stack chess application featuring:

- **Backend:** Java Spring Boot (REST API, WebSocket, PostgreSQL)
- **Frontend:** Angular
- **Documentation:** API, architecture, deployment, and setup guides

## Project Structure

```
dieRochadisten/
  backend/    # Spring Boot backend
  frontend/   # Angular frontend
  docs/       # Documentation (API, architecture, setup, deployment)
```

## Getting Started

### Prerequisites

- Java 17+
- Node.js 18+ and npm
- PostgreSQL (for backend)
- Docker
- Docker-Compose

### Start via Docker
Mac:
```sh
open /Applications/Docker.app
docker-compose up --build
```

### Start your Backend

```sh
cd backend
./mvnw spring-boot:run
```

### Start your Frontend

```sh
cd frontend
npm install
npm start
```

Visit [http://localhost:4200](http://localhost:4200) for the frontend.

## Documentation

See [docs/README.md](docs/README.md) for API, architecture, and deployment details.

## Building

Build the project:

```sh
ng build
```

Artifacts are stored in `dist/`.

## Running unit tests

Run unit tests with Karma:

```sh
ng test
```

## End-to-end tests

Angular CLI does not include an e2e framework by default. Add one as needed.

## Further help

See the [Angular CLI documentation](https://angular.dev/tools/cli) for more commands and options.

---
```

---

````md
// filepath: dieRochadisten/backend/README.md
# Backend

This is the Java Spring Boot backend for Die Rochadisten.

## Features

- REST API (see [`../docs/api/backend-api.yaml`](../docs/api/backend-api.yaml))
- WebSocket support
- PostgreSQL database integration
- Spring Security

## Requirements

- Java 17+
- Maven (or use the included Maven Wrapper)
- PostgreSQL

## Running the Application

```sh
./mvnw spring-boot:run
```

The backend will start on [http://localhost:8080](http://localhost:8080) by default.

## Configuration

Edit [`src/main/resources/application.properties`](src/main/resources/application.properties) for application settings.

## Testing


## Building

Build the JAR:

```sh
./mvnw clean package
```