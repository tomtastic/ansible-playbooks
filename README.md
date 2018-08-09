# ansible-playbooks

```
$ xcode-select --install
$ sudo easy_install pip
$ sudo -H pip install ansible
$ mkdir -p ~/src && cd ~/src
$ git clone git@github.com:tomtastic/ansible-playbooks.git ansible
$ cd ansible
$ ansible-playbook mbp.yml --list-tasks
$ ansible-playbook mbp.yml -K
$ ansible-playbook mbp.yml -K --tags "homebrew,mas,macos"
```




