# install-nautobot
Run with ```ansible-playbook install_nautobot.yml -i hosts```
Run this against an Ubuntu linux box

Install follows the nautobot install instructions that start at https://nautobot.readthedocs.io/en/stable/installation/  It then moves to each other page, each page change is noted in the comments of the roles/install_nautobot/tasks/main.yml playbook