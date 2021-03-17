# About
This is the ArgoCD chart for Energinet. 

# How to install
1. Create the namespace you want argocd to be deployed into
2. Install the chart while being in the chart/ directory with the following command: `helm install -n argocd argocd .`
3. Install the argocd CLI tool by following the guide [here](https://argoproj.github.io/argo-cd/cli_installation/)
4. Once deployed, follow the steps [here](https://argoproj.github.io/argo-cd/getting_started/) to connect to the UI

