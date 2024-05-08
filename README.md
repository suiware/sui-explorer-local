# Sui Explorer for Localnet

Uses an unofficial fork of the Sui Explorer https://github.com/kkomelin/sui-explorer/tree/after-fork

## Requirements

- [Docker](https://docs.docker.com/engine/install/)

## Install

```bash
git clone kkomelin/sui-explorer-docker
```

## Use

Go to the folder:

```bash
cd sui-explorer-docker
```

Run it:

```bash
docker compose up -d
```

Open it:

[http://localhost:9001/](http://localhost:9001/)


## Other commands

Stop it:

```bash
docker compose stop
```

Rebuild the container in case of any issues:

```bash
docker compose up -d --force-recreate --build
```
