# npvpn
IPsec VPN for Gerrit connection

Usage:
```
ssh-copy-id -p 22245 -i /home/kmonti/.ssh/id_rsa.pub kamil@public.novelpay.pl
ansible-galaxy install -r requirements.yml 
ansible-playbook vpn.yml -b -i vpn --ask-vault-pass -K

```
