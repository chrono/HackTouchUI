# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant::Config.run do |config|
  config.vm.box = "precise32"
  config.vm.box_url   = 'http://files.vagrantup.com/precise32.box'
  config.vm.host_name = 'hacktouch'
  config.vm.forward_port 3000, 3000

  config.vm.provision :puppet, :manifests_path => 'puppet/manifests'
end
