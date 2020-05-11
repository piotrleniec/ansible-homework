# Ansible Homework

## Setup

1. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. Install [Vagrant](https://www.vagrantup.com/docs/installation/)
3. Install [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## Acceptance Criteria

1. Each task should be completed using two commands: `vagrant up` and ansible playbook run.

## Task 1

1. Create two virtual machines
2. In the first, add a user and generate SSH key for him
3. Configure the second machine to accept SSH connection from the first machine for the create user

## Task 2

1. Create one virtual machine
2. Install nginx and customize a bit the static page using ansible templates
3. The webpage should be accessible through port 80

## Task 3

1. Create two virtual machines
2. In the first, install postgres instances and make sure that the database is accessible only from the second machine
3. In the second, install postgresl CLI and connect to the database
4. The database shouldn't be accessible from your laptop, only the second database

## Task 4

1. Create one virtual machine
2. Deploy wordpress or ghost server into it
3. The CMS should be accessible from port 80

## Task 5

1. Create two virtual machines
2. Deploy redis in the first one
3. Create SSH tunnel from one instance ot another
4. Try to connect to the redis from the second instances through the secure SSH tunnel

## Task 6

1. Create one virtual machine
2. Deploy collectd, graphite and grafana and integrate them
3. Install stress package
4. Use stress to increase cpu and memory usage and watch grafana for changes

## Task 7

1. Create two virtual machines
2. Make sure that the 1st one accepts ssh connections only through the second one
3. Prepare SSH config to connect to the 1st instance through the second one (jumphost)
