# Bi-frost helm

## Install cmd

```console
helm upgrade --install <release-name> <chart-location> --namespace <namespace> --set deploy.image.tag="<tag-name>",imgPullSecret="<image-pull-secret>"
```
