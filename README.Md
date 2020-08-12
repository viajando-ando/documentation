## Documentation

In this project explain all about of this project

## You can view the project in the next URL or [live demo](https://viajando-ando.dflores.dev/):

#### `https://viajando-ando.dflores.dev/`

#### Frontend

- [Full Documentation](https://github.com/viajando-ando/viajando-ando-frontend/blob/dev/README.md)
- [Live Demo](https://viajando-ando.dflores.dev/)

#### Backend

- [Full Documentation](https://github.com/viajando-ando/viajando-ando-backend/blob/dev/README.md)
- [Live Demo](https://viajando-ando-ykmiteeaiq-uc.a.run.app/)
- Endpoint
  - `GET /api/travels/:number`: return 10 travel by page
  - `GET /api/travels/count-cities`: count travels by city
  - `POST /api/travels/`: add travel
  - `PATCH /api/travels/`: update travel
  - `POST /api/travels/upload`: upload a file json with travels
  - `GET /api/travels/count`: return total of travels

## Architecture of backend

The design of backend it's like to components, this "boxes" have the all necessary to work or become to microservices, the transition and scaling are easy.

![](https://drive.google.com/uc?export=view&id=1yLX5hwq8eyKn_fjymdA68IUR9ri0M0C6)

## General architecture

Frontend its made in react and deployed in firebase, firebase gives us an ssl

The server in NodeJS with Typescript is built with docker, build a image and pushed to container registry after it's used in cloud run to deploy and expose the service and endpoint

![](https://drive.google.com/uc?export=view&id=1tMI4KTOaeYYcRL3czGL8-l96RyyyDvCw)

## Data arquitecture

[Example of dataset]('./data.json') in database

## Database

The database is hosted in Mongodb Atlas, tell me if you wish the credential :wink:

#### `It's a big scalable solution`

## Follow me [dflores.dev](https://dflores.dev)

### Anywhere @dfloresdev
