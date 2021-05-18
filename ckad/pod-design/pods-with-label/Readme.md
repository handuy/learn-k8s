Create 3 pods with names nginx1,nginx2,nginx3. All of them should have the label app=v1
kubectl run nginx1 --image=nginx -l app=v1

Edit pod label:
kubectl edit pods nginx

Get pods that has label app
kubectl get pods -l app

Get pods that has label app=v2
kubectl get pods -l app=v2
