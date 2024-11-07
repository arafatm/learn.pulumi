# Kube/Docker

[How to Install Kubernetes (K8s) on Ubuntu 24.04](https://hostnextra.com/learn/tutorials/how-to-install-kubernetes-k8s-on-ubuntu)

###### Docker

🚢 [c53c2df](https://github.com/arafatm/learn.pulumi/commit/c53c2df) 
> `sudo apt update sudo apt upgrade -y`

🚢 [4a112c8](https://github.com/arafatm/learn.pulumi/commit/4a112c8)
> `sudo apt install -y docker.io`

🚢 [883dfc7](https://github.com/arafatm/learn.pulumi/commit/883dfc7)
> `sudo docker --version`  
> #> Docker version 24.0.7, build 24.0.7-0ubuntu4.1

###### [Install and Set Up kubectl on Linux | Kubernetes](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/#install-using-native-package-management)

> `curl -fsSL https://pkgs.k8s.io/core:/stable:/v1.31/deb/Release.key | sudo gpg --dearmor -o /etc/apt/keyrings/kubernetes-apt-keyring.gpg`  
> #. allow unprivileged APT programs to read this keyring  
> `sudo chmod 644 /etc/apt/keyrings/kubernetes-apt-keyring.gpg`  
> `echo 'deb [signed-by=/etc/apt/keyrings/kubernetes-apt-keyring.gpg] https://pkgs.k8s.io/core:/stable:/v1.31/deb/ /' | sudo tee /etc/apt/sources.list.d/kubernetes.list`  
> #. helps tools such as command-not-found to work correctly  
> `sudo chmod 644 /etc/apt/sources.list.d/kubernetes.list`   

xxx
