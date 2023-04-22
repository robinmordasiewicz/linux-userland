
ansible-galaxy install gantsign.oh-my-zsh

ansible-pull -U https://github.com/robinmordasiewicz/linux-userland.git playbook.yml

cloud-init single --name cc_ansible

sudo cloud-init schema --system
