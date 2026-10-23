# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  # Box for CentOS Stream 9
  config.vm.box = "eurolinux-vagrant/centos-stream-9"

  # Hostname
  config.vm.hostname = "parneet"

  # Private network
  config.vm.network "private_network", ip: "192.168.56.53"

  # Public (bridged) network
  config.vm.network "public_network"

  # Provider settings
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
    vb.cpus = 2
  end

end
