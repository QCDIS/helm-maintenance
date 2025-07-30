# Maintenance page Helm Chart

This Helm Chart deploys a maintenance page and configures ingress rules.

## Usage

Deployment (simple):

```shell
helm -n maintenance upgrade --create-namespace --install maintenance ./chart -f my-values.yaml
```

Uninstall:

```shell
helm -n maintenance uninstall maintenance
```

## Acknowledgements

The Helm Chart is adapted from [CodeWithEmad/helm-charts](https://github.com/CodeWithEmad/helm-charts/).
The page is adapted from [tadwohlrapp/simple-maintenance-page](https://github.com/tadwohlrapp/simple-maintenance-page/).
The illustration is from [unDraw](https://undraw.co/).
