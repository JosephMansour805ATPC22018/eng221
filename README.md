# eng221 
## exemples pour la presentation
### Kubernetes
 
#### Traefik, quelconteneur
<li> kubectl apply -f https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/kubernetes/backend.yaml
<li> kubectl apply -f https://raw.githubusercontent.com/containous/traefik/master/examples/k8s/traefik-rbac.yaml
<li> kubectl apply -f https://raw.githubusercontent.com/containous/traefik/master/examples/k8s/traefik-deployment.yaml
<li> kubectl apply -f https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/kubernetes/traefik/ingrules.yaml
<li> echo "<i> IP </i> ma.machine.kubernetes" | sudo tee -a /etc/hosts
<li> wget https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/kubernetes/traefik/kube_strlb.txt
<li> wget https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/kubernetes/traefik/kube_strsc.txt

  
## Swarm
### Traefik, quelconteneur
<li> wget https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/swarm/traefik/stack.yml 
<li> dicker stack deploy --compose-file stack.yml stack1
<li> wget https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/swarm/traefik/swarm_strlb.txt
<li> wget https://raw.githubusercontent.com/JosephMansour805ATPC22018/eng221/master/swarm/traefik/swarm_strsc.txt

awk '{for (i=1;i<=NF;i++) a[tolower($i)]++}END{for (i in a) print i" "a[i]}' o.txt| sort -nrk2
