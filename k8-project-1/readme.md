kubectl apply -f mongo-config.yaml
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml
kubectl apply -f webapp.yaml

kubectl get all

kubectl get configmap
kubectl get secret

kubectl describe pod webapp-deployment-76b9949f46-hlv97

kubectl logs podName

kubectl get svc

## Get the ip address
minkikube ip
or
kubectl get node -o wide

## delete everything

### kubectl delete deployment webapp-deployment
### kubectl delte deployment mongo-deployment


### kubectl delete configmap  mongo-config
configmap "mongo-config" deleted

### kubectl delete secret mongo-secret
secret "mongo-secret" deleted
