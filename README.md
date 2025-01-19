# Helm Charts

This repository hosts [Helm](https://helm.sh) charts for use with Kubernetes.

## Usage

### Add via [OCI-based registry](https://helm.sh/docs/topics/registries/) **(recommended)**

```shell
helm registry login ghcr.io --username $GITHUB_ACTOR --password-stdin
```

### Add via traditional [chart repository](https://helm.sh/docs/topics/chart_repository/)

```shell
helm repo add dudo-home-lab https://dudo-home-lab.github.io/helm-charts/
helm repo update
```

## Support

### Kubernetes versions

The four latest versions of Kubernetes are tested (the versions of Kubernetes that are supported by the major cloud providers).
