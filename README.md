# Helm Charts

> Collection of Helm Charts that allow for easy deployment of applications onto a Kubernetes Cluster, these charts
> follow best-practise and security policies.

## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

`helm repo add mhuzaifahkhan https://mhuzaifahkhan.github.io/helm-charts`

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo mhuzaifahkhan` to see the charts.

To install the `grafana-agent` chart:

`helm install grafana-agent mhuzaifahkhan/grafana-agent`

To uninstall the chart:

`helm delete grafana-agent`
