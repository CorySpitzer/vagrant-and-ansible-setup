# vargant-and-ansible-setup
Instructions to set up Vagrant and Ansible

### On a digital Ocean Box running Ubuntu 14.04:
## Install Vagrant and VirtualBox:
* Warning: Do not install VirtualBox nor Vagrant with `apt-get` as the Ubuntu repositories might be out of date
 * Download virtualbox with `wget http://download.virtualbox.org/virtualbox/4.3.30/virtualbox-4.3_4.3.30-101610~Ubuntu~trusty_amd64.deb`
 * Install virtualbox with `sudo dpkg -i virtualbox-4.3_4.3.30-101610~Ubuntu~raring_amd64.deb` (We're on 'trusty', but the package is apparrently 'raring')
 * Download the vagrant .deb with `wget https://dl.bintray.com/mitchellh/vagrant/vagrant_1.7.4_x86_64.deb` 
 * Install vagrant with `sudo dpkg -i vagrant_1.7.4_x86_64.deb`

## Find different boxes to install:
 * Check out different boxes to install at http://www.vagrantbox.es/

 

