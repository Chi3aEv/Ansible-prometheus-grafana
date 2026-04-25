Hii 
Ansible -->> TO manage inside the SERVER --> AFter Logging to server
Terraform -->> For infrastructure Management --> BEfore logging to server

1.Ansible has one dependency it works only on linux 
   so downloaded ansible on Local ubuntu machine vmware

2. wrote some playbook directory.yml to check 

3. created a prometheus server on aws 

4. copied its keypair inside a ansible local machine and ssh prometheus srv through ansible

5. wrote some playbook grafana.yml , node_exporter+prometheus.yml and inventory.ini and also alert_manager.yml 

6. RUN them 

Promethues  <IP>:9090
Node exporter <IP>:9100
ALert Manager <IP>:9093
Grafana <IP>:3000


