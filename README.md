# rust-server-metrics-docker

A Docker (docker-compose) wrapper to spin up the needed Grafana and Influxdb instances (and other quirks) in order to run [Pinkstink-Rust/Rust-Server-Metrics](https://github.com/Pinkstink-Rust/Rust-Server-Metrics#rust-server-metrics).

## Prerequisites

- Install [Docker](https://docs.docker.com/engine/install/)
- Install [git](https://git-scm.com/downloads)
- /todo ???

## Build / Setup


Clone this repo:

```shell

```
/todo ???


Define `.env` file, and your own variables to override the grafana/influxdb ones. On the file write:

```
INFLUXDB_USERNAME=example-influxdb-username
INFLUXDB_PASSWORD=example-influxdb-password
GRAFANA_USERNAME=example-grafana-username
GRAFANA_PASSWORD=example-grafana-password
```

And then run `source .env`

## Run

/todo ???

Run:

```shell
docker-compose up -d
```

## Misc / Kudos

- Thank you [@Pinkstink-Rust](https://github.com/Pinkstink-Rust) for the awesome on [Rust-Server-Metrics](https://github.com/Pinkstink-Rust/Rust-Server-Metrics#rust-server-metrics).
- Thank you [@jkehres](https://github.com/jkehres) for providing the example docker-compose file in [jkehres/docker-compose-influxdb-grafana](https://github.com/jkehres/docker-compose-influxdb-grafana).