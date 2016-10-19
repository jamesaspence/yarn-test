VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"

  # We want vagrant to use its default key.
  config.ssh.insert_key = false

  # Set our ip.
  # This can be updated to any ip address
  # preferred. This will allow us to access
  # the site via that ip address.
  config.vm.network "private_network", ip: "192.168.99.10"
  config.vm.provider "virtualbox" do |v|
      v.memory = 512
  end
end
