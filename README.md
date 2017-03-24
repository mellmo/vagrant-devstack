# vagrant-devstack
Ubuntu box with a devstack shell provisioning script

# Requirements 
 - Vagrant env: 
 	either run `setup.bat` 
	or the following command `vagrant plugin install vagrant-env:`

# Environment variables:
create an .env file and fill it with the following environment variables:

 - VM_MEMORY=VALUE # min 4096
 - VM_CPU_COUNT=VALUE # min 2
 - ADMIN_PASSWORD=VALUE

# Install
After .env file setup, run `vagrant up` and be patient :) (it took ~5000s on a i5, 16go, ssd etc. the vm had minimum config required: 2cpus and 4go of ram)

In case you're running vagrant on windows with hyper-v, remember to run the command in a console with admin rights


Tested under windows 10 pro with hyperv
