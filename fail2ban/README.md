# Fail2Ban

## What is Fail2Ban?

Fail2Ban is a daemon that protects your SSH and other services from brute-force attacks by banning an IP address or host after a number of failed login attempts.

## Jail List

| Jail Name | Description | Config File
| --- | --- | --- |
| sshd | SSH server | [sshd.conf](sshd.conf) |
| ssh | SSH client | [ssh.conf](ssh.conf) |
| pam | PAM | [pam.conf](pam.conf) |
| mariadb | MariaDB | [mariadb.conf](mariadb.conf) |
