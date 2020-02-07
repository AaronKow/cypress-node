# aaronkow/cypress-node:11.13.0

This dockerfile is created to suit the use case for Cypress under OS: Debian + Node v11.13.0

Read [Run Cypress with a single Docker command](https://www.cypress.io/blog/2019/05/02/run-cypress-with-a-single-docker-command/)

```shell
$ docker run -it -v $PWD:/e2e -w /e2e --entrypoint cypress aaronkow/cypress-node:latest --version
Cypress package version: 3.8.3
Cypress binary version: 3.8.3
```