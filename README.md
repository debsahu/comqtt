# comqtt Helm chart repository

Add this repo to Helm:

```sh
helm repo add comqtt https://debsahu.github.io/comqtt
helm repo update
helm search repo comqtt
```

The chart index is published automatically by the `chart-release` workflow on
`main` branch pushes that touch `deploy/helm/**`.
