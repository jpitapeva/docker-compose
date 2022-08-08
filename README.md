# docker-compose
docker-compose postgres




version: '3.1'

services:
  postgresdb:
    image: postgres
    environment:
      POSTGRES_PASSWORD: "12345"
    ports:
      - "5432:5432"
    volumes:
      - ./postgres:/var/lib/postgresql/data
      
      
      
  command 
  docker-compose up --build
  docker-compose up -d --build
