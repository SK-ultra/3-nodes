Running ansible-playbook -i inventory/aws.py > inventory creates an inventory with json formatted aws objects for the given creds
  
Kubeadm was used to setup K8s

AWS credentials need to be unencrypted in ansible vault, currently stored as encrypted in cred.yml

To Do: 
1. Figure out how to connect the load balancer to nginx applications that will be setup in k8s
2. Figure out cheaper ALB than Route53(because money)


  
