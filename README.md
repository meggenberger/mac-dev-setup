# MacOS Setup with Ansible

This repo contains an ansible playbook (and some scripts) that installs and configures most of the software I use on my Mac.
This has been heavily inspired by:

- https://github.com/geerlingguy/mac-dev-playbook
- https://github.com/TalkingQuickly/ansible-osx-setup

## Installation

There is a smple shell script in 'bin/bootstrap' that does the inital steps of:

1. Installing Xcode Command Line Tools
2. Installing Ansible
3. Fetching required Ansible roles and collections

It then runs the main playbook 'ansible_osx.yml'.
For future updates use 'bin/apply' to just run the Ansible playbook without the bootstrap commands.
