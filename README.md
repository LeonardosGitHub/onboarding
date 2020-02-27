# Pave and Nuke Demo


## This was tested using i10800
 - Running version 13.1.1.5 EHF
 - Mgmt IP already defined
 - License already activated
 - v13.1.1.5EHF & v15.1.0.1 present on device

## Usage
 - host
   - /host/ansible-playbook playbook_host_DO_demo.yml
   - Provisions resources, initial build, vlans, 4 guests(2 running v13 & 2 running v15)
 - guests
   - /guests/ansible-playbook playbook_guests_DO_demo.yml
   - v13 guests
   - Provisions resources, initial build, networking, and AS3 example configuration
 - paveNuke
   - /paveNuke/ansible-playbook playbook_paveNukeGuests_DO_demo.yml
   - v15 guests
   - Provisions resources, initial build, networking, and AS3 example configuration

## Links to F5 Automation toolchain and F5 Ansible
 - Declarative Onboarding: https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/
 - Application Services 3: https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/
 - F5 Ansible: https://clouddocs.f5.com/products/orchestration/ansible/devel/
