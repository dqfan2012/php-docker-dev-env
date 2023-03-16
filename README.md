# Simple PHP Docker Development Environment

This is a simple PHP Docker development environment. It defines the following containers:

1. nginx - latest version
2. php-fpm - latest version
3. Postgresql - latest version
4. Redis - latest version

Port 9000 of the php-fpm container is exposed to allow for X-Debug debugging.

## Prerequisites

 - You need to clone this repo.
 - You need to have `git` and `Docker Desktop` installed.
    - On Windows, you'll need to install WSL.

I'm not going to provide instructions telling you how to install `git` or `Docker Desktop`. You can find instructions online using a search engine like Google or Bing. Alternatively, you can probably find videos on YouTube explaining the process for both.

I'm assuming you have basic knowledge of command-line commands. Additionally, I'm assuming you know that Docker Desktop must be running in order to run docker containers. I'm not going to explain either of these things. You can research, if needed, to learn how.

## Cloning this repo

Choose a location on your computer or workstation to clone this repo.

**Via SSH**

```bash
git clone git@github.com:dqfan2012/php-docker-dev-env.git
```

**Via HTTPS**

```bash
git clone https://github.com/dqfan2012/php-docker-dev-env.git
```

## Running the docker containers

After you've changed directories to the root directory of this project, you can run the following command to get the containers running.

```bash
docker-compose up -d
```

You may stop the containers with the following command:

```bash
docker-compose stop
```

You can read Docker documentation or search online to learn more about using Docker properly.

