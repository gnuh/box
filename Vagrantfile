Vagrant.configure("2") do |config|
    config.vm.box = "gnuh/box"
    config.vm.network "private_network", ip: "192.168.33.10"
    config.ssh.forward_agent = true
    config.vm.synced_folder ".", "/var/www/html", :mount_options => ["dmode=777", "fmode=666"]
end