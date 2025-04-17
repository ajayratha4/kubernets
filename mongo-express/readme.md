kubectl apply -f mongo-secret.yaml

kubectl apply -f mongo-deployment.yaml

kubectl apply -f mongo-config.yaml

kubectl apply -f mongo-express-deployment.yaml

<!-- kubectl delete deployment --all
kubectl delete service --all
kubectl delete secret --all
kubectl delete configmap --all -->
