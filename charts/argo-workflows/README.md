# argo-workflows

![Version: 3.4.7](https://img.shields.io/badge/Version-3.4.7-informational?style=flat-square)

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| https://argoproj.github.io/argo-helm | argo-workflows | 0.27.0 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| applicationSet.replicaCount | int | `1` |  |
| controller.replicas | int | `1` |  |
| redis-ha.enabled | bool | `false` |  |
| repoServer.replicas | int | `1` |  |
| server.replicas | int | `1` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)
