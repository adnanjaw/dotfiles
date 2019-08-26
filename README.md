# Dotfiles

Generic configuration files

## SSH config example

```sh
Host <name>
    HostName <ip>
    Port <port>
    User <user>

Host *
    PubKeyAuthentication=yes
    ForwardAgent=yes
    IdentityFile ~/.ssh/id_rsa
```
