to check namepace resources:
 kubectl get pods -n default

Deploy pod in custom namespace:
kubectl run nginx --image=nginx -n develop

Configuring to custom namespace a default:
kubectl config set-context --current --namespace=

delete namespace:
kubectl delete namespace develop 
