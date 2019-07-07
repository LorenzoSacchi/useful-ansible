# List of ansible and related options:

* check the value of a single var
put var in the role
ansible-playbook -i <inventory> test-vars.yml

* output a template
put the template in 
ansible-playbook -i <inventory> test-jinja.yml

* add service status
test ansible that logs the status of a systemd services

This is a WIP. Not completely tested yet
