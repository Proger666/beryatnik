FROM kong:latest

ENV KONG_DATABASE=postgres \
    KONG_PG_HOST=kong-database \
    KONG_PASSWORD=1234567890

RUN kong migrations up