1. Init Server
Password: Tn{T-PJynEs[vG9~

Add non-root user ubuntu
useradd ubuntu
usermod -aG sudo ubuntu
vi /etc/ssh/sshd_config

`rsync --archive --chown=ubuntu:ubuntu ~/.ssh /home/ubuntu`

2. Setup Docker

