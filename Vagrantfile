Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |v|
     v.customize ["modifyvm", :id, "--memory", "2048"]
     v.customize ["modifyvm", :id, "--cpus", "2"]
  end
  config.vm.box = "centos/7"
  end
