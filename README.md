# kubernetes

1. Install kubectl (The Kubernetes command-line tool, kubectl, allows you to run commands against Kubernetes clusters)
   curl.exe -LO "https://dl.k8s.io/release/v1.31.0/bin/windows/amd64/kubectl.exe"
2. To check kubectl installed or not
   kubectl version
3. Install minikube (Download .exe from https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download)
4. Check minikube status
   minikube status
6. minikube stop (To stop minikube)
7. minikube start (To start minikube)
8. kubectl get all (Get all components)
9. kubectl get pods (To get pods details)
10. kubectl get namespace (To get namespace details)
11. kubectl get deployment (To get deployment details)
12. kubectl get services (To get the services)
13. kubectl delete all --all (To delete all)
14. kubectl create deployment nginx --image=nginx (Crete deploymnet using nginx image)
15. kubectl get all -o wide (To get more information)
16. kubectl describe deployment nginx (To get complete details about deployment)
17. kubectl describe pod nginx-676b6c5bbc-l929k (To get complete details about pod)
