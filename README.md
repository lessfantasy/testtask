# testtask
Run maim.yml with extra-vars target for apply playbook on specified server. For example:
> ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook -u root -i '159.69.30.244,' main.yml --extra-vars "target=159.69.30.244"
