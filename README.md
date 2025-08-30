Task	Command Example
Debug render (for troubleshooting)	helm template myrelease "C:\Prabhakar\HELM\HelmChart" --values "C:\Prabhakar\HELM\HelmChart\values.yaml" --debug > output-debug.yaml
Preview using dry-run install	helm install myrelease "C:\Prabhakar\HELM\HelmChart" --values "C:\Prabhakar\HELM\HelmChart\values.yaml" --dry-run --debug
Lint the chart for issues	helm lint "C:\Prabhakar\HELM\HelmChart"
