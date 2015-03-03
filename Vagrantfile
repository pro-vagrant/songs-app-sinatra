VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "http://boxes.gajdaw.pl/sinatra/sinatra-v0.2.0.box"
  config.vm.network :forwarded_port, guest: 4567, host: 45670, host_ip: "127.0.0.1"
end
