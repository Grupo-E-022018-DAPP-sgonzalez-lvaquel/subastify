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

Set environment variables

``` bash
AUTH_DOMAIN="<domain>"
AUTH_CALLBACK_URL="http://localhost:3000/auth"
AUTH_CLIENT_ID="<client_id>"
```

Bootstrap dependencies

``` bash
lerna bootstrap
```

Start Dev Server

``` bash
lerna run development
```
