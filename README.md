# nginx-playbook-mac
Ansible Playbook to install nginx on MacOS and replace default homepage with a static html.

### To run
Clone the repo
```
git clone https://github.com/abhinav-shawarma/nginx-playbook-mac.git
```
Run playbook
```
ansible-playbook -i src/inventory.cfg src/nginx-install-pb.yml
```