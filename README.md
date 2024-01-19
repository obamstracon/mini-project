  DOCUMENTATION

RESOURCES CREATED IN THIS PROJECT

* EC2
* LOADBALANCER
* ROUTE53
* ANSIBLE PLAYBOOK
* SECURITY GROUP
* VARIABLE
* OUTPUT
* TERRAFORM MAIN


CONFIGURATION AND EXPLANATION OF EACH RESOURCE  CREATED


              Terraform 

Terraform allows you to describe your complete infrastructure in the form of code. Even if your servers come from different providers such as AWS or Azure, Terraform helps you build and manage these resources in parallel across providers

                 Main.tf


main.tf: This is our main configuration file where we are going to define our resource definition. variables.tf: This is the file where we are going to define our variables. outputs.tf: This file contains output definitions for our resources.21 Sept 2021
￼

                  Loadbalancer.tf 


detecting server problems and redirecting client traffic to available servers. You can use load balancing to make these tasks easier: Run application server maintenance or upgrades without application downtime.

               Sg.tf

Terraform currently provides both a standalone Security Group Rule resource (a single ingress or egress rule), and a Security Group resource with ingress and egress rules defined in-line. At this time you cannot use a Security Group with in-line rules in conjunction with any Security Group Rule resources.


               Ansible playbook

Ansible Playbooks are lists of tasks that automatically execute for your specified inventory or groups of hosts. One or more Ansible tasks can be combined to make a play—an ordered grouping of tasks mapped to specific hosts—and tasks are executed in the order in which they are written Before a play other can run as it should their are other component necessary, such as ansible.cfg , inventory and site.yaml
￼
