## Create POD

kubectl apply -f first-pod.yaml

### desccribe/get more info on pod

kubectl describe pod webapp

### folder structure inside pod

kubectl exec webapp ls

## Apply Service/pod

kubectl apply -f service/pod-name

### get all pods/service

kubectl get all

### shortcuts for

pod- po
service - svc

### delete service/pod

kubectl delete po/svc name-of-pod-svc
