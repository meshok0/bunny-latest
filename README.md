# latest bunny
Installs docker and "latest bunny" app  
Requires Ubuntu (tested on 18.04)  

## How to use:
1. Run ansible playbook:
```
ansible-playbook --connection=local --ask-sudo-pass --become playbook.yml -vv
```
2. Go to http://localhost:8088/bunny_latest.jpg  