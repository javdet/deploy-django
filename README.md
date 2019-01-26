Deploy django app
=========

example run
`ansible-playbook -i hosts -v playbook.yml`
 
Requirements
------------
*ansible 2.6.2


Role Variables
--------------
```buildoutcfg
repo_url - url application git repo
base_dir - base dir for install
project_name - project name application
app_port - port number for run application
```
