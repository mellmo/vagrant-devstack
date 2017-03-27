# vagrant-devstack
Ubuntu box with a devstack shell provisioning script

The hypervisor target is hyperV, not tested under virtualbox but the script support it with an appropriate linux box.

# Requirements 
 - Vagrant env: 
 	either run `setup.bat` 
	or the following command `vagrant plugin install vagrant-env`

# Environment variables:
create an .env file (or edit in case you've run the setup.bat) and fill it with the following environment variables:

	`touch .env`

	`echo VM_MEMORY=VALUE >> .env`
	`echo VM_CPU_COUNT=VALUE >> .env`
	`echo ADMIN_PASSWORD=VALUE >> .env`

	`vim .env`

 - VM_MEMORY=VALUE # min 4096
 - VM_CPU_COUNT=VALUE # min 2
 - ADMIN_PASSWORD=VALUE

# Install
After .env file setup, run `vagrant up` and be patient :) (it took ~5000s on a i5, 16go, ssd etc. the vm had minimum config required: 2cpus and 4go of ram)

In case you're running vagrant on windows with hyper-v, remember to run the command in a console with admin rights

Tested under windows 10 pro with hyperv
