# Pi Kios
Ansible script to transform a stock raspbian install into a full kiosk.

Run with:
ansible-playbook -e @vars.yml pikiosk.yml

you need to add your own user in pikiosk.yml at the chrome section
inspired by:

https://github.com/azlux/log2ram/blob/master/ansible_playbook/install_log2ram.yml

https://pimylifeup.com/raspberry-pi-log2ram/

https://deepgram.com/learn/chromium-kiosk-pi
