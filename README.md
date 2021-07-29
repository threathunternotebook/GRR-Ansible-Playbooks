# GRR-Ansible-Playbooks
Ansible playbooks to deploy and configure a GRR Server. These playbooks are setup to deploy a custom ISO on ESXi. The purpose is to be able to deploy and configure a GRR server on ESXi that doesn't have Internet access (isolated environment). This can be used for small hunt missions (less than 100 clients) for short periods (less than 2 months).
The playbooks should be run in the following order.
- grr-server-deploy-playbook.yml
- grr-server-config-playbook.yml
- grr-server-openssl.yml
- grr-server-nginx-playbook.yml
