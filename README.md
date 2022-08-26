# AUT
<p align="center">
  <img src="https://github.com/skippybossx/automagic-ios-upgrade/raw/main/automagic-ios-upgrade.png">
</p>

# `automagic-ios-upgrade`

Ansible based automatic firmware updater for Cisco switches.

- Clone repo
- Copy firmwares to ~/automagic-ios-upgrade/playbooks/firmware/
- Copy hosts to /etc/ansible/hosts and edit to your parameters
- in fw_upgrade.yml edit fw version and filename

run using
`ansible-playbook ~/automagic-ios-upgrade/playbooks/switch_version.yml`
