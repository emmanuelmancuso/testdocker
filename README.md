# TestDocker

This project is a demonstration of using Docker to deploy a basic FastAPI API. It aims to provide a simple and functional starting point for those looking to explore integrating FastAPI within a Docker container.

## Prerequisites

Make sure you have Docker installed on your machine before getting started.

- [Docker Installation Guide](https://docs.docker.com/get-docker/)

## How to Use This Project

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/testdocker.git
    cd testdocker
    ```

2. Build the Docker image using the provided Dockerfile:

    ```bash
    docker build -t testdocker .
    ```

3. Run the Docker container:

    ```bash
    docker run -p 8000:8000 testdocker
    ```

    The FastAPI API will be accessible at [http://localhost:8000](http://localhost:8000).

## Project Structure

- **app.py**: Contains the main code for the FastAPI API.
- **Dockerfile**: Defines the instructions for building the Docker image.
- **requirements.txt**: Lists Python dependencies required for the project.

## Contributing

If you'd like to contribute to this project, feel free to submit a pull request. Suggestions and improvements are welcome!

## Author

- Manu
