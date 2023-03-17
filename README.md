## Test run example

```
git clone https://github.com/an0th3rdba/infra-ansible.git
chmod -R 755 infra-ansible && cd ~/infra-ansible
ansible-galaxy install -p roles/ -r roles/requirements.yml
ansible-playbook -i ~/inventory.ini -l test playbook_setup_storage.yml
```

## Feedback

an0th3rdba@gmail.com

## License

MIT
