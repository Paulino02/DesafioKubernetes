<h1>
Etapas realizas:

###
- Download do Kind, Kubectl

    - kIND

            curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.20.0/kind-linux-amd64

            chmod +x ./kind

            sudo mv ./kind /usr/local/bin/kind
    - KUBECTL

           curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
            sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
            kubectl version --client 
</h1>
<h2>
Considerações finais
</h2>

- É necesário estar com o docker engine instalado na máquina para rodar o Kind(Kubernetes in Docker).

- O Kind usa o Docker para criar e gerenciar os containers que simulam os nós do cluster Kubernetes. Portanto, antes de instalar e usar o Kind, certifique-se de ter o Docker Engine configurado e em funcionamento no seu sistema.


