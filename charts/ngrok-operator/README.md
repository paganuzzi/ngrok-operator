# ngrok-operator charts
Helm repository for the arm version of ngrok-operator, a fork of zufardhiyaulhaq/ngrok-operator

### Installing the charts
```
helm repo add paganuzzi https://paganuzzi.github.io/ngrok-operator/
helm install paganuzzi/ngrok-operator --name-template ngrok-operator
```

### Configuration

| Parameter | Description | Default |
|-|-| -|
| operator.image | Image for ngrok-operator | ghcr.io/paganuzzi/ngrokoperator:latest |
| operator.tag | Tag for image ngrok-operator | 0.0.2 |
| operator.pullPolicy | pullPolicy | Always |
| operator.replica | number of replica | 1 |

Specify each parameter using the `--set key=value[,key=value]` argument to helm install.
