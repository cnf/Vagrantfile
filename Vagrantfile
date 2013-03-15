# -*- mode: ruby -*-
# # vi: set ft=ruby :
#
Vagrant.configure("2") do |config|
  config.vm.box = "precise64"
  # config.vm.box_url = "http://files.vagrantup.com/precise64.box"
  # config.vm.provider :virtualbox do |vb|
  #   vb.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
  #   vb.customize ["modifyvm", :id, "--memory", 512]
  # end
  # config.vm.network :private_network, ip: "192.168.50.4" # old :hostonly
  # config.vm.network :public_network # use to be :bridged
  # config.vm.hostname = "ptester"
  # config.vm.network :forwarded_port, guest: 80, host: 8080
  # config.vm.synced_folder "src/", "/srv/website"

  #  config.vm.provision :puppet do |puppet|
  #    puppet.manifests_path = "manifests"
  #    puppet.manifest_file = "base.pp"
  #    puppet.facter = { }
  # end

  # config.vm.provision :chef_solo do |chef|
  #   chef.cookbooks_path = [ "cookbooks", "~/.chef/cookbooks/" ]
  #   chef.roles_path = "../my-recipes/roles"
  #   chef.data_bags_path = "../my-recipes/data_bags"
  #   chef.add_recipe "mysql"
  #   chef.add_role "web"
  #   # You may also specify custom JSON attributes:
  #   chef.json = { :mysql_password => "foo" }
  # end

end
