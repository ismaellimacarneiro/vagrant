Vagrant.configure("2") do |config|
  # Escolha uma box (imagem base) para a VM
  config.vm.box = "ubuntu/bionic64" # Você pode escolher outra box se desejar

  # Configuração da CPU e memória
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048" # Memória em MB
    vb.cpus = 2 # Número de CPUs - Ismael
  end

  # Configuração da placa de rede em modo bridge
  config.vm.network "public_network"
end
