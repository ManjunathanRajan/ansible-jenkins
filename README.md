# ansible-jenkins

## Startup

* `vagrant up`
* `ansible-playbook -i inventory/virtualbox.hosts playbooks/virtualbox.yml`

## Cleanup

* `vagrant halt; vagrant destroy -f`