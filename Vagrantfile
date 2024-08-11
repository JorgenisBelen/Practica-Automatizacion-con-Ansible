Vagrant.configure("2") do |config|
  
  config.vm.define "vm1" do |vm1|
    vm1.vm.box = "ubuntu/bionic64"
    vm1.vm.hostname = "server1"
    vm1.vm.network "private_network", ip: "192.168.56.3"
    vm1.vm.provider "virtualbox" do |vb|
      vb.name = "server1"
      vb.memory = "256"
      vb.cpus = 1
    end
  end

  config.vm.define "vm2" do |vm2|
    vm2.vm.box = "ubuntu/bionic64"
    vm2.vm.hostname = "server2"
    vm2.vm.network "private_network", ip: "192.168.56.4"
    vm2.vm.provider "virtualbox" do |vb|
      vb.name = "server2"
      vb.memory = "256"
      vb.cpus = 1
    end
  end

  config.vm.define "vm3" do |vm3|
    vm3.vm.box = "ubuntu/bionic64"
    vm3.vm.hostname = "server3"
    vm3.vm.network "private_network", ip: "192.168.56.5"
    vm3.vm.provider "virtualbox" do |vb|
      vb.name = "server3"
      vb.memory = "256"
      vb.cpus = 1
    end
  end
end
