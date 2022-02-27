Vagrant.configure("2") do |config|
  config.vm.box = "./UbuntuServer.box"
  config.vm.boot_timeout = 30
  config.vm.provider :virtualbox do |vb|
    vb.name = "VagrantVM"
    vb.memory = 2048
    vb.cpus = 2
  end
end