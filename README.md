# Welcome to my Docker / Kubernetes Journey 2020
Putting together this github repo so that I can provide a central place of all things Docker & Kubernetes that I need to remember / dive further into.

[GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)

## Update History
2020-12-16 - Creating my GitHub Repo

## Content Links
[Important Technologies for Docker & Kubernetes](https://github.com/satsuk81/kube-journey#important-technologies-for-docker--kubernetes)

[Useful Resources](https://github.com/satsuk81/kube-journey#useful-resources)

[Code Examples](https://github.com/satsuk81/kube-journey#code-examples)

[Testing Area](https://github.com/satsuk81/kube-journey#testing-area)

## Important Technologies for Docker & Kubernetes
[Docker](https://www.docker.com/)

[Docker Desktop](https://www.docker.com/products/docker-desktop)

[Docker Hub](https://www.docker.com/products/docker-hub)

[Windows Terminal](https://www.microsoft.com/en-gb/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab)

[GitHub](https://github.com/)

[Kubernetes](https://kubernetes.io/)

[Azure Kubernetes Service (AKS)](https://azure.microsoft.com/en-gb/services/kubernetes-service/)

[Azure Container Instances (ACI)](https://azure.microsoft.com/en-gb/services/container-instances/)

[Azure Container Registry (ACR)](https://azure.microsoft.com/en-gb/services/container-registry/)

[Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/overview)

[Virtual Kubelet](https://github.com/virtual-kubelet/virtual-kubelet)

[Helm](https://helm.sh/)

## Useful Resources
### Kubernetes 101 by Jeff Geerling - https://kube101.jeffgeerling.com/

[Kube 101 - Episode 1](https://www.youtube.com/watch?v=IcslsH7OoYo)

[Kube 101 - Episode 2](https://www.youtube.com/watch?v=AHDrejEv0SM)

[Kube 101 - Episode 3](https://www.youtube.com/watch?v=nn9J9sWLj_w)

[Kube 101 - Episode 4](https://www.youtube.com/watch?v=mrxA8g3w6ic)

[Kube 101 - Episode 5](https://www.youtube.com/watch?v=euZdS5b2siA)

### Carlos A. Marquez GitHub - https://github.com/carlosalexei
[AKS Workshop](https://github.com/carlosalexei/aks-workshop)

Docker VM - [![Deploy Docker VM to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcarlosalexei%2Faks-workshop%2Fmain%2Fcontent%2Flabs%2Farm%2Fazuredeploy.json?token=ABTLB4JBZTT3VMZDJB3TCJK7ZGVU4)

## Code Examples
### GitHub
```
git clone https://github.com/carlosalexei/demoapps.git
```
### Docker Desktop
```
netstat -abn
```
```
net stop http
```
```
netcfg -d
```
```
wsl -l -v
```

### Docker CLI
```
docker pull nginx
```
```
docker run -d -p 8080:80 --name mynginx nginx
```
```
docker stop mynginx
```
```
docker run -it --rm -p 8080:8080 tomcat:8.0
```
```
docker ps -a
```
```
docker images
```
```
docker rm $(docker ps -a -q) -f
```
```
docker rmi $(docker images -a -q) -f
```
```
docker build -t helloworld:1.0 .
```
```
docker build -t myregistry1518.azurecr.io/helloworld:2.0 .
```
```
docker run -d -p 8080:80 helloworld:1.0
```
```
docker tag helloworld:1.0 <<your account>>/helloworld:1.0
```
```
docker push <<your account>>/helloworld:1.0
```
```
docker push myregistry1518.azurecr.io/helloworld:2.0
```

### Azure CLI
```
az account set --subscription <your-subs-id>
```
```
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
```
```
az login
```

### Kubernetes


## Testing Area
```
Test
```
![diagram](website/static/img/diagram.svg)
```bash
bash
```
* 1 star

** 2 star

*** 3 star
