#Arquivo Vagrantfile modificado para criação de maquina virtual CentOs 8, no VirtualBox
#Modificado por Markon Wytyney

Vagrant.configure("2") do |config|

    # Configurando a VM
      config.vm.define:CentOs do |centos_config|
        centos_config.vm.box ="centos/stream8"
        centos_config.vm.network "private_network" , ip: "192.168.56.0"
        centos_config.vm.provider:virtualbox do |virtualbox|
            virtualbox.memory = 2048
            virtualbox.cpus = 2
        end
    end
end    