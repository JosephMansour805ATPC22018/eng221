# eng221 
## exemples pour presentation
### Kubernetes
#### Nginx
<li> kubectl apply -f https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/kubernetes/backend.yaml
<li> kubectl apply -f  https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/namespace.yaml
<li>? kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/default-backend.yaml 
<li> kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/configmap.yaml 
<li> kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/tcp-services-configmap.yaml 
<li> kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/udp-services-configmap.yaml 
<li> kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/rbac.yaml 
<li> kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/with-rbac.yaml 
<li> kubectl apply -f https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/kubernetes/nginx/ingsvc.yaml
<li> kubectl apply -f https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/kubernetes/nginx/ingrrules.yaml
  
#### Traefik
<li> kubectl apply -f https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/kubernetes/backend.yaml
<li> kubectl apply -f https://raw.githubusercontent.com/containous/traefik/master/examples/k8s/traefik-rbac.yaml
<li> kubectl apply -f https://raw.githubusercontent.com/containous/traefik/master/examples/k8s/traefik-deployment.yaml
<li> kubectl apply -f https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/kubernetes/traefik/ingrules.yaml
<li> echo "ma.machine.kubernetes" | sudo tee -a /etc/hosts
  
### Swarm
swarm/traefik/deploy.yaml
