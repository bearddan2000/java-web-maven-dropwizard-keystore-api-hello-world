# java-web-maven-dropwizard-keystore-api-hello-world

## Description
A POC for dropwizard api with self-signed ssl.

## Tech stack
- java
- maven
  - dropwizard

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- Endpoints
  - [No args](https://localhost/hello-world)
  - [Single args](https://localhost/hello-world?name=Steve)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code based on](https://howtodoinjava.com/dropwizard/tutorial-and-hello-world-example/)
- [SSL code](https://github.com/dropwizard/dropwizard/tree/master/dropwizard-example)
