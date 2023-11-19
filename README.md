# Kubernetes__
Kubernetes is composed of several key components that work together to manage containerized applications.
Here are some pointers you must remember while working with Kubernetes.

💠Master Components:
▪ API Server: Exposes the Kubernetes API and serves as the entry point for managing the cluster.
▪ Controller Manager: Monitors the cluster's state and ensures that the desired state is maintained. It includes controllers for nodes, replication, endpoints, and more.
▪ Scheduler: Assigns workloads to nodes based on resource requirements and constraints.

💠Node Components:
▪ Kubelet: Agent running on each node that communicates with the API server and manages containers on the node.
▪ Container Runtime: Software responsible for running containers, such as Docker or containerd.
💠Kube Proxy: Maintains network rules to allow communication between pods and external traffic.
💠 Controller Plane:
Etcd: A distributed key-value store that stores the cluster's configuration data and state.
💠Pods:
▪ Basic Building Block: Smallest deployable units in Kubernetes, containing one or more containers sharing the same network namespace.

......#kubernetes #learningeveryday #devopsjourney #eks #ecs .....
~Diksha Shirke
