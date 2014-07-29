The per-resiqite for deployment is:
0. Your OS is either Centos or RedHat
1. Ansible must have been installed (yum install ansible)
2. SElinux is disabled 
3. apache is installed (yum install httpd)
4. passwordless ssh is setup

Deployment steps:
Unzip the tgz file
edit included "hosts" file to fit your environment
execute "run_playbook"
