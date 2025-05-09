# 🌐 Serviços de Computação e Rede no Microsoft Azure

Este documento faz parte das atividades do curso introdutório de Microsoft Azure, onde exploramos os principais **serviços de computação e rede**, além de práticas relacionadas ao **dimensionamento e configuração de recursos em Máquinas Virtuais (VMs)**.

---

## ☁️ Serviços de Computação no Azure

O Azure oferece diversos serviços de computação para diferentes necessidades de escalabilidade, gerenciamento e flexibilidade:

### 🔹 Máquinas Virtuais (VMs)
Serviço IaaS que permite criar VMs com diferentes sistemas operacionais e configurações, ideais para controle total do ambiente.

### 🔹 Conjunto de Dimensionamento de VMs
Permite escalar automaticamente o número de VMs de acordo com a demanda de uso, garantindo performance e economia.

### 🔹 Conjunto de Disponibilidade de VMs
Garante alta disponibilidade distribuindo VMs em domínios de falha e atualização, minimizando indisponibilidades planejadas ou não planejadas.

### 🔹 Área de Trabalho Virtual
Oferece um ambiente de desktop remoto escalável e seguro, acessível de qualquer lugar com internet.

### 🔹 Serviços de Contêineres
Ideal para aplicações baseadas em microserviços, com suporte para diferentes formas de execução:

- **Instância de Contêiner**: Executa contêineres de forma rápida e isolada, sem precisar gerenciar infraestrutura.
- **Aplicativos de Contêiner**: Plataforma gerenciada para executar contêineres com escalabilidade automática.
- **Serviços de Kubernetes (AKS)**: Gerenciamento completo de clusters Kubernetes, para aplicações em larga escala.

### 🔹 Azure Functions
Permite executar pequenos trechos de código (funções) em resposta a eventos, com cobrança apenas pelo tempo de execução. Ideal para automações e integrações pontuais.

---

## 🌐 Serviços de Rede no Azure

### 🔹 Gateway de VPN
Conecta redes locais a redes do Azure por meio de conexões criptografadas via VPN, garantindo segurança na comunicação.

### 🔹 ExpressRoute
Proporciona conexões privadas e seguras entre a infraestrutura local e o Azure, com maior largura de banda e confiabilidade.

### 🔹 DNS do Azure
Gerencia e resolve nomes de domínio personalizados para serviços e recursos implantados no Azure.

---

## ⚙️ Configurando Recursos e Dimensionamento de VMs

Durante as práticas no portal do Azure, aprendemos a:

- Criar e configurar VMs com base em diferentes tamanhos e imagens de SO.
- Associar VMs a conjuntos de disponibilidade para garantir alta disponibilidade.
- Configurar conjuntos de dimensionamento para escalar automaticamente a infraestrutura.
- Integrar serviços de rede como IP público, NSG (Network Security Groups) e VPN gateways.
- Utilizar contêineres para aplicações leves e orquestrar microsserviços com AKS.
- Implementar Azure Functions para automatizar rotinas simples e eventos disparados por outros serviços.

---

## ✅ Conclusão

Esse aprendizado permite entender como projetar soluções eficientes, resilientes e seguras com base nos serviços de computação e rede do Azure. Ao dominar esses recursos, estamos aptos a estruturar arquiteturas modernas e escaláveis na nuvem.

---

🚀 *Projeto realizado como parte do curso introdutório de Microsoft Azure.*
