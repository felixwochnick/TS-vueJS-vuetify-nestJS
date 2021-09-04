# vueJS-vuetify-nestJS

Template with frontend and backend for Linux/Unix + Docker

## Requires (tested)

- nodejs@14.17.4 or higher
- yarn@1.22.11 or higher
- @vue/cli@4.5.13 or higher
- nest@8.1.0 or higher

__Test and Build__

- docker@20.10.8 or higher
- bash@5.0.17(1)-release or higher

## Frontend (Vue2)

```sh
# open the frontend folder
cd frontend

# test only forntend
yarn serve
```

## Backend (NestJS + GarphQL Client + basic auth service)

```sh
# open the backend folder
cd backend

# test only backend
yarn start:dev
```

## Test
```sh
sh test.sh # Test runs at Port 8080

# or 

sh test.sh 5000 # Test runs at Port 5000
```
## Production Build

```sh
sh production.sh
```