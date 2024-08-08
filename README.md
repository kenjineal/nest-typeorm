# 🗄️ Nest.js + TypeORM with a Custom Repository

[![MegaLinter](https://github.com/leosuncin/nest-typeorm-custom-repository/workflows/MegaLinter/badge.svg?branch=master)](https://github.com/leosuncin/nest-typeorm-custom-repository/actions/workflows/mega-linter.yml)
[![Tests](https://github.com/leosuncin/nest-typeorm-custom-repository/workflows/Tests/badge.svg?branch=master)](https://github.com/leosuncin/nest-typeorm-custom-repository/actions/workflows/tests.yml)
![Prettier](https://img.shields.io/badge/Code%20style-prettier-informational?logo=prettier&logoColor=white)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![HitCount](https://hits.dwyl.com/leosuncin/nest-typeorm-custom-repository.svg)](https://hits.dwyl.com/leosuncin/nest-typeorm-custom-repository)

> An example of how to use a custom repository of TypeORM within Nest.js  
> **🚨 NOTICE 🚨** this example now works with TypeORM v0.3.x for previous version check out [v1.0.0](https://github.com/leosuncin/nest-typeorm-custom-repository/tree/v1.0.0)

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

## Features

- [TypeORM](https://typeorm.io/) with custom repository
- Unit tests and E2E tests
- Check code quality with [MegaLinter](https://oxsecurity.github.io/megalinter/latest/)
- Run tests with [github actions](.github/workflows/tests.yml)

## Run Locally

Clone the project

```bash
  git clone https://github.com/leosuncin/nest-typeorm-custom-repository.git
```

Go to the project directory

```bash
  cd nest-typeorm-custom-repository
```

Install dependencies

```bash
  yarn install
```

Start the server

```bash
  yarn start:dev
```

## Running Tests

To run unit tests, run the following command:

```bash
  pnpm test
```

To run e2e tests (the MySQL instance must be available), run the following command:

```bash
  pnpm test:e2e
```
