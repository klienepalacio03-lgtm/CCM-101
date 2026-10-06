# Docker Compose Guide

## What does the `services:` block do?

The `services:` section lists all the containers needed for the application. In this project, it contains the Nextcloud application and MySQL database, along with the settings required for them to work properly.

## How did the Nextcloud app container know how to find the database container?

The Nextcloud container uses the `MYSQL_HOST` variable to locate the MySQL database. The value is the name of the database service in the Docker Compose file, so Nextcloud can connect to it through Docker's internal network.

For example:

```yaml
environment:
  - MYSQL_HOST=db
```

The `db` value points to the MySQL service, allowing Nextcloud to communicate with the database without using a specific IP address.

## Difference Between `docker run` and `docker-compose up -d`

The `docker run` command is normally used to create and start one container at a time. It requires the settings and options to be provided directly in the command.

Meanwhile, `docker-compose up -d` starts the containers that are already defined in the Compose YAML file. It is useful for applications with multiple containers because it can start and connect the services together automatically in the background.

