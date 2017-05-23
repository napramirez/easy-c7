# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  # Workaround for Vagrant 1.8.5 Issue #7610
  config.ssh.insert_key = false

  config.vm.hostname = "easy-c7"
  config.vm.box = "centos/7"
  config.vm.synced_folder ".", "/home/vagrant/sync", disabled: true
  config.vm.network "public_network", :mac => "6E626F78DD00"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "1024"
  end
  
end

