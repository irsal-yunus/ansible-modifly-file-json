# ansible-modifly-file-json
ansible modify file json

- copy config file ansible to directory playbook :
  - cp * /etc/ansible .
- git clone repository project app tree dir :
  - app repository
  - playbook

- create file playbook.yml :
  - touch playbook.yml
- checking syntax ansible :
  - ansible-playbook -i hosts playbook.yml --syntax-check
- running playbook :
  - ansible-playbook -i hosts playbook.yml 
