Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/bionic64"
    config.vm.network "public_network"
    config.vm.provision "docker",
        images: ["ubuntu"]
end