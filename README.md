# parcel-locker-api

> Go REST API that unifies Omniva, DPD and LP Express parcel lockers in Lithuania with nearest-locker search — PostgreSQL + PostGIS, sqlc, OpenAPI.

![status](https://img.shields.io/badge/status-in%20development-yellow) ![license](https://img.shields.io/badge/license-MIT-green)

## Overview

One API for every parcel-locker network in Lithuania. It imports Omniva, DPD and LP Express locker locations and answers "which lockers are nearest to this address?" with fast geo queries.

## Features

- Importers for Omniva, DPD and LP Express locker data with scheduled refresh
- `GET /lockers?near=lat,lng&radius=` nearest-locker search
- Filter by carrier, city and locker type
- Geo queries with PostgreSQL + PostGIS
- OpenAPI specification
- Small Docker image

## Tech stack

Go · chi · PostgreSQL + PostGIS · sqlc · Docker · GitHub Actions

## License

[MIT](LICENSE) © Arman Salek
