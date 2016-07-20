# ansibleAdvertise
Ansible configuration files for automate PHP5, Memcached and Nginx Server
Currently operative version is Ubuntu 14.04 and Ubuntu 16.04

# Requeriments
- Ansible 2.x

# Packages Installed in Ubuntu 14.04
- Nginx
- Php5
- Php5-fpm
- Memcached
- Test files in Nginx Root (info.php and memcached.php)
- Added user for administration: advsupport

# Packages Installed in Ubuntu 16.04
- Nginx
- Php7
- Php7-fpm
- Memcached
- Test files in Nginx Root (info.php and memcached.php)
- Added user for administration: advsupport

# Installation procedure Ubuntu 14.04
ansible-playbook advbook-14.04.yml

# Installation procedure Ubuntu 16.04
ansible-playbook advbook-16.04.yml
