# Neuvector
# kubernetes

#commands for deployment

kubectl apply -f <filename>


#listing pods 

kubectl get pods 

#listing deployment

kubectl get deployment

#listing services

kubectl get services

#listing pods

kubectl get pods

#hosting in localhost

kubectl port-forward service/nginx 8080:80

#deleting

kubectl delete svc/pods/deployment  <name of svc/pods/deployment>

#other commands

kubectl describe deplyment <name of deploymemt>

