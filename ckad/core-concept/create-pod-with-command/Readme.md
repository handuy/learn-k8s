Create a busybox pod (using kubectl command) that runs the command "env". Run it and see the output

kubectl run busybox --image=busybox --restart=Never --command -- env
kubectl logs busybox
