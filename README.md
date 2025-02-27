# Installation
```sh
sudo apt install ansible -y
sudo whoami
ansible-playbook bubble-bot-build/main.yml
```

You'll likely need to change the owner name to your user in the [github-repos.yml](./roles/install-tools/tasks/github-repos.yml) file and alter the aliases in [.zshrc](./roles/customize-terminal/files/.zshrc) to your liking. 
