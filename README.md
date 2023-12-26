# Wordpress
> WordPress docker-compose by [phamquiduong](https://github.com/phamquiduong)

<br>

# Introduction
> - [Wordpress Official website](https://wordpress.com/)

### Docker image
> - [workpress:6.3.2](https://hub.docker.com/_/wordpress)
> - [mysql:8.2.0](https://hub.docker.com/_/mysql)

<br>

# Setup and build project
## Configuration docker-compose
> - Change directory to `docker` folder
>   ```bash
>   cd docker/
>   ```
> - Copy environment file
>   ```bash
>   cp .env.example .env
>   ```
> - Change some environment variables

## Configuration WorkPress
> - You can configure WorkPress in `php.conf.ini` file

## Build and start docker-compose
> - Change directory to `docker` folder
>    ```bash
>    cd docker/
>    ```
> - Build docker-compose
>    ```bash
>    docker-compose build
>    ```
> - Up docker-compose
>     ```bash
>     docker-compose up -d
>     ```
> - Stop docker-compose
>     ```bash
>     docker-compose stop
>     ```

<br>

# Using Wordpress
> - Visit `http://localhost:[PORT]`
>   - `[PORT]` is set up in [.env file](#configuration-docker-compose)
> - Now you can first setup for wordpress
