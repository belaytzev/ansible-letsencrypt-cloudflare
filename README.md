# Ansible playbook for make Let's Encrypt certificates
1. Install Ansible [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/index.html)
2. Clone repository from Github `https://github.com/belaytzev/ansible-letsencrypt-cloudflare.git`
3. Run playbook with domain and token `ansible-playbook playbook.yml -e 'lego_domain=example.com' -e 'cloudflare_token=<secret token>'`
