Create a namespace called 'mynamespace' and a pod with image nginx called nginx on this namespace

1. Create namespace
kubectl create ns mynamespace

2. Create pod in ns
kubectl run nginx --image=nginx -n mynamespace
