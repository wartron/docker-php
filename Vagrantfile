# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubermuda/docker"
  config.vm.provision "shell", :inline => "apt-get update -y; apt-get install -y php5-cli"
end