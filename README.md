#### set_hosts  

Inicializa los /etc/hosts del grupo que se le pase como variable "grupo"

ansible-playbook -e "grupo=k8" set_hosts.yml

Incluye el template hosts.j2

