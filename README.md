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

## Configuration

[Marquez](https://github.com/MarquezProject/marquez) **parameters**

| Parameter                  | Description       | Default   |
|----------------------------|-------------------|-----------|
| `marquez.image.repository` | Marquez image     | `marquez` |
| `marquez.image.tag`        | Marquez image tag | `0.10.2`  |

[Marquez Web UI](https://github.com/MarquezProject/marquez-web) **parameters**

| Parameter              | Description              | Default       |
|------------------------|--------------------------|---------------|
| `web.image.repository` | Marquez Web UI image     | `marquez-web` |
| `web.image.tag`        | Marquez Web UI image tag | `0.3.0`       |