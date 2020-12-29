Content obtained from,

git clone https://github.com/containous/traefik-helm-chart
helm template traefik-helm-chart/traefik  --name-template vera --values values.yaml --namespace=traefik-v2 --output-dir .
