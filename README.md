**Kubernetes-Deployment**

**Kubernetes is a popular container orchestration tool**

**Features**:

→ Load balancing

→ Self-healing

→ High availability/ensure no downtime/maintain fault tolerance

→ Performance enhancement

→ Auto-scaling

![image](https://github.com/user-attachments/assets/3721071c-cf71-42bf-b17a-d12ed7e66c88)

**Kubernetes follows master-slave architecture. Kubernetes architecture has a master node and worker nodes**

**There are four components of a master node**:

→ Kube API server

→ controller

→ scheduler

→ etcd

**There are three components of worker node**:

→ kubelet

→ kube-proxy

→ container runtime


**Kubernetes Terminologies:**

 **Pod**: It represents one or more containers running in a cluster.

 **Service**: An abstract way to access pod/application.

 **Namespace**: It is used to remove name collision within a cluster. It supports multiple virtual clusters on      the same physical cluster.

 **Node**: Kubernetes worker machine.

 **Cluster**: Consisting of a group of nodes running containerized applications on Kubernetes.

 **ReplicaSet**: Several replicas of running pods. It helps in achieving high availability and scalability.

 **Label**: Giving a name to Kubernetes objects so that it can be identified across the system.

 **Kubelet**: It is an agent that runs on each node and checks if the containers are running in the pods.

 **Kubectl**: Command-line utility to interact with the Kubernetes API server.

 **Kube****-****proxy**: Network proxy which contains all the network rules on each node in the cluster.

