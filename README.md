# Configure

1. Install ansible temp with xbps
2. Install xbps ansible module
```
ansible-galaxy collection install community.general
```
3. Then run
```
ansible-playbook install.yml -K --extra-vars 'user=<your user>'
```
4. Remove Ansible xbps package

# Credits

To Jonathan Kirszling, ansible scripts copied shamesly from his repository [void-config](https://github.com/eoli3n/void-config). 
