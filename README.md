# OpenAPI Generator for the default library

Welcome to he main repository of the klauke enterprises api. From here all work on the public
api is managed.

## Documentation

The documentation website lives at the [docs](docs) folder. 

You can find a fair amount of guidelines and general info at the API Design Section.

Relevant links:
- [Download](https://docs.api.klauke-enterprises.com/klauke-enterprises-api.v3.yaml) latest Specification 
- Access the Specification in our [Editor](https://docs.api.klauke-enterprises.com/editor)
- View Specification in as Swagger UI [Docs](https://docs.api.klauke-enterprises.com/)

## Build Status
| Build Status 	| GitHub Release                                                                                                                                                                            	| OpenAPI Generator / Publishing                                                                                                                                                                                 	| Docker                                                                                                                                                                          	|
|--------------	|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| main         	| [![GitHub Release](https://github.com/klauke-enterprises/protocol/actions/workflows/release.yml/badge.svg)](https://github.com/klauke-enterprises/protocol/actions/workflows/release.yml) 	| [![OpenAPI Generator](https://github.com/klauke-enterprises/protocol/actions/workflows/openapi-generate.yml/badge.svg)](https://github.com/klauke-enterprises/protocol/actions/workflows/openapi-generate.yml) 	| [![Docker](https://github.com/klauke-enterprises/protocol/actions/workflows/docker.yml/badge.svg)](https://github.com/klauke-enterprises/protocol/actions/workflows/docker.yml) 	|

## API Design

You may consider the following tips when working on this api:
- We're mainly using [Stoplight Studio](https://stoplight.io/studio/) for API work

## Third party APIs

This api anticipates the usage of some third party tools. The authentication is built with [FusionAuth](https://fusionauth.io/) or
any other oauth2 / openid compatible authentication endpoint in mind.

## Docker

We provide some docker image for maintenance and convenience:

| Docker Image                                                                                        	| Description                                                                                                                                                                                        	|
|-----------------------------------------------------------------------------------------------------	|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| [klauke-enterprises/swagger-editor](https://github.com/klauke-enterprises/protocol/packages/912109) 	| Provides the Klauke Enterprises API Specification bundled into a swagger editor for easy editing. You can just spin up the editor and begin working on our api spec.                               	|
| [klauke-enterprises/swagger-cli](https://github.com/klauke-enterprises/protocol/packages/912078)    	| Provides the Klauke Enterprises API Specification bundled into a swagger cli container. This is a great starting point if you want to generate non-standard api clients or use foreign generators. 	|
| [klauke-enterprises/swagger-ui](https://github.com/klauke-enterprises/protocol/packages/912079)     	| Provides the Klauke Enterprises API Specification bundled into a swagger ui container. You can spin up this container for using swagger ui or just looking at it.                                  	|
| [klauke-enterprises/redoc](https://github.com/klauke-enterprises/protocol/packages/912110)          	| Provides the Klauke Enterprises API Specification bundled into a redoc container. This is an alternative visualization of the API.                                                                 	|

## Maintainers

- Felix Klauke <[felix@klauke-enterprises.com](mailto:felix@klauke-enterprises.com)>
