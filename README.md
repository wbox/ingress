# ingress

>DISCLAIMER: This is a work in progress. Use at your own risk.

Self study on nginx ingress controller with Metallb as NLB on bare metal kubernetes in my home lab.

![Screenshot 2024-06-16 at 1 42 50 PM](https://github.com/wbox/ingress/assets/1964035/e9fec18e-ba80-4091-904f-2a156ea5a9cb)

# Artifacts
- [ArgoCD App manifest](https://github.com/wbox/ingress/blob/main/argocd/ingress-app.yaml)
- [App Kubernetes Manifests](https://github.com/wbox/ingress/tree/main/app)

# ToDo
- Use ArgoCD to deploy everything
- Add this readme as the page for the app
- Create a Helm to install the app
- Install ingress helm chart from my own repo
- Implement dymainc creation of certificates

# Stack
- [Kubernetes](https://kubernetes.io)
- [MetalLB](https://metallb.universe.tf)
- [NGINX](https://nginx.org/en/)
- [NGINX Ingress Controller](https://docs.nginx.com/nginx-ingress-controller/)
- [Kubernetes Ingress-Nginx Controller](https://kubernetes.github.io/ingress-nginx/)
- [ArgoCD](https://argo-cd.readthedocs.io/en/stable/)
