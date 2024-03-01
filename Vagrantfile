Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.define "prometheus"
  config.vm.hostname = "prometheus"
  config.vm.network "private_network", ip: "192.168.56.60"
end
