# eng221 
## exemples pour la presentation
### Kubernetes
 
#### Traefik, quelconteneur
<li> kubectl apply -f https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/kubernetes/backend.yaml
<li> kubectl apply -f https://raw.githubusercontent.com/containous/traefik/master/examples/k8s/traefik-rbac.yaml
<li> kubectl apply -f https://raw.githubusercontent.com/containous/traefik/master/examples/k8s/traefik-deployment.yaml
<li> kubectl apply -f https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/kubernetes/traefik/ingrules.yaml
<li> echo "<i> IP </i> ma.machine.kubernetes" | sudo tee -a /etc/hosts
  
## Swarm
### Traefik, quelconteneur
<li> wget https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/swarm/traefik/stack.yml 
<li> dicker stack deply --compose-file stack.yml stack1
