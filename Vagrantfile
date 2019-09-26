Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |v|
    v.name = "ansible_playbook"
    v.memory = 2048
    v.cpus = 1
    #v.gui = true
  end
  config.vm.box = "centos/7"
  config.vm.network "private_network", ip: "172.16.10.4"
end