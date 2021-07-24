FROM openapitools/openapi-generator-cli:latest AS build

ADD klauke-enterprises-api.v3.yaml openapi.yaml

RUN /usr/local/bin/docker-entrypoint.sh generate -i openapi.yaml -g openapi

FROM swaggerapi/swagger-ui:latest AS ui

COPY --from="build" openapi.json /app/swagger.json
