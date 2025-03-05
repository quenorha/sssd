### Setting up sssd on a controller

(Replace IP address at the end by the IP address of the LDAP server)

```
curl -k -o /root/setup_sssd https://raw.githubusercontent.com/quenorha/sssd/refs/heads/main/client/setup_sssd && chmod +x /root/setup_sssd && /root/setup_sssd 192.168.68.83
```

### Setting up openldap test server on a device supporting Docker

```
curl -k -o /root/setup_server https://raw.githubusercontent.com/quenorha/sssd/refs/heads/main/server/setup_server && chmod +x /root/setup_server && /root/setup_server 
```
