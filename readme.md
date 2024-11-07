# Kube/Docker

[How to Install Kubernetes (K8s) on Ubuntu 24.04](https://hostnextra.com/learn/tutorials/how-to-install-kubernetes-k8s-on-ubuntu)

## Docker & Kubectl

🚢 [c53c2df](https://github.com/arafatm/learn.pulumi/commit/c53c2df) 
> `sudo apt update sudo apt upgrade -y`

🚢 [4a112c8](https://github.com/arafatm/learn.pulumi/commit/4a112c8)
> `sudo apt install -y docker.io`

🚢 [883dfc7](https://github.com/arafatm/learn.pulumi/commit/883dfc7)
> `sudo docker --version`  
> #> Docker version 24.0.7, build 24.0.7-0ubuntu4.1

###### [Install and Set Up kubectl on Linux | Kubernetes](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/#install-using-native-package-management)

```bash
curl -fsSL https://pkgs.k8s.io/core:/stable:/v1.31/deb/Release.key | sudo gpg --dearmor -o /etc/apt/keyrings/kubernetes-apt-keyring.gpg  
sudo chmod 644 /etc/apt/keyrings/kubernetes-apt-keyring.gpg # allow unprivileged APT programs to read this keyring  
echo 'deb [signed-by=/etc/apt/keyrings/kubernetes-apt-keyring.gpg] https://pkgs.k8s.io/core:/stable:/v1.31/deb/ /' | sudo tee /etc/apt/sources.list.d/kubernetes.list  
sudo chmod 644 /etc/apt/sources.list.d/kubernetes.list # helps tools such as command-not-found to work correctly  

sudo apt update  
sudo apt install -y kubelet kubeadm kubectl
sudo apt-mark hold kubelet kubeadm kubectl

# Kubernetes requires swap to be disabled.
sudo swapoff -a 
sudo sed -i '/ swap / s/^\(.*\)$/#\1/g' /etc/fstab
```

## Pulumi

🚢 [81af0e3](https://github.com/arafatm/learn.pulumi/commit/81af0e3) 
> `curl -fsSL https://get.pulumi.com | sh`

> pulumi version


🚢 [9046e20](https://github.com/arafatm/learn.pulumi/commit/9046e20) 
```bash
`${lastcommand}`
```

🚢 [9046e20](https://github.com/arafatm/learn.pulumi/commit/9046e20) 
```bash
`${lastcommand}`
```

xxx
