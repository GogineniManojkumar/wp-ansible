# wp-ansible
ansible-playbook for wordpress server setup
The playbook setup the wordpress based on centos os. 

Once you are clone with the repo. please follow below setups to execute the playbooks. 

Pre requests: 
1. anisble should be instannced on the machine where you are running the palybook. 


RUN Playbook:

ansible-playbook -i hosts wp-setup.yml --connection=local 
