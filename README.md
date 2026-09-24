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
