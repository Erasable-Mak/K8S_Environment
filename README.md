# K8S_Environment_Creation

►   install minikube and kubectl
►  create and start a minikube cluster

🔗 Links:
- Install Minikube (Mac, Linux and Windows): https://bit.ly/38bLcJy 
- Install Kubectl: https://bit.ly/32bSI2Z


Main Kubectl Commands - K8s CLI
►  Get status of different components
►  create a pod/deployment
►  layers of abstraction
►  change the pod/deployment
►  debugging pods
►  delete pod/deployment
►  CRUD by applying configuration file


K8s YAML Configuration File
►  3 parts of a Kubernetes config file (metadata, specification, status)
►  format of configuration file
►  blueprint for pods (template)
►  connecting services to deployments and pods (label & selector & port)
►  demo


Demo Project follow steps
►  Deploying MongoDB and Mongo Express
►  MongoDB Pod
►  Secret
►  MongoDB Internal Service
►  Deployment Service and Config Map
►  Mongo Express External Service


Organizing your components with K8s Namespaces
►  What is a Namespace?
►  4 Default Namespaces
►  Create a Namespace
►  Why to use Namespaces? 4 Use Cases
►  Characteristics of Namespaces
►  Create Components in Namespaces
►  Change Active Namespace


K8s Ingress explained
►  What is Ingress? External Service vs. Ingress
►  Example YAML Config Files for External Service and Ingress
►  Internal Service Configuration for Ingress
►  How to configure Ingress in your cluster?
►  What is Ingress Controller?
►  Environment on which your cluster is running (Cloud provider or bare metal)
►  Demo: Configure Ingress in Minikube
►  Ingress Default Backend
►  Routing Use Cases
►  Configuring TLS Certificate


Helm - Package Manager
►  Package Manager and Helm Charts
►  Templating Engine
►  Use Cases for Helm
►  Helm Chart Structure
►  Values injection into template files
►  Release Management / Tiller (Helm Version 2!)


Persisting Data in K8s with Volumes
►  The need for persistent storage & storage requirements
►  Persistent Volume (PV)
►  Local vs Remote Volume Types
►  Who creates the PV and when?
►  Persistent Volume Claim (PVC)
►  Levels of volume abstractions
►  ConfigMap and Secret as volume types
►  Storage Class (SC)


Deploying Stateful Apps with StatefulSet
►  What is StatefulSet? Difference of stateless and stateful applications
►  Deployment of stateful and stateless apps
►  Deployment vs StatefulSet
►  Pod Identity
►  Scaling database applications: Master and Worker Pods
►  Pod state, Pod Identifier
►  2 Pod endpoints

K8s Services
►   What is a Service in K8s and when we need it?
►  ClusterIP Services
►  Service Communication
►  Multi-Port Services
►  Headless Services
►  NodePort Services
►  LoadBalancer Services
