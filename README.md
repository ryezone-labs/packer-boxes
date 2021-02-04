# packer-boxes

## Generating password hash

```bash
openssl passwd -6 -salt your_salt your_password
```

## Building Ubuntu 20.04

```bash
packer build -var-file=secrets.json -var-file=variables/ubuntu.20.04.json ubuntu-20.04-amd64-proxmox.json
```
