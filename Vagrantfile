# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

  config.vm.define "acs" do |acs|
    acs.vm.box = "ubuntu/trusty64"
    acs.vm.hostname = "acs"
    acs.vm.network "private_network", ip: "192.168.33.10"
    acs.vm.provider "virtualbox" do |v|
      v.name = "Ansible"
      v.memory = 1024
  end
end

  config.vm.define "sh01" do |sh01|
    sh01.vm.box = "nrel/CentOS-6.5-x86_64"
    sh01.vm.hostname = "sh01"
    sh01.vm.network "private_network", ip: "192.168.33.20"
    sh01.vm.network "forwarded_port", guest: 80, host: 8080
    sh01.vm.provider "virtualbox" do |v|
      v.name = "Splunk_SH01"
      v.memory = 1024
  end
end

  config.vm.define "sh02" do |sh02|
    sh02.vm.box = "nrel/CentOS-6.5-x86_64"
    sh02.vm.hostname = "sh02"
    sh02.vm.network "private_network", ip: "192.168.33.30"
    sh02.vm.provider "virtualbox" do |v|
      v.name = "Splunk_SH02"
      v.memory = 1024
  end
end

  config.vm.define "sh03" do |sh03|
    sh03.vm.box = "nrel/CentOS-6.5-x86_64"
    sh03.vm.hostname = "sh03"
    sh03.vm.network "private_network", ip: "192.168.33.40"
    sh03.vm.provider "virtualbox" do |v|
      v.name = "Splunk_SH03"
      v.memory = 1024
  end
end

  config.vm.define "ind01" do |ind01|
    ind01.vm.box = "nrel/CentOS-6.5-x86_64"
    ind01.vm.hostname = "ind01"
    ind01.vm.network "private_network", ip: "192.168.33.50"
    ind01.vm.provider "virtualbox" do |v|
      v.name = "Splunk_IND01"
      v.memory = 1024
  end
end

    config.vm.define "ind02" do |ind02|
    ind02.vm.box = "nrel/CentOS-6.5-x86_64"
    ind02.vm.hostname = "ind02"
    ind02.vm.network "private_network", ip: "192.168.33.60"
    ind02.vm.provider "virtualbox" do |v|
      v.name = "Splunk_IND02"
      v.memory = 1024
  end
end

    config.vm.define "ind03" do |ind03|
    ind03.vm.box = "nrel/CentOS-6.5-x86_64"
    ind03.vm.hostname = "ind03"
    ind03.vm.network "private_network", ip: "192.168.33.70"
    ind03.vm.provider "virtualbox" do |v|
      v.name = "Splunk_IND03"
      v.memory = 1024
  end
end

    config.vm.define "hf01" do |hf01|
    hf01.vm.box = "nrel/CentOS-6.5-x86_64"
    hf01.vm.hostname = "hf01"
    hf01.vm.network "private_network", ip: "192.168.33.80"
    hf01.vm.provider "virtualbox" do |v|
      v.name = "Splunk_HF01"
      v.memory = 1024
  end
end

end