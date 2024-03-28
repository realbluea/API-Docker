# API-Ecommerce
This is a API inspirated on a video from Michelli Brito

I was trying to complain about doing my postgresql on docker but this mf whale is hard, so i'll leave what commands i used to create my database

sudo docker network create --driver bridge api-spring && sudo docker run --name postgres-api --network=api-spring -p 5433:5432 -e POSTGRES_PASSWORD=postgres -d postgres && sudo docker run --name my-pgadmin --network=api-spring -p 15432:80 -e PGADMIN_DEFAULT_EMAIL=kanyewest@gmail.com -e PGADMIN_DEFAULT_PASSWORD=vultures1 dpage/pgadmin4
