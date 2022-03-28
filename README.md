# wordpress-docker

## Install

1. Install [docker engine](https://docs.docker.com/engine/install/).
2. After docker engine installed, using `docker-compose.yml` to install related docker.
   ```bash
   docker-compose up
   ```
3. You will see docker in docker desktop app, after dockers is installed.
   ![docker list](./images/docker-list.png)
4. Using browser to open [phpMyAdmin](http://localhost:8000/), then craete a database named as `wordpress`, using `utf8mb4_unicode_ci` charset.
5. Using browser to open [WordPress](http://localhost:8080/), you can now start using wordpress with the installation page.
6. Filling all the required information, click start install.
7. Now you can visit [control pannel](http://localhost:8080/wp-login.php) and your [wordpress web page](http://localhost:8080/).