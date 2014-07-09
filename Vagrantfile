# -*- mode: ruby -*-
# vi: set ft=ruby :

$script = <<SCRIPT

# Vagrant Install
sudo yum -y localinstall https://dl.bintray.com/mitchellh/vagrant/vagrant_1.6.3_x86_64.rpm

vagrant plugin install vagrant-vbguest

SCRIPT

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "CentOS_6.5_x86_64"

  config.vm.box_url = "https://github.com/2creatives/vagrant-centos/releases/download/v6.5.3/centos65-x86_64-20140116.box"

  config.vm.provision :shell, inline: $script

end
