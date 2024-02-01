# MultiVM-Vagranfile

This is just a simple vagrantfile script for you to deploy multiple Ubuntu 20.04 Box in your Vagrant-vms.

## Installation

Use git clone.
```bash
git clone https://github.com/oepilcore/MultiVM-Vagrantfile.git
```
Copy the file to your vagrant-vms folder
*For example mine folder was installed on drive D
```bash
mv MultiVM-Vagrantfile /d/vagrant-vms/
```

## Usage

```bash
cd /vagrant-vms/MultiVM-Vagrantfile
vagrant up
```

## Note

Please take note of some lines:
Change these lines using your private IP
```bash
config.vm.network "private_network", ip: "xxx.xxx.xxx.xxx"
```
