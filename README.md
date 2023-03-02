
ansible-galaxy install gantsign.oh-my-zsh

ansible-pull -U https://github.com/robinmordasiewicz/linux-userland.git userland.yml

cloud-init single --name cc_ansible
