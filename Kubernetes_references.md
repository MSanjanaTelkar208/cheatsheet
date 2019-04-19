
## Kubernetes basic commands:

- gcloud container clusters get-credentials cluster-one --zone <zone_name> --project <project_name> --> connect to kubernetes cluster
- kubectl get namespaces --> List all namespaces
- kubectl create deployment nginx --image=nginx --> create nginx deployment
- kubectl get deployment --> displays details of all deployments
- kubectl get deployment <deployment_name> --> shows details of particular deployment
- kubectl get services --> List all services in the namespace
- kubectl get pods --all-namespaces --> List all pods in all namespaces
- kubectl get pods -o wide --> List all pods in the namespace, with more details -o output
- kubectl get pod my-pod -o yaml  --> Get a pod's YAML
- kubectl describe nodes <my-node>  --> Describe node with verbose output
- kubectl describe pods <my-pod>  --> Describe pod with verbose output
- 
