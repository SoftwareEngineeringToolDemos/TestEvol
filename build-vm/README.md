Instructions

Open up terminal or command prompt.

Type in 'vagrant init rudolfochrist/ubuntu-desktop'. This will create a Vagrantfile.

Open up the Vagrantfile and type in 'config.vm.provision :shell, path: "bootstrap.sh"' after the line containing config.vm.box = "rudolfochrist/ubuntu-desktop"

Type in 'vagrant up --provider virtualbox' to start the machine.

Once the box is running you can start it from the Virtual box.

If you would like to check the java version type in 'java -version'.

Script sources:

[http://thediscoblog.com/blog/2013/11/18/provisioning-ubuntu-with-java-in-3-steps/](http://thediscoblog.com/blog/2013/11/18/provisioning-ubuntu-with-java-in-3-steps/)

[https://docs.vagrantup.com/v2/getting-started/provisioning.html](https://docs.vagrantup.com/v2/getting-started/provisioning.html)

[https://github.com/aglover/ubuntu-equip/raw/master/equip_java8.sh](https://github.com/aglover/ubuntu-equip/raw/master/equip_java8.sh)