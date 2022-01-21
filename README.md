# Application Deployment on CPU Manager for Kubernetes enabled Cluster

Four different workloads run on isolated cores of the host with the help of Intel CMK. These workloads are not interupted by any other kernel scheduled processes that increases efficiency.

export INSTALL_K3S_VERSION="v1.19.1+k3s1"
export K3S_NODE_NAME="alderlake"
export K3S_TOKEN="K107f84c1e6aff273eaf2833499d3d328211915f6be8bf09d0d0021cf868b67054b::server:ecea9781b7168827e49da540640c582e"
curl -sfL https://get.k3s.io | sh -s - agent --server https://10.62.226.108:6443
