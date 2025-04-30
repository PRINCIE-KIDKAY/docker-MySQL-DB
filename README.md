# docker-MySQL-DB

This project provides a simple `docker-compose` setup for running a PostgreSQL database with Adminer (a lightweight database management tool).

## 📦 Requirements

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## 🚀 Getting Started

### 1. Clone this repository (or copy the `docker-compose.yml` to your project)

# bash
- git clone https://github.com/PRINCIE-KIDKAY/docker-MySQL-DB.git
- cd your-project-directory


## Start the containers
`docker-compose up -d`

## this will Start a Mysql container with:

- Username: root
- Password: 123456
- Database: mydb
- Exposed on localhost:5532
- Start Adminer on localhost:8181

# Access the services
- Adminer UI: Open your browser and go to `http://localhost:8181`

# Adminer login details:
- System: Mysql
- Server: db (or localhost if connecting from host)

- Username: root
- Password: 123456
- Database: mydb

# Stop the containers

`docker-compose down`