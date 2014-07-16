precise64-vagrant
=================
 precise64 + provision "docker"

## up
    vagrant plugin install vagrant-proxyconf

    mv env_proxy.sh.sample env_proxy.sh
    vi env_proxy.sh
    sh env_proxy.sh

    vagrant up

## precies64 
This is a simple 64-bit Ubuntu 12.04 LTS box that has Chef/Puppet pre-installed.
