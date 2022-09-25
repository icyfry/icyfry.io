# Source code of [icyfry.io](https://www.icyfry.io)

[![Build and deploy](https://github.com/icyfry/icyfry.io/actions/workflows/deploy-prod.yml/badge.svg?branch=main)](https://github.com/icyfry/icyfry.io/actions/workflows/deploy-prod.yml) <img src="https://img.shields.io/github/languages/top/icyfry/icyfry.io" />

## Development

Use `.env.local` based on `.env` and `task build deploy-prod` to deploy website

* Launch local development `task dev`
* Compiles and minifies for production `task build`
* Deploy to cloud prod and staging `task build deploy-prod` or `task build deploy-staging`

## Tools

* [vue.js](https://fr.vuejs.org/index.html)
* [taskfile.dev](https://taskfile.dev/#/installation)
* [act](https://github.com/nektos/act)