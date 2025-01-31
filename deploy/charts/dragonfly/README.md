# Dragonfly

## Install

Install with Helm 3:

```bash
helm install dragonfly https://github.com/dragonfly/Dragonfly2/releases/download/v0.1.0-beta/dragonfly-chart.tgz
```

## Uninstall

```bash
$ helm delete dragonfly
release "dragonfly" uninstalled
```

## [TODO] Configuration

The following table lists the configurable parameters of the dragonfly chart, and their default values.

| Parameter                                 | Description                                                  | Default                       |
| ----------------------------------------- | ------------------------------------------------------------ | ----------------------------- |
| `installation.jaeger`                     | whether enable an all in one jaeger for tracing              | `false`                       |

Specify each parameter using the `--set key=value[,key=value]` argument to `helm install`.

For example:

```shell
helm install --namespace dragonfly-system dragonfly https://...
```

## Reference

[https://github.com/openkruise/kruise/blob/master/charts/kruise/v0.9.0/README.md](https://github.com/openkruise/kruise/blob/master/charts/kruise/v0.9.0/README.md)
