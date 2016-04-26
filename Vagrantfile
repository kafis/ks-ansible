# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  (1..4).each do |i|
      config.vm.define "node-0#{i}" do |node|
        node.vm.hostname = "ansible-0#{i}"
        node.vm.network "private_network", ip: "10.100.199.20#{i}"
        #node.vm.network "public_network", ip: "192.168.33.1#{i}", bridge: "en0: Wi-Fi (AirPort)"
      end
  end
end
