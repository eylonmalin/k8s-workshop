# Kubernetes cheat sheet
## Pod
```bash
kubectl get po                        # list pods and their status
kubectl get po foo                    # Show one pod named foo
kubectl describe po foo               # Show details of pod named foo
kubectl apply -f resource-file.yaml   # Create/update resource from file
kubectl exec foo -- curl localhost:80 # Exec command - browse html file
kubectl delete po foo                 # Delete the pod
```

## Deployment
```bash
kubectl get deployment                    # List deployments
kubectl get deploy bar                    # Show one deployment
kubectl describe deployment bar           # Show details about deployment bar
kubectl scale deployment bar --replicas=4 # Scale deployment to 4 pods
```