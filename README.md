# hola-mundo

A Docker "Hello world!" in Rust

## Build & Run
`docker build -t hola-mundo .`

`docker run --name holam hola-mundo`

## Clean
`docker rm -f holam && docker rmi -f hola-mundo`

&nbsp;

## Build & Run & Clean Together
`
docker build -t hola-mundo . && 
docker run --name holam hola-mundo && 
docker rm -f holam && docker rmi -f hola-mundo
`


-----

Learning Docker