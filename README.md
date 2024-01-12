Add the repo kong:
$ helm repo add kong https://charts.konghq.com
$ helm repo update

Install kong:
$ helm install kong/kong --generate-name
