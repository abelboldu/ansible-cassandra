Vagrantfile
===========

Only use one box, either 'ubuntu' or 'centos', for testing. Since there is no
way right now to access `ansible_default_ipv4` address of one machine from
another, we will need to use only one box at a time for testing. So until a 
feasible solution is found, comment out either `ubuntu` or `centos` box in 
Vagrantfile and run `vagrant up` or just run either `vagrant up ubuntu` or 
`vagrant up centos` while not commenting out any box in Vagrantfile. 
