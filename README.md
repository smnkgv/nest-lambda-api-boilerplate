## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository with pre-installed serverless framework. It allows to deploy the code based on this template as AWS Lambdas.

## Installation

```bash
$ yarn install
$ yarn build
```

## Running the app in dev env

```bash
$ sls offline
$ curl http://localhost:3000/dev/hello
```

## Running the app in prod env

```bash
$ yarn build
$ sls deploy
$ curl https://xxxyyyzzz.execute-api.eu-west-1.amazonaws.com/dev/hello
```

## Running the app offline

```bash
$ sls offline
```

## Author
Glib Semenyuk (smnk.gv@gmail.com)
