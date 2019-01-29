Deploy django app
=========
Playbook for deploy [app](https://github.com/kirpit/django-sample-app/) in docker. 
Test in Ubuntu 16.04/18.04

1. Clone this repo
2. `pip install -r requirements.txt`
3. Set host in hosts file
4. Run playbook `ansible-playbook -i hosts -v playbook.yml`
5. Connect to http://host
 
Requirements
------------
* ansible 2.6.4


Role Variables
--------------
```buildoutcfg
repo_url - url application git repo
base_dir - base dir for install
project_name - project name application
app_port - port number for run application
```
