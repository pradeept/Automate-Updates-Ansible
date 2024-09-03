# Automate updates

__Description__: The ansible script written to automate the updation of security patches and important OS packages.

### Files:

- __cron_play_book.yaml__ : 
For creating a cron job in host machine. (This cron will run the playbook.yaml at specified intervals)

- __playbook.yaml__ : Contains tasks to enable auto-install security updates service (unattended-service) and upgrade a list of important packages.

- __vault_secret.sh__ : Fetches vault password from environment.

-  __inventory.ini__ : Contains host list. Encrypted using ansible-vault (for secure storage).



