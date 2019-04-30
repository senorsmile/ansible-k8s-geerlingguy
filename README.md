# ansible-k8s-geerlingguy
Ansible site to deploy kubernetes to vagrant using geerlingguy's k8s role

# requirements
- vagrant
- default vm provider (virtualbox is good enough unless you have a reason to use something else)

# usage
check out this repo
`git clone https://github.com/senorsmile/ansible-k8s-geerlingguy.git`

make sure to update submodules
`git submodule update --init --recursive`

bring up vagrant nodes
`vagrant up`

run ansible against nodes
`./run_ansible.sh`
