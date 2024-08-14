# OpenNavigator Helm charts

This repository contains [Helm](https://helm.sh/) charts for OpenNavigator project.

## Usage

Helm must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```bash
helm repo add opennavigator https://opennavigator.github.io/helm-charts
```

## Helm Charts

You can then run helm search repo open-insight to see the charts.

### OpenNavigator

The chart can be used to install [OpenNavigator](https://github.com/openinsight-proj/OpenNavigator) in a Kubernetes cluster. More detailed documentation can be found in [OpenNavigator chart directory](./charts/opennavigator/README.md).
