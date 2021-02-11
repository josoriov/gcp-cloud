# Kubernetes Architechture

## Kubernetes Concepts

1. What is the difference between a pod and a container?

- [X] A pod contains one or more containers.
- [ ] A container contains one or more pods.
- [ ] Pods and containers are two names for the name thing.

## The Kubernetes Control Plane

1. Which master control plane component is the only one with which clients interact directly?

- [X] kube-apiserver
- [ ] kube-controller-manager
- [ ] kube-scheduler
- [ ] etcd

2. Which master control plane component is the cluster's database?

- [ ] kube-apiserver
- [ ] kube-controller-manager
- [X] etcd
- [ ] kube-scheduler

3. What is the role of the kubelet?

- [X] To serve as Kubernetes’s agent on each node
- [ ] To maintain network connectivity among the Pods in a cluster
- [ ] To interact with underlying cloud providers

## Google Kubernetes Engine Concepts

1. In GKE clusters, how are nodes provisioned?

- [X] As Compute Engine virtual machines
- [ ] As abstract parts of the GKE service that are not exposed to GCP customers

2. In GKE, how are masters provisioned?

- [ ] As Compute Engine virtual machines
- [X] As abstract parts of the GKE service that are not exposed to GCP customers

3. What is the purpose of configuring a regional cluster in GKE?

- [X] To allow applications running in the cluster to withstand the loss of a zone
- [ ] To ensure that the cluster's workloads are isolated from the public Internet

## Kubernetes Object Management

1. In a manifest file for a Pod, in which field do you define a container image for the Pod?

- [ ] metadata
- [ ] apiVersion
- [X] spec
- [ ] kind

2. What are Kubernetes namespaces useful for? Choose all that are correct (2 correct answers).

- [X] Namespaces let you implement resource quotas across your cluster.
- [X] Namespaces allow you to use object names that would otherwise be duplicates of one another.
- [ ] Namespaces partition Linux kernel resources.
- [ ] Namespaces make resources more secure,

3. What is the purpose of the Deployment object?

- [X] To ensure that a defined set of Pods is running at any given time.
- [ ] To launch one or more Pods and ensure that a specified number of them succcessfully run to completion and exit.
- [ ] To launch one or more Pods on a time-based schedule.

## Kubernetes Controller Objects

1. What is the purpose of a Service? Choose all that are true (2 correct answers)

- [X] To provide a load-balancing network endpoint for Pods
- [X] To allow you to choose how Pods are exposed
- [ ] To allow you to put constraints on Pods' resource consumption
- [ ] To provide a way to inspect and diagnose code running in a Pod

2. If you are deploying applications in your Pods that need persistent storage, which controller type should you use?

- [X] StatefulSet
- [ ] Deployment
- [ ] DaemonSet
- [ ] ReplicaSet

## Kubernetes Architechture

1. You are designing an application, and you want to ensure that the containers are located as close to each other as possible, in order to minimize latency. Which design decision helps meet this requirement?

- [ ] Give the containers the same labels.
- [X] Place the containers in the same Pod.
- [ ] Place the containers in the same Namespace.
- [ ] Place the containers in the same cluster.

2. Which Kubernetes component does the kubectl command connect to in order to carry out operations on a cluster?

- [ ] kube-dns
- [X] kube-apiserver
- [ ] kube-scheduler
- [ ] kube-controller-manager

3. You have deployed a new Kubernetes Engine regional cluster with four machines in the default pool for the first zone and left the number of zones at the default. How many Compute Engine machines are deployed and billed against your account?

- [ ] Ten. (Four nodes are deployed in the first zone and three nodes are deployed in two other zones because you selected the defaults.)
- [X] Twelve. (Four nodes are deployed in each of three zones.  A master node is deployed in each zone but it is not billed against your account.)
- [ ] Fifteen. (Four nodes and a single master are deployed to each of the three zones.  A master node is deployed in each zone and it is billed against your account.)
- [ ] Sixteen. (Four nodes are deployed in primary and secondary zones in two regions, for a total of 4 zones and 16 nodes.  A master node is deployed in each zone but it is not billed to your account.)

4. You need to ensure that the production applications running on your Kubernetes cluster are not impacted by test and staging deployments.  Which features should you implement and configure to ensure that the resources for your production applications can be prioritized?

- [ ] Configure resource requests for Test, Staging and Production and configure specific Kubernetes resource quotas for the Production Namespace.
- [ ] Configure Namespaces for Test, Staging and Production and configure specific Kubernetes resource quotas for the Production Namespace.
- [ ] Configure labels for Test, Staging and Production and configure specific Kubernetes resource quotas for the Production Namespace.
- [X] Configure Namespaces for Test, Staging and Production and configure specific Kubernetes resource quotas for the test and staging Namespaces.

5. When configuring storage for stateful applications, what steps must you take to provide file system storage inside your containers for data from your applications that will not be lost or deleted if your Pods fail or are deleted for any reason?

- [X] You must create Volumes using network based storage to provide durable storage remote to the Pods and specify these in the Pods.
- [ ] You must mount NFS Volumes on each container in the Pod that requires durable storage.
- [ ] You must export the data from your applications to a remote service that preserves your data.
- [ ] You must create Volumes using local Storage on the Nodes and mount the Volumes inside your containers to provide durable storage.

6. You have a new logging and auditing utility that you need to deploy on all of the nodes within your cluster.  Which type of controller should you use to handle this task?

- [X] DaemonSet
- [ ] StatefulSet
- [ ] ReplicaSet
- [ ] Deployment.

7. You want to deploy multiple copies of your application, so that you can load balance traffic across them.  How should you deploy this application's Pods to the production Namespace in your cluster?

- [ ] Create a Service manifest for the LoadBalancer that specifies the number of replicas you want to run.
- [X] Create a Deployment manifest that specifies the number of replicas that you want to run.
- [ ] Create separate named Pod manifests for each instance of the application and deploy as many as you need.
- [ ] Deploy the Pod manifest multiple times until you have achieved the number of replicas required.
