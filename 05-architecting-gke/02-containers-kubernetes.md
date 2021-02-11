# Containers and Kubernetes

## Introduction to Containers

1. Which of these problems are containers intended to solve? Mark all that are correct (3 correct answers),

- [X] Packaging applications in virtual machines can be wasteful.
- [X] Applications need a way to isolate their dependencies from one another.
- [ ] Some developers need parts of their applications to be Linux-based while other parts are Windows-based.
- [X] It's difficult to troubleshoot applications when they work on a developer's laptop but fail in production.

## Containers and Container Images

1. Why do Linux containers use union file systems?

- [X] To efficiently encapsulate applications and their dependencies into a set of clean, minimal layers
- [ ] To control an application's maximum consumption of CPU time and memory
- [ ] To give a container its own virtual memory address space
- [ ] To control what an application's ability to see parts of the directory tree and IP addresses

2. What is significant about the topmost layer in a container? Choose all that are true (2 correct answers).

- [ ] Reading from or writing to the topmost layer requires special privileges.
- [X] The topmost layer's contents are lost when the container is no longer running.
- [ ] Reading from or writing to the topmost layer requires special software libraries.
- [X] An application running in a container can only modify the topmost layer.

## Introduction to Kubernetes

1. When you use Kubernetes, you describe the desired state you want, and Kubernetes's job is to make the deployed system conform to your desired state and to keep it there in spite of failures. What is the name for this management approach?
1 point

- [ ] Imperative configuration
- [ ] Virtualization
- [ ] Containerization
- [X] Declarative configuration

2. What is a stateful application?

- [X] An application that requires data to be stored persistently
- [ ] A web front end
- [ ] An application that is not containerized

## Introduction to Google Kubernetes Engine

1. What is the relationship between Kubernetes and Google Kubernetes Engine?

- [ ] Kubernetes and Google Kubernetes Engine are two names for the same thing.
- [ ] Google Kubernetes Engine is a closed-source variant of Kubernetes.
- [X] Google Kubernetes Engine is Kubernetes as a managed service.

2. What is the name for the computers in a Kubernetes cluster that can run your workloads?

- [ ] Container images
- [ ] Masters
- [ ] Containers
- [X] Nodes

3. Which of the following supports scaling a Kubernetes cluster as a whole?

- [X] Google Kubernetes Engine
- [ ] Compute Engine
- [ ] Kubernetes

## Containers and Kubernetes in Google Cloud

1. You are choosing a technology for deploying applications, and you want to  deliver them in lightweight, standalone, resource-efficient, portable packages. Which choice best meets those goals?

- [X] Containers
- [ ] Executable files
- [ ] Virtual Machines
- [ ] Hypervisors

2. You are classifying a number of your applications into workload types. Select the stateful applications in this list of applications. Choose all responses that are correct (2 correct responses).

- [X] A shopping application that saves user shopping cart data between sessions.
- [ ] Web server front end for your inventory system.
- [X] A gaming application that keeps track of user state persistently.
- [ ] Image recognition application that identifies product defects from images.

3. Google Compute Engine provides fine-grained control of costs.  Which Compute Engine features provide this level of control?

- [X] Per-second billing
- [ ] Autoscaling groups
- [ ] Managed instance groups
- [X] Fully customizable virtual machines
- [ ] Billing budgets and alerts

4. You are developing a new solution and want to explore serverless application solutions. Which Google Cloud compute services provide serverless compute resources that you can use with containers?

- [X] App Engine
- [ ] Cloud Functions
- [ ] Compute Engine
- [ ] Google Kubernetes Engine

5. You are deploying a containerized application, and you want maximum control over how containers are configured and deployed. You want to avoid the operational management overhead of managing a full container cluster environment yourself. Which Google Cloud compute solution should you choose?

- [ ] Compute Engine
- [ ] App Engine
- [X] Google Kubernetes Engine
- [ ] Cloud Functions
