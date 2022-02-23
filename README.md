# ansible_experiments

These are my notes on setting up and using ansible to configure a new Docker host.  I'm sure I missed things in this so please don't use this as a guide.  


Installing ansible:
```
sudo yum install ansible
```

Verify:
```
ansible --version
```

Running a playbook:
```
ansible-playbook <filename>.yml
```


References:
1) https://blog.risingstack.com/getting-started-with-ansible-infrastructure-automation/
