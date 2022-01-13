## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add nginx-chart-test https://avrhamneeman.github.io/AviChart

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
nginx-chart-test` to see the charts.

To install the nginx-chart-test chart:

    helm install my-nginx-chart-test nginx-chart-test/nginx-chart-test

To uninstall the chart:

    helm delete my-nginx-chart-test
