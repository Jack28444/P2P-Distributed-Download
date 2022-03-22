# P2P-Distributed-Download

## Installation
Clone and install project dependecies using npm or yarn

```yarn install```

once that is done you can run it on youtr local machine

```yarn start```

## Development
you can run the project in dev mode including both server and front-end code

``` yarn dev ```

you can also run the client or the server independently in dev mode

```yarn dev:client```

```yarn dev:server```

## Simulate the multipe-node environment with Docker
Create an ubuntu virtual machine, install docker and nodejs14, then create 1 server and 3 clients in docker
(Install docker engine and docker compose before start)

Build the docker images

```./build_client.sh ```

```./build_server.sh ```

Launch a signaling server and 3 clients

``` docker-compose up```

To access the clients, open a browser window and visit the following URLs:

1. localhost:3010
1. localhost:3020
1. localhost:3030
