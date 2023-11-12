# Virtualbox
To install the guest additions on a CentOS Stream

Add the following:  
sudo yum install perl gcc dkms kernel-devel kernel-headers make bzip2  

RHEL: 
sudo dnf install epel-release  

### Terminal commands
- vboxmanage list vms  
- vboxmanage list runningvms  
- vboxmanage startvm <name or UUID>  
- VBoxManage controlvm <vm> poweroff/reset  
Power off a vm  
VBoxManage controlvm "Ubuntu Server" poweroff --type headless  
