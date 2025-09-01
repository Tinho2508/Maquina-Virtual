# Maquina-Virtual


# Desafio de Projeto: Criando uma Máquina Virtual no Azure

Repositório criado para o Desafio de Projeto da [Digital Innovation One](https.dio.me). O objetivo era criar uma máquina virtual (VM) do Windows no Microsoft Azure e documentar todo o processo.

## 📝 Descrição do Desafio

Este desafio consiste em aplicar os conhecimentos adquiridos no módulo de "Máquinas Virtuais" do bootcamp, consolidando o aprendizado sobre a criação e gerenciamento de VMs no ambiente Azure. O processo foi documentado para demonstrar a compreensão dos conceitos abordados.

## 🛠️ Ferramentas Utilizadas

-   **Microsoft Azure:** Plataforma de nuvem utilizada para a criação e gerenciamento dos recursos.
-   **Windows Server 2019 Datacenter:** Imagem do sistema operacional escolhida para a máquina virtual.
-   **Conexão de Área de Trabalho Remota (RDP):** Ferramenta utilizada para conectar e acessar a VM.

## 📄 Passo a Passo

### 1. Criação do Grupo de Recursos

O primeiro passo foi criar um **Grupo de Recursos** no Azure, que funciona como um contêiner lógico para agrupar os recursos da solução. As seguintes configurações foram utilizadas:

-   **Nome do Grupo:** `[Ex: GrupoRecursosVM]`
-   **Região:** `[Ex: East US]`

### 2. Criação da Máquina Virtual (VM)

Com o grupo de recursos criado, iniciei o processo de criação da Máquina Virtual. As configurações principais foram:

-   **Nome da VM:** `[Ex: MinhaVM-Windows]`
-   **Região:** `[Ex: East US]`
-   **Imagem:** `Windows Server 2019 Datacenter - Gen2`
-   **Tamanho (Size):** `[Ex: Standard_B1s (1 vcpu, 1 GiB memory)]`
-   **Nome de Usuário Administrador:** `[Ex: admin-user]`
-   **Regras de Portas de Entrada:** Foi liberada a porta **RDP (3389)** para permitir o acesso remoto.

### 3. Conexão com a Máquina Virtual

Após a implantação da VM ser concluída, o próximo passo foi conectar-se a ela. Para isso, utilizei o endereço de IP Público fornecido pelo Azure e a ferramenta de **Conexão de Área de Trabalho Remota (RDP)**. O acesso foi realizado com sucesso utilizando o usuário e a senha definidos durante a criação da VM.

## ✅ Verificação do Processo

A conexão foi estabelecida com sucesso utilizando o IP Público da VM e as credenciais de administrador. Após o login, a área de trabalho do Windows Server 2019 foi carregada, confirmando que a máquina virtual estava online, funcional e acessível remotamente.

## 💡 Conclusão

Este desafio foi fundamental para colocar em prática os conceitos teóricos sobre virtualização e computação em nuvem. O processo de criação e acesso a uma VM no Azure é intuitivo e poderoso, demonstrando a flexibilidade e a escalabilidade que a nuvem oferece para a provisionamento de infraestrutura de TI.

---
