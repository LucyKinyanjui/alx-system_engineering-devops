Requirements
Allowed editors: vi, vim, emacs.
All your files will be interpreted/compiled on Ubuntu 20.04 LTS.
All your files should end with a new line.
Your Puppet manifests must pass puppet-lint version 2.1.1 without any errors.
All your Bash script files must be executable.
The first line of all your Bash scripts should be exactly #!/usr/bin/env bash.
The second line of all your Bash scripts should be a comment explaining what is the script doing.
Project Description.
Learn what is a server. Where servers usually live. What is SSH. How to create an SSH RSA key pair. How to connect to a remote host using an SSH RSA key pair. The advantage of using #!/usr/bin/env bash instead of /bin/bash.

0. Use a private key - Write a Bash script that uses ssh to connect to your server using the private key ~/.ssh/school with the user ubuntu. - 0-use_a_private_key.

Requirements:

Only use ssh single-character flags.
You cannot use -l.
You do not need to handle the case of a private key protected by a passphrase.
sylvain@ubuntu$ ./0-use_a_private_key
ubuntu@server01:~$ exit
Connection to 8.8.8.8 closed.
sylvain@ubuntu$
