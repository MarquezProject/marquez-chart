# Marquez [Helm Chart](https://helm.sh)

[![status](https://img.shields.io/badge/status-WIP-yellow.svg)](#status)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/marquez-project/community)
[![license](https://img.shields.io/badge/license-Apache_2.0-blue.svg)](https://raw.githubusercontent.com/MarquezProject/marquez-chart/master/LICENSE)

Helm Chart for [Marquez](https://github.com/MarquezProject/marquez).

## Status

This chart is under active development at [WeWork](https://www.wework.com). 

## Installing

To install the chart with release `my-release`:

```bash
$ helm install --name my-release .
```

> 

## Uninstalling

To uninstall `my-release`:

```bash
$ helm install --name my-release .
```

## Configuration

[Marquez](https://github.com/MarquezProject/marquez) **parameters**

| Parameter                  | Description                      | Default                  |
|----------------------------|----------------------------------|--------------------------|
| `marquez.image.registry`   | Marquez image registry           | `docker.io`              |
| `marquez.image.repository` | Marquez image                    | `marquezproject/marquez` |
| `marquez.image.tag`        | Marquez image tag                | `0.10.2`                 |
| `marquez.image.pullPolicy` | Image pull policy                | `IfNotPresent`           |
| `marquez.db.enabled`       | Create a PostgreSQL database     | `false`                  |
| `marquez.db.host`          | PostgreSQL host                  | `nil`                    |
| `marquez.db.port`          | PostgreSQL port                  | `5432`                   |
| `marquez.db.name`          | PostgreSQL database              | `marquez`                |
| `marquez.db.user`          | PostgreSQL user                  | `buendia`                |
| `marquez.db.password`      | PostgreSQL password              | `macondo `               |

[Marquez Web UI](https://github.com/MarquezProject/marquez-web) **parameters**

| Parameter              | Description              | Default        |
|------------------------|--------------------------|----------------|
| `web.image.repository` | Marquez Web UI image     | `marquez-web`  |
| `web.image.tag`        | Marquez Web UI image tag | `0.3.0`        |
| `web.image.pullPolicy` | Image pull policy        | `IfNotPresent` |