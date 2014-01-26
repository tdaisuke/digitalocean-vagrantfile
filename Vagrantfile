Vagrant.require_plugin "vagrant-digitalocean"
Vagrant.configure("2") do |config|
  config.vm.box = 'digital_ocean'
  config.vm.box_url = "https://github.com/smdahlen/vagrant-digitalocean/raw/master/box/digital_ocean.box"

  config.ssh.private_key_path = '~/.ssh/id_rsa'

  config.vm.provider :digital_ocean do |provider|
    provider.client_id = 'YOUR_CLIENT_ID'
    provider.api_key   = 'YOUR_API_KEY'
    provider.ssh_key_name = 'SSH_KEY_NAME'

#select memory size
    provider.size      = '512MB'
    #provider.size      = '1GB'
    #provider.size      = '2GB'
    #provider.size      = '4GB'
    #provider.size      = '8GB'
    #provider.size      = '16GB'
    #provider.size      = '32GB'
    #provider.size      = '48GB'
    #provider.size      = '64GB'
    #provider.size      = '96GB'

#select region
    provider.region    = 'San Francisco 1'
    #provider.region    = 'New York 1'
    #provider.region    = 'New York 2'
    #provider.region    = 'Amsterdam 1'
    #provider.region    = 'Amsterdam 2'

#select image
  #ubuntu
    #provider.image     = 'Ubuntu 13.10 x64'
    #provider.image     = 'Ubuntu 13.10 x32'
    provider.image     = 'Ubuntu 13.04 x64'
    #provider.image     = 'Ubuntu 13.04 x32'
    #provider.image     = 'Ubuntu 12.10 x64 Desktop'
    #provider.image     = 'Ubuntu 12.10 x64'
    #provider.image     = 'Ubuntu 12.10 x32'
    #provider.image     = 'Ubuntu 12.04.3 x64'
    #provider.image     = 'Ubuntu 12.04.3 x32'
    #provider.image     = 'Ubuntu 10.04 x64'
    #provider.image     = 'Ubuntu 10.04 x32'
  #centos
    #provider.image     = 'CentOS 6.5 x64'
    #provider.image     = 'CentOS 6.5 x32'
    #provider.image     = 'CentOS 6.4 x64'
    #provider.image     = 'CentOS 6.4 x32'
    #provider.image     = 'CentOS 5.8 x64'
    #provider.image     = 'CentOS 5.8 x32'
  #Debian
    #provider.image     = 'Debian 7.0 x64'
    #provider.image     = 'Debian 7.0 x32'
    #provider.image     = 'Debian 6.0 x64'
    #provider.image     = 'Debian 6.0 x32'
  #Arch
    #provider.image     = 'Arch Linux 2013.05 x64'
    #provider.image     = 'Arch Linux 2013.05 x32'
  #Fedora
    #provider.image     = 'Fedora 19 x64'
    #provider.image     = 'Fedora 19 x32'
    #provider.image     = 'Fedora 17 x64 Desktop'
    #provider.image     = 'Fedora 17 x64'
    #provider.image     = 'Fedora 17 x32 Desktop'
    #provider.image     = 'Fedora 17 x32'

    provider.ca_path   = '/usr/local/opt/curl-ca-bundle/share/ca-bundle.crt'
  end
end
