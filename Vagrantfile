Vagrant.configure("2") do |config|
    config.vm.define "nginx" do |nginx|
      nginx.vm.box = "ubuntu/focal64"
      nginx.vm.network "private_network", ip: "192.168.50.10"
      nginx.vm.network "public_network"
      nginx.vm.hostname = "nginx"
      nginx.vm.provision "shell", inline: <<-SHELL
        # Provisioning script for nginx server
        # You can add your provisioning commands here
      SHELL
    end
  
    config.vm.define "web-01" do |web01|
      web01.vm.box = "ubuntu/focal64"
      web01.vm.network "private_network", ip: "192.168.50.11"
      web01.vm.network "public_network"
      web01.vm.hostname = "web-01"
      web01.vm.provision "shell", inline: <<-SHELL
        # Provisioning script for web-01 server
        # You can add your provisioning commands here
      SHELL
    end
  
    config.vm.define "web-02" do |web02|
      web02.vm.box = "ubuntu/focal64"
      web02.vm.network "private_network", ip: "192.168.50.12"
      web02.vm.network "public_network"
      web02.vm.hostname = "web-02"
      web02.vm.provision "shell", inline: <<-SHELL
        # Provisioning script for web-02 server
        # You can add your provisioning commands here
      SHELL
    end
  
    config.vm.define "api-server-1" do |api1|
      api1.vm.box = "ubuntu/focal64"
      api1.vm.network "private_network", ip: "192.168.50.13"
      api1.vm.network "public_network"
      api1.vm.hostname = "api-server-1"
      api1.vm.provision "shell", inline: <<-SHELL
        # Provisioning script for api-server-1
        # You can add your provisioning commands here
      SHELL
    end
  
    config.vm.define "api-server-2" do |api2|
      api2.vm.box = "ubuntu/focal64"
      api2.vm.network "private_network", ip: "192.168.50.14"
      api2.vm.network "public_network"
      api2.vm.hostname = "api-server-2"
      api2.vm.provision "shell", inline: <<-SHELL
        # Provisioning script for api-server-2
        # You can add your provisioning commands here
      SHELL
    end
  
    config.vm.define "api-server-3" do |api3|
      api3.vm.box = "ubuntu/focal64"
      api3.vm.network "private_network", ip: "192.168.50.15"
      api3.vm.network "public_network"
      api3.vm.hostname = "api-server-3"
      api3.vm.provision "shell", inline: <<-SHELL
        # Provisioning script for api-server-3
        # You can add your provisioning commands here
      SHELL
    end
  end
