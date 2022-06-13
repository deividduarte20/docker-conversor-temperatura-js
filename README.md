# docker-conversor-temperatura-js

## Esse projeto disponibiliza uma aplicação de conversão de temperatura desenvolvida em javascript

## Requisitos

| npm | nodejs | docker |
|-----|--------|--------|

## Para buildar imagem
docker image build -t conversao-temperatura .

## Para subir container
docker run -dti -p 8080:8080 conversao-temperatura
