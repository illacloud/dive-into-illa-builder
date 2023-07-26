<div align="center">
  <a href="https://cloud.illacloud.com/">
    <img alt="ILLA Design Logo" width="120px" height="120px" src="https://github.com/illacloud/.github/blob/main/assets/images/illa-logo.svg"/>
  </a>
</div>

<h1 align="center"><a href="https://cloud.illacloud.com/">Dive into ILLA Builder</a> </h1>

<p align="center">Wanna modify illa-builder by yourself? Check out this repo! </p>


<p align="center">
  <a href="https://discord.gg/illacloud"><img src="https://img.shields.io/badge/chat-Discord-7289DA?logo=discord" height=18></a>
  <a href="https://twitter.com/illacloudHQ"><img src="https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&logoColor=white" height=18></a>
  <a href="https://github.com/orgs/illacloud/discussions"><img src="https://img.shields.io/badge/discussions-GitHub-333333?logo=github" height=18></a>
  <a href="./LICENSE"><img src="https://img.shields.io/github/license/illacloud/illa-builder" height=18></a>
</p>



## 🚀Get Started

illa-builder consists of these parts, which are:
- illa-builder (the whole frontend project)
- illa-builder-backend (for managing apps , resources, and actions)
- illa-builder-backend-ws (for managing WebSocket connection)
- illa-supervisor-backend (for managing user info and ABAC)
- illa-supervisor-backend-internal (for illa-builder-backend fetch info which in illa-supervisor-backend)

And the add-ons include:
- nginx (for serving the illa-builder)
- envoy (as all units ingress)
- minio (storage user avatar etc)
- redis (for cache and user session storage)
- postgres (for all data storage)


## ✨ Index

- The Design Documents List 
  - [illa-builder Design Documents]()
  - [illa-builder-backend Design Documents]()
  - [illa-supervisor-backend Design Documents]()
  - [illa-cli Design Documents]()

- The API Documents List
  - [illa-builder-backend HTTP API Documents](https://github.com/illacloud/illa-builder-backend-api-docs)
  - [illa-builder-backend WebSocket Message Documents](https://github.com/illacloud/illa-builder-backend-weosocket-docs)
  - [illa-supervisor-backend HTTP API Documents](https://github.com/illacloud/illa-supervisor-backend-api-docs)

- The Database Schema Design and DDLs
  - [illa-builder-backend Database Design](https://github.com/illacloud/illa-builder-backend-database-design-docs)
  - [illa-supervisor-backend Database Design](https://github.com/illacloud/illa-supervisor-database-design-docs)

- The Docker Image Building & Build Locally Documents List
  - [build-all-in-one-image (build your own illa-builder image by type ```make build```)](https://github.com/illacloud/build-all-in-one-image)
  - [deploy-illa-manually (deploy on local machine, docker, docker-compose, k8s)](https://github.com/illacloud/deploy-illa-manually)

## License

This project is [Apache License 2.0](./LICENSE).
