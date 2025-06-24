# Todo
- [ ] switch to templateselctor for vm-template versions


- [ ] ToDo:
    - apps of apps becuase of dependencies testing
    - Anleitung wie man terminal von proxmox öffnet
    - full run    



Fix this - test running with ansiblecfg env - seems to work - let wait to secound and thrid run
```
proxmox-iso.ubuntu-2404: fatal: [default]: FAILED! => {"msg": "Timeout (12s) waiting for privilege escalation prompt: "}
    proxmox-iso.ubuntu-2404:
    proxmox-iso.ubuntu-2404: PLAY RECAP *********************************************************************
    proxmox-iso.ubuntu-2404: default                    : ok=84   changed=64   unreachable=0    failed=1    skipped=434  rescued=0    ignored=0
    proxmox-iso.ubuntu-2404:
==> proxmox-iso.ubuntu-2404: Provisioning step had errors: Running the cleanup provisioner, if present...
==> proxmox-iso.ubuntu-2404: Stopping VM
==> proxmox-iso.ubuntu-2404: Deleting VM
Build 'proxmox-iso.ubuntu-2404' errored after 24 minutes 19 seconds: Error executing Ansible: Non-zero exit status: exit status 2

==> Wait completed after 24 minutes 19 seconds
```
