# springboot-k8s-yaml


## running on k8s locally

## build & tag the image -->  docker build -f Dockerfile . -t 8168245089/javatechie-k8s-springboot

## docker login 

## docker push  --> docker push 8168245089/javatechie-k8s-springboot  


##kubectl apply -f user-service-deployment.yml 
##kubectl get all 

##minikube tunnel --> in seperate window, as external IP cannot be issued to load balancer on minikube locally 

## go to http://127.0.0.1:8080/message 