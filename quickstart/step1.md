# Step 1 - Create Kubernetes Cluster

NexClipper runs in a Kubernetes environment.

First, You have to provision multi node Kubernetes cluster environment configured using `launch.sh`{{execute}}

After a while, you can see the next message.
```
Waiting for Kubernetes to start...
Kubernetes started
```

You can get with `kubectl get nodes`{{execute}}.
```
kubectl get nodes
NAME           STATUS   ROLES    AGE   VERSION
controlplane   Ready    master   20m   v1.18.0
node01         Ready    <none>   19m   v1.18.0
```

When all nodes are in the Ready state, click the Continue button to move on to the next step.