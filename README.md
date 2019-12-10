# vSphere_Builder_for_Ansible
Build of "vSphere resource" / "Windows System" / "Linux System" for Ansible

# How to use
1. Make inventory (ex.site.yml this is example) in working dir.
1. Make Playbook(ex.playbook.yml Play-ALL.yml is example) in working dir.
1. Run this command
```
ansible-playbook -i {{ inventory-file_to_path }}.yml {{ playbook-file_to_path }}.yml

(example)
ansible-playbook -i site.yml playbook.yml  (if site.yml & playbook.yml is defined current directory.)
```
