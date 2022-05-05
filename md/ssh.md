
## what is SSH and OpenSSH
SSH, Secure Shell or Secure Socket Shell, is a network protocal.
SSH, als refer to the suite of utilities that impletement SSH protocal.
OpenSSH is a connectivity tool for remote login that use SSH protocal. It encrypts all traffic between client and server to elinimate eaversdropping, connection hijacking, and other attacks.
## SSH server and SSH client
SSH is based on a client-server architecture. 
the system the user is working on is the client
the remote system being managed is the server

## OpenSSH commponents
- sshd.ext SSH server component that must be runnning on the remote machine
- ssh.exe SSH client component that runs on the user's local system
- ssh-kengen.ext generates, manages and converts authentication keys for SSH
- ssh-agent.exe stores private keys used for public key authentication
- ssh-add.exe add private keys to the list allowed by the server
- ssh-keyscan.exe aids in collecting the public SSH host keys from a number of hosts
- sftp.exe is the service that provides the Secure File Transfer Protocol, and runs over SSH
- scp.exe is a file copy utility that runs on SSH

## OpenSSH in Windows



## OpenSSH in WSL2
### how to generate SSH key pair
### where to store SSH key pair
### how to add SSH to 




## Password vs Passphase



## Linked documents/Guids

[Manage Windows with SSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_overview)