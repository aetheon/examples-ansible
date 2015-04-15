# Ansible examples

Contains the following examples of ansible using roles or simple playbooks. The examples (see inventory file ```hosts```) is 
configured to point to localhost.

## Playbook

```sh

# run role example using interactive ssh authentication
ansible-playbook example_playbook.yml -i hosts -k

```

## Roles

The folder ``role/example`` contains an example of an ansible role, which is used by 
the ```example_role.yml``` playbook.

```sh

# run role example using interactive ssh authentication
ansible-playbook example_role.yml -i hosts -k

```

## References

* [Ansible - docs](http://docs.ansible.com/)
* [DigitalOcean - roles](https://www.digitalocean.com/community/tutorials/how-to-use-ansible-roles-to-abstract-your-infrastructure-environment)

## Authors

**Oscar Brito**

+ [github/aetheon](https://github.com/aetheon)
+ [twitter/aetheon](http://twitter.com/aetheon)
