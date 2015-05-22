Vagrant.configure(2) do |config|
  config.vm.box = "sinatra-v1.0.0"
  config.vm.box_url = "http://boxes.gajdaw.pl/sinatra/sinatra-v1.0.0.box"
  config.vm.network :forwarded_port, guest: 4567, host: 45670, host_ip: "127.0.0.1"
end
