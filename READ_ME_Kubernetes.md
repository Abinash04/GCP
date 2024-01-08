Kubernetes is an open-source container orchestration platform designed to automate deploying, scaling, and managing containerized applications.

It provides a framework to run distributed systems resiliently.

Components of Kubernetes :

[ Pods ]
Basic scheduling unit that holds one or more containers.

[ Nodes ]
Machines (physical or virtual) in the cluster where pods are scheduled.

[ Cluster ]
Collection of nodes and associated resources.

[ Kubelet ]
An agent running on each node, responsible for managing the node and its containers.

[ Kubernetes Controller Manager ] Manages controllers to regulate the state of the system.

[ Kube Proxy ]
Maintains network rules to allow communication between pods and external traffic.

[ etcd ]
Consistent and highly-available key-value store used for all cluster data.

[ API Server ]
Serves the Kubernetes API and is the primary entry point for administrative tasks.

[ Scheduler ]
Assigns pods to nodes based on resource requirements and other constraints.

[ Controller ]
Maintains the desired state of the system, such as ensuring the correct number of replicas for a particular application.

[ Service ]
Provides a consistent way to access a set of pods.

[ Namespace ]
A way to divide cluster resources between multiple users.

[ Volumes ]
Kubernetes supports various types of storage volumes, providing data persistence for pods.

[ Secrets and ConfigMaps ]
Mechanisms to manage sensitive information and configuration data separately from application code.

[ Deployment ]
A higher-level resource that manages updates to applications by handling the deployment and scaling of pods.

[ StatefulSets ]
Manages stateful applications, ensuring stable network identities and persistent storage for pods.

[ DaemonSets ]
Ensures that specific pods run on all (or specific) nodes for cluster-wide tasks like logging or monitoring.

[ Jobs and CronJobs ]
Run short-lived or scheduled tasks within the cluster.

[ Ingress ]
Manages external access to services, typically HTTP.

[ Network Policies ]
Define how groups of pods can communicate with each other and other network endpoints.

[ Horizontal Pod Autoscaler ] Automatically adjusts the number of replica pods to handle varying load.

[ Vertical Pod Autoscaler ]
Adjusts the resources allocated to individual pods based on their usage.

[ Operators ]
A way to package, deploy, and manage applications using Kubernetes APIs and controllers.

[ Kubectl ]
The command-line interface to interact with Kubernetes clusters.