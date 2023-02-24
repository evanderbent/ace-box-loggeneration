# ace-box-loggeneration

This ACE-BOX external use case is an example on how to get an easy sandbox running with EasyTravel deployed!

## Components deployed

The following components get deployed:

- microk8s
- Dynatrace Operator with OneAgent and Kubernetes ActiveGates
- Dynatrace Monaco CLI
- EasyTravel demo application exposed via the Kubernetes Ingress Controller
- EasyTrade demo application exposed via the Kubernetes Ingress Controller
- Hipstershop demo application exposed via the Kubernetes Ingress Controller
- Monitoring as Code configuration is applied
- Dashboard with predefined links

## Running the sandbox

Check out [ace-box documentation](https://github.com/Dynatrace/ace-box/blob/dev/docs/external-use-case.md) for more information and provite this git repo URL as the use-case!

```
use_case="https://github.com/evanderbent/ace-box-sandbox-loggeneration.git"
```
