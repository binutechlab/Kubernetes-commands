General Cluster Info
kubectl cluster-info → Show cluster details
kubectl get nodes → List all nodes
kubectl describe node <node> → Detailed info about a node
kubectl top node → Show node resource usage
Working with Pods
kubectl get pods -A → List all pods
kubectl describe pod <pod> → Detailed pod info
kubectl logs <pod> → View pod logs
kubectl exec -it <pod> -- /bin/sh → Access pod shell
kubectl delete pod <pod> → Remove a pod
Deployments & ReplicaSets
kubectl get deployments → List deployments
kubectl describe deployment <deploy> → Deployment details
kubectl rollout status deployment <deploy> → Check rollout
kubectl rollout undo deployment <deploy> → Rollback
Services & Networking
kubectl get services → List services
kubectl describe service <svc> → Service details
kubectl port-forward <pod> 8080:80 → Port forwarding
kubectl get ingress → List ingress
ConfigMaps & Secrets
kubectl get configmaps → List ConfigMaps
kubectl describe configmap <name> → ConfigMap details
kubectl get secrets → List secrets
kubectl describe secret <name> → Secret details
DaemonSets, StatefulSets, Jobs
kubectl get daemonsets → List DaemonSets
kubectl get statefulsets → List StatefulSets
kubectl get jobs → List Jobs
kubectl get cronjobs → List CronJobs
Debugging & Troubleshooting
kubectl get events → Show cluster events
kubectl describe pod <pod> → Check issues in a pod
kubectl logs <pod> --previous → View previous logs
kubectl exec -it <pod> -- /bin/bash → Debug a pod
Working with YAML
kubectl apply -f file.yaml → Apply config
kubectl delete -f file.yaml → Delete resources
kubectl get -f file.yaml → View resources
Cleanup & Maintenance
kubectl delete pod --all → Delete all pods
kubectl delete all --all → Delete all resources
kubectl delete namespace <name> → Remove namespace
