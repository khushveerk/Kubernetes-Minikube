# Kubernetes (K8S)
- It is an open source container orchestration platform that automates many of the manual processes involved in deploying, managing, and scaling containerized applications.
-  It was originally developed by Google and is now maintained by the Cloud Native Computing Foundation.


# ![image](https://github.com/user-attachments/assets/2324a0f7-0072-42f3-a614-b5b984bfcabf)


**Key features of Kubernetes include**:
1. Container Management: Simplifies running and managing containers across clusters.
2. Scaling: Automatically adjusts the number of active containers based on demand.
3. Load Balancing: Distributes traffic to ensure no single container is overwhelmed.
4. Self-healing: Automatically restarts failed containers and replaces or reschedules them as needed.
5. Service Discovery: Allows containers to communicate with each other and external services seamlessly.
6. Configuration Management: Manages application configuration and secrets securely.

# Kubernetes cluster
- A working Kubernetes deployment is called a cluster, which is a group of hosts running Linux® containers. You can visualize a Kubernetes cluster as two parts: the control plane and the compute machines, or nodes.

- Each node is its own Linux environment, and could be either a physical or virtual machine. Each node runs pods, which are made up of containers.

# Kubernetes vs Docker
- Docker can be used as a container runtime that Kubernetes orchestrates. When Kubernetes schedules a pod to a node, the kubelet (the service that makes sure each container is running) on that node will instruct Docker to launch the specified containers.
- The difference when using Kubernetes with Docker is that an automated system asks Docker to do those things instead of the admin doing so manually on all nodes for all containers.

# ![image](https://github.com/user-attachments/assets/3e873b57-b536-44d0-8406-1f00faf3bbc1)

# Minikube
![image](https://github.com/user-attachments/assets/d13159ed-cc18-4267-b491-4323cb9ec9c6)

- Minikube is a one-node Kubernetes cluster where master processes and work processes both run on one node.
- Minikube is local Kubernetes, focusing on making it easy to learn and develop for Kubernetes.
