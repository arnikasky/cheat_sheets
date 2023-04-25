# Kubernetes Cheat Sheet

1. kubectl get services *# List all services in the namespace*

2. kubectl get pods --all-namespaces *# List all pods in all namespaces*

3. kubectl get pods -o wide *# List all pods in the current namespace, with details*

4.kubectl get deployment my-dep *# List a particular deployment*

5. kubectl get pods *# List all pods in the namespace*

6. kubectl get pod my-pod -o yaml *# Get a pod's YAML*

7. kubectl scale --replicas=3 deployment/foo *# Scale a deployment named 'foo' to 3*

8. kubectl rollout restart deployment/frontend *# Rolling restart of the "frontend" deployment*

9. kubectl rollout restart statefulset/frontend *# Rolling restart of the "frontend" statefulset*

10. kubectl logs my-pod *# Check logs of pods*

11. kubectl exec -i -t my-pod --container main-app -- /bin/bash *# Exec command*

