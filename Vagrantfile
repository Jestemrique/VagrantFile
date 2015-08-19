Vagrant.configure("2") do |config|
  if Vagrant.has_plugin?("vagrant-proxyconf")
  ##
  #[user][:password@]IP:port
  ##
    config.proxy.http = "http://user:password@10.25.9.1:8080"
    config.proxy.https = "https://user:password@10.25.9.1:8080"
    config.proxy.no_proxy = "localhost,127.0.0.1"
  end
end
