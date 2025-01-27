# Order MS

![Badge](https://img.shields.io/static/v1?label=author&message=DanielHessel&color=0070f3&style=flat&logo=<LOGO>)
![Badge](https://img.shields.io/static/v1?label=status&message=Done&color=success&style=flat&logo=<LOGO>)
![Badge](https://img.shields.io/static/v1?label=license&message=MIT&color=0070f3&style=flat&logo=<LOGO>)

Microservice capable of processing requests from a RabbitMQ queue with Java and Spring Boot API.

## :pushpin: Table of contents

<!--ts-->

- [Technologies](#zap-technologies)
- [Getting started](#computer-getting-started)
- [How to run](#information_source-how-to-run)
- [How to contribute to the project](#tada-how-to-contribute-to-the-project)
- [License](#page_facing_up-license)
<!--te-->

## :zap: Technologies

This project was developed with the following technologies:

- [Java](https://www.oracle.com/br/java/)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [RabbitMQ](https://www.rabbitmq.com/)
- [MongoDB](https://www.mongodb.com/)

## :computer: Getting started

Before you begin, you will need to have the following tools installed on your machine:

- [Git](https://git-scm.com)

- [Java v21.0.5](https://www.oracle.com/br/java/technologies/downloads/#java21) or heigher.

Docker is a containerization tool where we will be able to eliminate project configuration tasks between different machines and guarantee a development environment as close as possible to the production environment.

- [Docker](https://docs.docker.com/get-docker/)

Compose is a tool for defining and running multi-container Docker applications. And in this scenario, we will use it to automate the execution of our API container next to the database.

- [Docker Compose](https://docs.docker.com/compose/install/)

Also, it’s good to have an editor to work with the code like [IntelliJ IDEA Community](https://www.jetbrains.com/idea/).

## :information_source: How to run

Follow the instructions below to download and use the project from this repository:

Clone this repository using SSH:

```bash
git clone git@github.com:danielhessell/orderms-java-api.git
```

or clone using https:

```bash
git clone git@github.com:danielhessell/orderms-java-api.git
```

Go to project folder in terminal/cmd:

```bash
cd orderms-java-api
```

Run project:

```bash
docker compose up
```

To stop project:

```bash
docker compose down
```

And Run project with your IDE.

The server will start on port 8080. Go to http://localhost:8080/.

## :tada: How to contribute to the project

1. Fork the project
2. Create a new branch with your changes: `git checkout -b my-feature`
3. Save the changes and create a commit message telling what you've done: `git commit -m "feature: My new feature"`
4. Submit your changes: `git push origin my-feature`

If you have any questions, check this out [guide on how to contribute to GitHub](https://github.com/firstcontributions/first-contributions).

## :page_facing_up: License

This project is under the Apache-2.0 license. See the [LICENSE](https://github.com/danielhessell/orderms-java-api/blob/master/LICENSE) file for more details.

---

Made with :blue_heart: by Daniel Hessel.
