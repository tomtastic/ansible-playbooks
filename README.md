# ansible-playbooks

```
$ xcode-select --install
$ sudo easy_install pip
$ sudo -H pip install ansible
$ mkdir -p ~/src && cd ~/src
$ git clone git@github.com:tomtastic/ansible-playbooks.git ansible
$ cd ansible
$ ansible-galaxy install --roles-path roles -r requirements.yml
$ ansible-playbook mbp.yml --list-tags
$ ansible-playbook mbp.yml --tags "macos" --list-tasks
$ ansible-playbook mbp.yml -K
  or just run specific tags...
$ ansible-playbook mbp.yml -K --tags "homebrew,mas"
```

NB: mas is currently broken due to some private framework changes with the App Store

