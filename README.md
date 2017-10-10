[![tests][tests]][tests-url]

<div align="center">
  <img width="200" height="200"
    src="https://cdn.worldvectorlogo.com/logos/circleci.svg">
  <a href="https://github.com/easymetrics">
    <img width="200" height="200" vspace="" hspace="25"
      src="https://cdn.worldvectorlogo.com/logos/webpack-icon.svg">
  </a>
  <h1>CircleCI 2.0 JDK 8 build container</h1>
  <p>Docker Repository for the WebpackContrib Closure JDK8 test container.<p>
</div>

<h2 align="center">Usage</h2>

```bash
# config.yml
    docker:
      - image: webpackcontrib/circleci-node-jdk8
```

<h2 align="center">Container Includes</h2>

- CircleCI specific dependencies & runtime user configuration.
- Docker tooling ( Engine, Compose, Dockerize ).
- Node Version Manager ( Version defaults to node:latest )
- Google Closure Compiler
- Java JDK 8

> This container does not have a headless browser configuration

[tests]: https://circleci.com/gh/webpack-contrib/ccircleci-node-jdk8.svg?style=svg
[tests-url]: https://circleci.com/gh/webpack-contrib/circleci-node-jdk8
