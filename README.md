Add the repo kong:
$ helm repo add kong https://charts.konghq.com
$ helm repo update

Install kong:
$ helm install kong/kong --generate-name

Add the repo konga:
$ helm repo add konga https://lakshanmamalgaha96.github.io/konga-helm

Install konga:
$ helm install my-konga konga/konga --version 1.1.0
