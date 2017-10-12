# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "jhcook/macos-sierra"
  config.vm.synced_folder "~/dev/", "/Users/vagrant/dev/", owner: "vagrant", group: "staff", type: "rsync"
end
