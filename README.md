Here’s a well-structured `README.md` for your GitHub project:

---

# Video Catalog

A TypeScript-based project with Nest.js API, integrated with RabbitMQ, video encoder, and comprehensive testing setup. This repository includes the development of key entities such as Category, Genre, Cast Member, and Video, and applies best practices for architecture, testing, and clean code principles.

## Table of Contents
- [Getting Started](#getting-started)
- [Technologies](#technologies)
- [Features](#features)
- [Setup](#setup)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Testing](#testing)
- [License](#license)

## Getting Started

Follow these instructions to set up the development environment and run the project locally.

### Prerequisites
- [Docker](https://www.docker.com/get-started)
- Node.js (v16 or higher)
- [Nest.js CLI](https://docs.nestjs.com/cli/overview)

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/projectname.git
   cd projectname
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up Docker environment:**
   Ensure that Docker is running and use the following command to set up the containers.
   ```bash
   docker-compose up -d
   ```

4. **Run the application:**
   ```bash
   npm run start:dev
   ```

## Technologies

- **TypeScript**: Strongly-typed JavaScript for better development experience.
- **Nest.js**: A progressive Node.js framework for building efficient server-side applications.
- **Docker**: Containerization of services to streamline development and deployment.
- **RabbitMQ**: Messaging broker integration for handling asynchronous tasks.
- **Video Encoder**: Encodes video files as part of the project requirements.
- **Testing Tools**: Unit testing and End-to-End testing setup.

## Features

- Development of core entities such as Category, Genre, Cast Member, and Video.
- Comprehensive use of repositories, aggregates, and use cases for clean architecture.
- Custom handling of entity IDs and the Unit of Work pattern.
- Full integration with RabbitMQ for messaging and video encoding tasks.
- Thorough testing: unit tests, integration tests, and End-to-End (E2E) tests.

## Usage

To create the various entities (Category, Genre, Cast Member, Video), follow the modular structure set up in the project. Each entity has its dedicated folder with services, use cases, and tests. Modify and extend them as needed for your application.

## Testing

This project includes comprehensive tests, covering unit tests, use case tests, and E2E tests.

- **Unit Tests:**
   ```bash
   npm run test
   ```

- **End-to-End (E2E) Tests:**
   ```bash
   npm run test:e2e
   ```

- **Testing Entities (Genre, Cast Member, Video, etc.):**
   Each entity includes its tests that ensure proper functionality and relationships between aggregates.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize this `README.md` based on your project's specific needs or features.