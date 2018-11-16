# Subastify

## Table of Contents

- [Development](#Development)

## Development

Install node

``` bash
nvm install 10.13.0 && nvm use 10.13.0
```

Install Lerna

``` bash
npm install -g lerna
```

Bootstrap dependencies

``` bash
lerna bootstrap
```

Build Packages

``` bash
lerna run build
```

Run Migrations

``` bash
lerna run migrate
```

Run Seeds to populate data bases

``` bash
lerna run seed
```

Start Dev Server

``` bash
lerna run development
```
