# ez Platform docker containers

A Proof-of-concept of a running ez platform application inside containers

## Getting started

1. Clone project
2. Copy your ez project into the `src` folder
3. Create custom `.env` file in the `docker` folder (check `.env.example` file)
4. Build docker container  ``` cd docker && docker-compose up -d```
5. Install composer dependencies via  `docker-compose exec -it composer install`
6. Import DB

Everything should be up and running and the page can be reached via localhost (127.0.0.1).

## Improvements

- Automatic composer install on container build
- Automatic DB import on container build  
