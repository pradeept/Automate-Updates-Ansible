# Automate updates

__Description__: The ansible script written to automate updation of security patches and important packages

### Files:

1. cron_play_book.yaml : for creating a cron job in host machine.

2. playbook.yaml : contains tasks to enable auto-install security updates service (unattended-service) and upgrade a list of important packages.

3. vault_secret.sh : fetches vault password from environment

4. inventory.ini : contains all hosts. Encrypted using ansible-vault.



