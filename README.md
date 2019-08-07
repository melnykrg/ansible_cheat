# ansible_cheat

Short example of how we can generate variables (dafault/main.yml) using Jinja2 templates (template/template.j2)

Ansible task (task/main.yml) run template job that is generating variables. 

`macbook050:ucs-deployer-ansible rme$ ansible-playbook -i test workflow/equipment-fabric_interconnect_ports.yaml --extra-vars="chassis_count=8" -vvvvv`
