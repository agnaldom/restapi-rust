# restapi-rust
Este projeto foi criado para estudo rust, foi um api rest usando a linguagem Rust

## Build a CRUD API with Rust
Para escrever api em rust é mas complicado do que escrever com nodejs ou golang.

## Frameworks
Frameworks que serão usados para auxiliar no projeto
* [Rocket]{https://rocket.rs/}  --  web framework for writing fast web applications
* [Serde ] {https://serde.rs/} -- framework for serializing and deserializing Rust data structures
* [Diesel ]{http://diesel.rs/} -- safe, extensible ORM and query builder

## Criando o projeto
Crie o projeto usando o gerenciador de depencia cargo
```
$ cargo new hero-api
```

Depois siga o processo, por que Rocket requer que use   a versão nightly do Rust.

```
$ rustup default nightly
$ rustup update && cargo update
```