# Jokeish

A sample Golang / Gin / React application, based on the original tutorial [here](https://hakaselogs.me/2018-04-20/building-a-web-app-with-go-gin-and-react)

## Dependencies

Install with:

```
go get -u github.com/gin-gonic/gin
go get -u github.com/gin-gonic/contrib/static
go get -u github.com/auth0/go-jwt-middleware
go get -u github.com/dgrijalva/jwt-go
```

## Auth0

Go to [Auth0](https://auth0.com/signup)'s site, signup and create an API. Take note of the data.

## Configure

```
cp .env.example .env
cp views/js/env.jsx.example views/js/env.jsx
```

Edit the new files and replace the values to the ones that Auth0 provided when creating the API.

## Run!

```
go run main.go
```