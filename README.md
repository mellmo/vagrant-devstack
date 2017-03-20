# vagrant-devstack

# Requirements 
 - Vagrant env : `vagrant plugin install vagrant-env:`

# Environment variables:
create an .env file and fill it with the following environment variables:

 - VM_MEMORY=VALUE # min 4096
 - VM_CPU_COUNT=VALUE # min 2
 - ADMIN_PASSWORD=VALUE

# Install
After .env file setup, run `vagrant up`

In case you're running vagrant on windows with hyper-v, remember to run the command in a console with admin rights
