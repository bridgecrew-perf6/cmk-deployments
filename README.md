# Application Deployment on CPU Manager for Kubernetes enabled Cluster

Four different workloads run on isolated cores of the host with the help of Intel CMK. These workloads are not interupted by any other kernel scheduled processes that increases efficiency.

export INSTALL_K3S_VERSION="v1.19.1+k3s1"
export K3S_NODE_NAME="alderlake"
export K3S_TOKEN="K10297760a3b513dcbb64445fe102858f96b329ea5820b3be1455692fbe8a4c54b7::server:a874036f5139ac5af77ec8fcdf8ed195"
curl -sfL https://get.k3s.io | sh -s - agent --server https://10.62.226.108:6443
