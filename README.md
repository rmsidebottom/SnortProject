# ansible

## Snort
Run `ansible-playbook -i hosts snort.yml --extra-vars "ansible_become_pas=pass"`

Prior to doing this, edit the sample interfaces file to reflect the interfaces on the box. Do the same thing with the snort.service.
