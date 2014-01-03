Vagrant.configure("2") do |config|

  config.vm.box      = 'precise64'
  config.vm.box_url  = 'http://files.vagrantup.com/precise64.box'

  config.vm.hostname = 'boxes-vm'
  
  config.vm.network :private_network, ip: "33.33.33.33"
  
  config.vm.provider :virtualbox do |vb|
    vb.customize ["modifyvm", :id, "--memory", 2048]
  end
end
