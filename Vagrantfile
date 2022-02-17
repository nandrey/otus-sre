# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-18.04"

  config.vm.provider "virtualbox" do |vb|
    vb.name = "vagrant_work_place"
    vb.memory = "1024"
    vb.cpus = 1
  end

  config.vm.hostname = "vwp"

  config.vm.synced_folder "./code", "/home/vagrant/code",
    owner: "vagrant", group: "vagrant"
  
  config.vm.network "forwarded_port", guest: 5000, host: 5000

  config.vm.provision "shell", path: "provision.sh"
end
