# SkyLine

This project is a full-stack, type-safe application for airlines. 

Still in progress

![demo_video](https://github.com/user-attachments/assets/48903b09-e263-4978-9f65-5b986a042f72)

### Authentication and Authorization
Users can register with secure password hashing. JWT tokens are issued for stateless, secure authentication.

### Dockerized Environment
Frontend and backend are dockerized.
Utilized PostgreSQL Docker image.

## Technology Stack

- **Next.js** - For providing server-side rendering, static site generation, and handling routes + backend logic.
- **ReactJS** - For creating a dynamic and interactive user interface with a component-based architecture.
- **Tailwind CSS** - For utility-first CSS styling, enabling rapid and responsive design with minimal custom CSS.
- **Typescript** - For adding static typing to JavaScript, improving code quality and maintainability with type safety.
- **Express.js** - For building a backend server.
- **Prisma ORM** - For seamless and type-safe database interactions with PostgreSQL.
- **PostgreSQL** - For storing and querying structured data.
- **Docker** - For containerizing the application, ensuring consistency across different environments and simplifying deployment.

## Get Started

To set up and run the project locally, follow these steps:

### 1. Clone the Repository

First, clone the repository to your local machine.

### 2. Set Up Docker

To set up and run the Docker containers using Docker Compose, follow these steps:

1. **Ensure Docker and Docker Compose are installed** on your machine. If not, you can download and install them from [Docker's official site](https://docs.docker.com/get-docker/).

2. **Run Docker Compose** to build and start the containers. Open your terminal, navigate to the root of your project directory, and run:

    ```bash
    docker-compose up --build
    ```

   This command will build the Docker images and start the containers as defined in the `docker-compose.yml` file.

3. **Verify Everything is Running**:

    - The frontend should be accessible at [http://localhost:3000](http://localhost:3000).
    - The backend should be accessible at [http://localhost:4000](http://localhost:4000).
    - The PostgreSQL database should be accessible at `localhost:5432`.

If you need to stop the containers, use:

```bash
docker-compose down



