
  Vagrant.configure("2") do |config|
    config.vm.define "ag1" do |ag1|
    ag1.vm.box = "bento/centos-6.7" 
	ag1.vm.hostname = "agent1.mydev.local"
	ag1.vm.network "private_network", ip: "192.168.56.10"
   
end

config.vm.define "ag2" do |ag2|
    ag2.vm.box = "bento/centos-6.7" 
	ag2.vm.hostname = "agent1.mydev.local"
	ag2.vm.network "private_network", ip: "192.168.56.11"
	
 end
 end
