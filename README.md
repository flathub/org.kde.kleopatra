# Kleopatra Flatpak

Kleopatra is a certificate manager and a universal crypto GUI. It supports managing X.509 and OpenPGP certificates in the GpgSM keybox and retrieving certificates from LDAP servers.

## NOTICE

Kleopatra Flatpak may not work out of box. It needs an running gpg-agent from host to work, and here are some instruction for this.

In order to run gpg-agent in the background, you can run following command from your terminal:

```
gpg-agent --daemon
```

You can add this line in your `~/.bashrc` or `~/.profile`, so that gpg-agent can start on your login.

Or you can utilize systemd to start it. See this for more infomation: https://sources.debian.org/src/gnupg2/2.2.39-1/doc/examples/systemd-user/README/
