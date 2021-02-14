# Ansible_Playbook

This repo contains 5 different YML files with Ansible playbook automation code for different tasks

ansible-hostname.yml) - Changes the hostname of the instance

dns-update.yml) - Adds a predefined script to the instance so that it's public ip is updated in the hosted zone automatically evreytime it boots up

chrony.yml) - Installs and runs chrony services on the instance

fail2ban.yml) - Installs and runs a scan from fail2ban 

kubernetes-worker.yml) - Created security group, created instance, added nodes to kubernetes server, installed docker, kubernetes, chrony and ran all the commands to add the new instances to the existing kubernetes cluster.
