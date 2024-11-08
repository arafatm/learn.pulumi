# Kube/Docker

[How to Install Kubernetes (K8s) on Ubuntu 24.04](https://hostnextra.com/learn/tutorials/how-to-install-kubernetes-k8s-on-ubuntu)

## Docker 

🚢 [c53c2df](https://github.com/arafatm/learn.pulumi/commit/c53c2df) 
> `sudo apt update sudo apt upgrade -y`

🚢 [4a112c8](https://github.com/arafatm/learn.pulumi/commit/4a112c8)
> `sudo apt install -y docker.io`

🚢 [883dfc7](https://github.com/arafatm/learn.pulumi/commit/883dfc7)
> `sudo docker --version`  
> #> Docker version 24.0.7, build 24.0.7-0ubuntu4.1

## minikube (kubernetes) on Linux

[minikube start | minikube](https://minikube.sigs.k8s.io/docs/start/?arch=%2Flinux%2Fx86-64%2Fstable%2Fbinary+download#LoadBalancer)

🚢 [987f397](https://github.com/arafatm/learn.pulumi/commit/987f397) 
```bash
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube 
rm minikube-linux-amd64
```

xxx

## Pulumi

🚢 [81af0e3](https://github.com/arafatm/learn.pulumi/commit/81af0e3) 
```bash
curl -fsSL https://get.pulumi.com | sh
source .bashrc
pulumi version                          # $v3.138.0
```

🚢 Set up Kubectl
```bash
kubectl config set-context pulumi --cluster=pulumi --namespace=pulumi --user=pulumi
kubectl config use-context pulumi
```

🚢 [2522187](https://github.com/arafatm/learn.pulumi/commit/2522187) 
```bash
pulumi install
pulumi new kubernetes-go
pulumi up
```



