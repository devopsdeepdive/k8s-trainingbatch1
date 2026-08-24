apiVersion - Which version of the Kubernetes API you're using to create this object
kind - What kind of object you want to create
metadata - Data that helps uniquely identify the object, including a name string, UID, and optional namespace
spec - What state you desire for the object

API VERSION: https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.36/#mutatingadmissionpolicybinding-v1-admissionregistration-k8s-io
kubectl get pods
kubectl apply -f pod.yaml
