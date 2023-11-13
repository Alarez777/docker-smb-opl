## Dockerized Samba Server for Open PlayStation Loader

OPL can stream backed up games from SMB. Although the process of creating a share
and enabling smb is straightforward for Windows, in MacOS or Linux it is not.

Hence, the reason for creating this repo. To set up an SMB server for streaming
games on your PS2 do the following.

On your PC

1. Execute 'docker build -t smb_opl:lastest .'
2. Use docker-compose.yml to start the server

On your PS2

1. As your share enter `PS2SMB` (this is important)
2. As a username enter `guest`
3. Leave password empty

Enjoy!
