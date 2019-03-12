# elasticsearch-instalattion
Installation ElasticSearch 6.4.2 Cluster

## Instructions

### 1 - Installation of Ansible
 yum install epel-release <br/>
 yum install ansible git <br/>

### 2 - Installation of ElasticSearch Galaxy
ansible-galaxy install elastic.elasticsearch <br/>

### 2 - Get Repository
 git clone https://github.com/jmalmeid/elasticsearch-installation.git <br/>

### 3 - Run Playbook install
 cd elasticsearch-installation <br/>
 ansible-playbook -i hosts playbook-install.yml <br/>
 ansible-playbook -i hosts playbook-init.yml <br/>
