[![Powered By Vaadin on Kotlin](http://vaadinonkotlin.eu/iconography/vok_badge.svg)](http://vaadinonkotlin.eu)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin-flow/Lobby#?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# Bookstore App Starter for Vaadin

A project example for a Vaadin application that only requires a Servlet 3.1 container to run (no other JEE dependencies). The UI is built with Kotlin only.

The easiest way of using it is simply to git-clone this repository:

```bash
git clone https://github.com/mvysny/bookstore-vok
cd bookstore-vok
./gradlew clean appRun
```

The Bookstore Example will be running on http://localhost:8080

## Live Demo

The [Live Demo of Bookstore-VOK](https://bookstore-vok.herokuapp.com/) is running on Heroku.

## Prerequisites

The project can be imported into the IDE of your choice, with Java 8 installed, as a Gradle/Kotlin project.

## Workflow

To compile the entire project, run `./gradlew` in the parent project.

Other basic workflow steps:

- getting started
- compiling the whole project
  - run `./gradlew` in parent project
- developing the application
  - edit code
  - run `./gradlew appRun`
  - open http://localhost:8080/

## Links

The project uses the following libraries:

* Based on the [Vaadin-on-Kotlin](http://vaadinonkotlin.eu) framework.
* [Karibu-Testing](https://github.com/mvysny/karibu-testing) for testing
* [vok-security](https://github.com/mvysny/vaadin-on-kotlin/tree/master/vok-security) for enforcing user security
* [Vaadin](https://vaadin.com/docs/v10) for the UI
