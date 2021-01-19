# kubernetes
![Alt](/9a2020d4-0e5f-4b95-8f2a-7fe134cde4c0.png)
## Orchestration

## Concept
## Architech
## Components
### Node vs Pod
**1.Node**
  -> each Node is a worker, minion
  -> Contain Pods that is running
**2.Pod**
  -> Smallest unit of k8s
  -> Abstraction over container
  -> Pod manage container, usually 1 application per Pod
  -> Each Pod gets its own IP address (IP Internal)
  -> Pod can die easily
  -> New IP address on re-creation
### Service
  -> Basically a static ip address
  -> Permanent IP address that can be attached each Pod, so to say to each Pod
  -> Lifecycle of Pod and Service NOT connected
  -> Static IP can be hold event Pod is deleted
### Ingress
  -> Allow Config Loadbalancer HTTP for service running on kubernetes
### Volumes
### Secrect
### ConfigMap
### StatefulSet
### Deployment

