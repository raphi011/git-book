# Kubernetes

## Useful Commands

Get all the configuration details about the node, including the allocated pod CIDR

```
kubectl describe node node-name
```

Get extra details about the nodes, including internal IP

```
kubectl get nodes -o wide
```

Get the control plane and add-ons endpoints

```
kubectl cluster-info
```

Create a Deployment resource

```
kubectl create deploy NAME --image=image [FLAGS] -- [COMMAND] [args]
```

Expose a Deployment through a Service resource&#x20;

```
kubectl expose deploy NAME --port=port [--target-port=port] [FLAGS]
```

## Glossary

**Service** - an abstraction layer over a collection of pods running an application

**Ingress** - a mechanism to manage the access from external users and workloads to the services within the cluster

**Configmap** - a resource to store non-confidential data in key-value pairs.

**Secret** - a resource to store confidential data in key-value pairs. These are base64 encoded.

**Namespace** - a logical separation between multiple applications and associated resources.
