# parcel-locker-api

> Go REST API that unifies Omniva, DPD and LP Express parcel lockers in Lithuania with nearest-locker search — PostgreSQL + PostGIS, sqlc, OpenAPI.

![status](https://img.shields.io/badge/status-in%20progress-yellow) ![area](https://img.shields.io/badge/area-Golang-blue) ![license](https://img.shields.io/badge/license-MIT-green)

🚧 **Work in progress.** This repo is part of my public learning roadmap (**Phase 1 — Python & Go foundations**). I build in the open — follow the commits and the roadmap below.

## Why this project

Learn Go by solving a problem every Baltic e-shop has: one API for all parcel-locker networks, with distance search.

## What I'm learning

- Go fundamentals and idiomatic project layout
- HTTP services with `net/http` / `chi`, middleware, graceful shutdown
- Type-safe SQL with `sqlc`, geo queries with PostGIS
- Table-driven tests and integration tests
- Writing an OpenAPI spec

## Planned stack

Go · chi · PostgreSQL + PostGIS · sqlc · Docker · GitHub Actions

## Roadmap

- [ ] Project layout, Makefile, linting (`golangci-lint`), CI
- [ ] Importer for the first carrier's public locker list
- [ ] PostGIS schema + `sqlc` queries
- [ ] `GET /lockers?near=lat,lng&radius=` endpoint
- [ ] Importers for the other carriers + scheduled refresh
- [ ] Table-driven and integration tests
- [ ] OpenAPI spec + Docker image
- [ ] README with example requests and benchmarks

## Part of a 10-repo learning roadmap

I'm a full-stack developer in Vilnius ([armansalek.com](https://armansalek.com)) growing into **Python, Go, DevOps, cloud and AI engineering**. These repos connect: the Python and Go services are containerised, deployed and monitored by the DevOps and cloud repos, and the AI projects run on that infrastructure.

| # | Repo | Area | Phase |
|---|---|---|---|
| 1 | [lt-jobs-scraper](https://github.com/arman-aru/lt-jobs-scraper) | Python | 1 |
| 2 | [lt-vocab-api](https://github.com/arman-aru/lt-vocab-api) | Python | 1 |
| 3 | **parcel-locker-api** (this repo) | Golang | 1 |
| 4 | [go-uptime](https://github.com/arman-aru/go-uptime) | Golang | 1 |
| 5 | [ci-cd-pipelines](https://github.com/arman-aru/ci-cd-pipelines) | DevOps | 2 |
| 6 | [k8s-gitops-lab](https://github.com/arman-aru/k8s-gitops-lab) | DevOps | 2 |
| 7 | [terraform-aws-platform](https://github.com/arman-aru/terraform-aws-platform) | Cloud Computing | 3 |
| 8 | [serverless-media-pipeline](https://github.com/arman-aru/serverless-media-pipeline) | Cloud Computing | 3 |
| 9 | [site-audit-agent](https://github.com/arman-aru/site-audit-agent) | AI Engineering | 4 |
| 10 | [migration-rag-assistant](https://github.com/arman-aru/migration-rag-assistant) | AI Engineering | 4 |

## License

[MIT](LICENSE) © Arman Salek
