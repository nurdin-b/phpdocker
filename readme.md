# phpdocker
docker compose php nginx mariadb phpmyadmin

# Ho to use
- clone this repository
- paste your project into public directory
- command 'docker compose up' If you make changes to your application code or any files that are mounted into the Docker containers (e.g., PHP files).

******

If you make changes to the Nginx configuration file (nginx.conf) or to the Dockerfile for any service (e.g., the PHP-FPM Dockerfile), you should use:
'docker-compose up --build'

This command not only restarts the containers but also rebuilds the Docker images, ensuring that your changes to the Dockerfile or Nginx configurations are applied.

********

# Options #
- For changes in application code or files, use docker-compose restart.
- For changes in Nginx configurations, Dockerfiles, or anything affecting the container images, use docker-compose up --build.