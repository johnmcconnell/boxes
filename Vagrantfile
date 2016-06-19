# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.define "win-dev" do |dev|
    dev.vm.box = "opentable/win-2012r2-standard-amd64-nocm"

    dev.vm.guest = :windows

    dev.vm.provider "virtualbox" do |vb|
      vb.memory = 4 * 1024
    end
  end
end
