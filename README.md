# FastAPI Docker Example

## Description
This project demonstrates how to set up a simple FastAPI application using Docker. The application provides a basic API endpoint that returns a JSON response.

## Prerequisites
- [Docker](https://www.docker.com/get-started) installed on your machine.

## Project Structure
docker-basic/ │ ├──app└── main.py ├── Dockerfile ├──README.md ├── requirements.txt 


## Installation

1. Clone the repository (if applicable):
   ```bash
   cd docker-basic
   git clone <repository-url>
   create a virtual env and activate it
   install requirements


2. Build a Docker image 
   docker build -t <your_image_name> .

3. Run the fastapi application in docker
   docker run --name <your_container_name> -p 8000:8000 <your_image_name>


