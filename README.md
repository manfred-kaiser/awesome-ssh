<h1 align="center"> :computer: Awesome SSH :computer: </h1>
<p align="center">
  <p align="center">A curated list of SSH resources.</p>
</p>

# Servers
 
 ## Standard SSH servers
 
 -  [OpenSSH](https://github.com/openssh/openssh-portable) [![stars](https://img.shields.io/github/stars/openssh/openssh-portable.svg?style=social&label=stars)](https://github.com/openssh/openssh-portable) - OpenSSH is a complete implementation of the SSH protocol (version 2) for secure remote login, command execution and file transfer.
 -  [Dropbear](https://github.com/mkj/dropbear) [![stars](https://img.shields.io/github/stars/mkj/dropbear.svg?style=social&label=stars)](https://github.com/mkj/dropbear) - Dropbear is a software package written by Matt Johnston that provides a Secure Shell-compatible server and client.
- [ReverseSSH](https://github.com/Fahrj/reverse-ssh) [![stars](https://img.shields.io/github/stars/Fahrj/reverse-ssh.svg?style=social&label=stars)](https://github.com/Fahrj/reverse-ssh) - A statically-linked ssh server with a reverse connection feature for simple yet powerful remote access. Most useful during HackTheBox challenges, CTFs or similar.

## Bastion hosts

- [ContainerSSH](https://github.com/ContainerSSH/ContainerSSH) [![stars](https://img.shields.io/github/stars/ContainerSSH/ContainerSSH.svg?style=social&label=stars)](https://github.com/ContainerSSH/ContainerSSH) - Launch containers on demand 

## MitM servers

- [SSH-MITM](https://github.com/ssh-mitm/ssh-mitm) [![stars](https://img.shields.io/github/stars/ssh-mitm/ssh-mitm.svg?style=social&label=stars)](https://github.com/ssh-mitm/ssh-mitm) - SSH version 2 mitm-server - ssh mitm server for security audits supporting public key authentication, session hijacking and file manipulation
- [sshmitm](https://linux.die.net/man/8/sshmitm) - SSH version 1 mitm-server - sshmitm - SSH monkey-in-the-middle proxies and sniffs SSH traffic redirected by dnsspoof(8), capturing SSH password logins, and optionally hijacking interactive sessions. 

## Honeypots

- [Cowrie](https://github.com/cowrie/cowrie) [![stars](https://img.shields.io/github/stars/cowrie/cowrie.svg?style=social&label=stars)](https://github.com/cowrie/cowrie) - Launch containers on demand 
- [sshesame](https://github.com/jaksi/sshesame) [![stars](https://img.shields.io/github/stars/jaksi/sshesame.svg?style=social&label=stars)](https://github.com/jaksi/sshesame) - An easy to set up and use SSH honeypot, a fake SSH server that lets anyone in and logs their activity 



# Clients

- [OpenSSH](https://github.com/openssh/openssh-portable) [![stars](https://img.shields.io/github/stars/openssh/openssh-portable.svg?style=social&label=stars)](https://github.com/openssh/openssh-portable) - OpenSSH is a complete implementation of the SSH protocol (version 2) for secure remote login, command execution and file transfer.
- [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/) - PuTTY is a free and open-source terminal emulator, serial console and network file transfer application.
-  [Dropbear](https://github.com/mkj/dropbear) [![stars](https://img.shields.io/github/stars/mkj/dropbear.svg?style=social&label=stars)](https://github.com/mkj/dropbear) - Dropbear is a software package written by Matt Johnston that provides a Secure Shell-compatible server and client.

# Audit Tools

- [SSH-MITM](https://github.com/ssh-mitm/ssh-mitm) [![stars](https://img.shields.io/github/stars/ssh-mitm/ssh-mitm.svg?style=social&label=stars)](https://github.com/ssh-mitm/ssh-mitm) - ssh mitm server for security audits supporting public key authentication, session hijacking and file manipulation
- [ssh-audit](https://github.com/jtesta/ssh-audit) [![stars](https://img.shields.io/github/stars/jtesta/ssh-audit.svg?style=social&label=stars)](https://github.com/jtesta/ssh-audit) - SSH server & client auditing (banner, key exchange, encryption, mac, compression, compatibility, security, etc) 
- [whoami.filippo.io](https://github.com/FiloSottile/whoami.filippo.io) [![stars](https://img.shields.io/github/stars/FiloSottile/whoami.filippo.io.svg?style=social&label=stars)](https://github.com/FiloSottile/whoami.filippo.io) - A ssh server that knows who you are. $ ssh whoami.filippo.io

# Libraries

## Python

-  [Paramiko](https://github.com/paramiko/paramiko) [![stars](https://img.shields.io/github/stars/paramiko/paramiko.svg?style=social&label=stars)](https://github.com/paramiko/paramiko) - Paramiko is a pure-Python (2.7, 3.4+) implementation of the SSHv2 protocol, providing both client and server functionality.
-  [Fabric](https://github.com/fabric/fabric) [![stars](https://img.shields.io/github/stars/fabric/fabric.svg?style=social&label=stars)](https://github.com/fabric/fabric) - Fabric is a high level Python (2.7, 3.4+) library designed to execute shell commands remotely over SSH, yielding useful Python objects in return.
-  [AsyncSSH](https://github.com/ronf/asyncssh) [![stars](https://img.shields.io/github/stars/ronf/asyncssh.svg?style=social&label=stars)](https://github.com/ronf/asyncssh) - AsyncSSH is a Python package which provides an asynchronous client and server implementation of the SSHv2 protocol on top of the Python asyncio framework. 
