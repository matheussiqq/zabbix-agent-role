Vagrant.configure("2") do |config|
  config.vm.define "zabbix-server" do |vm1|
    vm1.vm.hostname = "zabbix-server"
    vm1.vm.box = "ubuntu/focal64"
    vm1.vm.network "public_network", ip: "192.168.0.150"
  end

  config.vm.define "agent1" do |vm2|
    vm2.vm.hostname = "agent1"
    vm2.vm.box = "ubuntu/focal64"
    vm2.vm.network "public_network", ip: "192.168.0.161"
  end

  config.vm.define "agent2" do |vm3|
    vm3.vm.hostname = "agent2"
    vm3.vm.box = "ubuntu/focal64"
    vm3.vm.network "public_network", ip: "192.168.0.162"
  end
  
  config.vm.define "agent3" do |vm4|
    vm4.vm.hostname = "agent3"
    vm4.vm.box = "ubuntu/focal64"
    vm4.vm.network "public_network", ip: "192.168.0.153"
  end
end