# Resumo do Laboratório Microsoft Azure

Este lab do Microsoft Azure explorou conceitos fundamentais sobre computação em nuvem e a plataforma de serviços da Microsoft. Os principais tópicos abordados foram:

## Criação de Conta
- Como criar a conta de estudante

## Introdução ao Azure  
- Visão geral da plataforma  
- Principais serviços disponíveis: Computação, Redes, Armazenamento, IA, Segurança  

## Gerenciamento de Recursos  
- Como configurar e buscar serviços no portal do Azure

## Máquinas Virtuais (VMs)  
- Provisionamento e configuração de máquinas virtuais  

## Armazenamento no Azure  
- Tipos de armazenamento: **Blob Storage, File Storage, Disk Storage**
- Demonstração de Blob Storage

## Monitoramento e Segurança  
- Uso do **Azure Monitor** para acompanhar desempenho  
- Práticas de segurança e conformidade  

Em resume, esse laboratório proporcionou experiência teórica na criação e gerenciamento de recursos dentro do Azure, permitindo um entendimento mais sólido sobre computação em nuvem e suas aplicações.

------------------------------------------------

# 🚀 Lab 2: Criando e Configurando uma Máquina Virtual no Microsoft Azure  

## 📌 Introdução  
Guia passo a passo para a criação e configuração de máquinas virtuais na plataforma **Microsoft Azure**. Com uma abordagem prática, vamos explorar os principais conceitos, configurações e boas práticas para garantir um ambiente otimizado para seus projetos e estudos.  

## 💻 O que é uma Máquina Virtual (VM)?  
Uma **máquina virtual (VM)** é um ambiente computacional simulado que opera como um computador físico. No Azure, as VMs são amplamente utilizadas para hospedagem de aplicativos, desenvolvimento, teste e diversas outras finalidades, sendo totalmente configuráveis conforme a necessidade do usuário.  

## 🛠️ Configurando sua Máquina Virtual no Azure  

### **1️⃣ Acessando o Portal do Azure**  
Para iniciar, siga os passos abaixo:  
1. Acesse o [Portal do Azure](https://portal.azure.com) e faça login com sua conta Microsoft.  
2. No menu lateral esquerdo, clique em **"Máquinas Virtuais"**.  
3. Clique em **"Criar" > "Máquina Virtual do Azure"**.  

### **2️⃣ Escolhendo as Configurações da VM**  
Durante a criação da máquina virtual, você precisará definir alguns parâmetros essenciais:  
- **Nome da VM:** Escolha um nome descritivo e único.  
- **Região:** Selecione a localização do data center onde sua VM será hospedada.  
- **Imagem do Sistema Operacional:** Escolha entre Windows, Linux ou outras opções disponíveis.  
- **Tamanho da VM:** Define os recursos de CPU, memória e armazenamento.  
- **Autenticação:** Opte por senha ou chave SSH, dependendo do acesso necessário.  

### **3️⃣ Configuração de Rede e Segurança**  
- **Grupo de Segurança de Rede:** Defina regras para controlar o tráfego de entrada e saída.  
- **IP Público:** Permite acesso remoto à VM. Pode ser dinâmico ou estático.  
- **Portas de Comunicação:** Configure portas específicas, como **RDP (3389)** para Windows ou **SSH (22)** para Linux.  

## 🔗 Conectando-se à sua Máquina Virtual  

### **💻 Conectar via RDP (Windows)**  
1. No **Portal do Azure**, vá até sua VM e clique em **"Conectar"**.  
2. Escolha **"RDP"** e baixe o arquivo de conexão.  
3. Abra o arquivo e insira suas credenciais para acesso remoto.  

### **🐧 Conectar via SSH (Linux)**  
1. No **Terminal**, digite o comando:  
   ```bash
   ssh usuario@ip-publico-da-vm
   ```
2. Insira sua chave SSH ou senha para autenticação.

### **⚙️ Personalização e Manutenção da VM**
- Instalação de Software: Utilize o terminal ou o PowerShell para instalar ferramentas necessárias.
- Atualizações: Mantenha o sistema operacional e aplicativos sempre atualizados.
- Monitoramento: Utilize o Azure Monitor para verificar o desempenho e uso de recursos.

### **✅ Boas Práticas para Gestão de VMs no Azure**
- Utilize tags para organização eficiente de múltiplas VMs.
- Configure backup automático para evitar perda de dados.
- Defina regras de firewall para garantir maior segurança.
- Automatize tarefas com scripts PowerShell ou Bash.

### **🔎 Recursos Adicionais**
📌 [Criar uma máquina virtual do Windows no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
📌 [Documentação do GitHub](https://docs.github.com/pt)
📌 [GitHub Markdown Guide](https://www.markdownguide.org/)

----
