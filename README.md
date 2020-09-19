# Mediawiki automation

Terraform : Setup two AWS EC2 redhat instances with Secuirty Group and AWS Elastic Load Balancer.

Ansible : Donwload Package, Enable Services, validate infrastrucuture readiness for the  application deployment

1) Run the following command from terraform folder at terminal

   terraform init   -Initialize the modules and setup configuration

   terraform plan   -Description on the action items and To-Do 

   terraform apply  -Perform the action items to provision the servers, instances, applications, security groups, vpc, cidr, ingress/outgress rules, route table, NACL etc


2) Run ansible playbook from ansible folder at terminal

   ansible-playbook -i hosts test.yaml 


# To Delete all resources on Cloud 
   terraform destroy: Delete all


