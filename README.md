# ENAUTO Ansible Lab

Hands-on Ansible automation lab running from a Raspberry Pi control node.

## Lab Environment

- Debian Linux control node
- Ansible
- SSH key authentication
- Tailscale networking
- Multiple Raspberry Pi managed nodes
- Git version control

## Project Structure

```text
ansible/
├── inventory/
│   └── homelab.ini
├── playbooks/
│   └── check-node-exporter.yml
├── docs/
└── README.md

Lab 01
The first lab established the Ansible control environment and verified remote management of multiple Linux hosts.
Tasks completed:
- Installed Ansible
- Configured SSH key authentication
- Created an Ansible inventory
- Verified inventory membership
- Tested Ansible connectivity with the ping module
- Executed ad-hoc commands across multiple hosts
- Created and executed the first YAML playbook
- Collected service state from multiple managed nodes
