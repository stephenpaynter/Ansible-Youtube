# Ansible For Network Engineers

This repository contains the code used in the Youtube series "Ansible For Network Engineers'

## Youtube Playlist Link

https://www.youtube.com/watch?v=Ieff_GaRbVY&list=PLp19NUZLnl5NzGcUQZgTmu6Xbg1cgwf_B

## Installation

To install, simply clone this repository. 

## Part 1

### Commands used in the video.

sudo apt-get update  
sudo apt-get -y upgrade  
python3 -V  
cd /usr/bin  
sudo ln -sf ./python3 ./python  
sudo apt-get install -y python3-pip  
sudo pip3 install --upgrade pip  
sudo apt-get install build-essential libssl-dev libffi-dev python-dev -y  
sudo apt-get install selinux-utils  
sudo apt-get install -y policycoreutils  
sudo apt-get install selinux-basics  
sudo setenforce 0  


### Ansible Installation Commands  
  
sudo apt-get update  
sudo apt-get install software-properties-common  
sudo apt-get update  
sudo -H pip install ansible  

### Validation Commands  

ansible --version  
ansible -m ping localhost  

## Part 2

Build the /etc/hosts  
Build the /etc/ansible/ansible.cfg  
Build the /etc/ansible/hosts  

These files can be found in this repository  

## Part 3

The following playbook was used in this video.

```bash
gather_facts.yml
```

###  run the code use the following command

```yaml
ansible-playbook gather_facts.yml
```

## Part 4

ssh-keygen  
sudo apt install git  
git config —global user.email testusertest.com  
git config —global user.name Network-Bright  

The following playbook was used in this video.

```bash
backup.yml
```
###  run the code use the following command

```yaml
ansible-playbook backup.yml
```

## Getting Help

If you have questions you can look me up on Twitter @stephenpaynter.
Any bug reports, etc., please create an issue against this repository.
