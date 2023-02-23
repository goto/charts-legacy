# Charts

Charts are curated application definitions for [Helm](https://github.com/helm/helm). For more information about installing and using Helm, see it's `README.md`.

## TL;DR

```bash
$ helm repo add gotocompany-legacy https://goto.github.io/charts-legacy/
$ helm search repo gotocompany-legacy
$ helm install my-release gotocompany-legacy/<chart>
```

## Repository Structure

This repository contains the source for the packaged and versioned legacy charts (released in the [Github Pages](https://goto.github.io/charts-legacy/)).
There may be previous versions of a Chart available in the Chart Repository.

## Usage

Once you have installed the Helm client on your kubernetes cluster, you can deploy a Helm Chart into a Kubernetes cluster.

Please refer to the [Quick Start guide](https://helm.sh/docs/intro/quickstart/) if you wish to get running in just a few commands, otherwise the [Using Helm Guide](https://helm.sh/docs/intro/using_helm/) provides detailed instructions on how to use the Helm client to manage packages on your Kubernetes cluster.

Helm Repo URL: `https://goto.github.io/charts-legacy/`

```bash
# To add Helm repo
$ helm repo add gotocompany-legacy https://goto.github.io/charts-legacy/

# To list all the charts in the repo
$ helm search repo gotocompany-legacy

# To install any searched chart
$ helm install my-release gotocompany-legacy/<chart>
```
