# <a name="topo"></a>Preparação para o exame Azure AZ-900

Icons ☁️🔸

- [Parte 1: Princípios básicos do Microsoft Azure: descrever os principais conceitos do Azure](#parte1)
- [Parte 2: Descrever os principais serviços do Azure](#parte2)
- [Parte 3: Descrever as principais soluções e ferramentas de gerenciamento no Azure](#parte3)
- [Parte 4: Descrever os recursos gerais de segurança de rede e segurança](#parte4)
- [Parte 5: Descrever recursos de identidade, governança, privacidade e conformidade](#parte5)
- [Parte 6: descrever contratos de nível de serviço e Gerenciamento de Custos da Microsoft](#parte6)

# ☁️ <a name="parte1"></a>Princípios básicos do Microsoft Azure: descrever os principais conceitos do Azure

Depois de concluir este roteiro de aprendizagem, você poderá:

- Entenderá os benefícios da computação em nuvem e como ela pode poupar tempo e dinheiro
- Explicar conceitos de nuvem (alta disponibilidade, escalabilidade, elasticidade, agilidade e recuperação de desastre)
- Descrever os principais componentes da arquitetura (subscription, managment groups, resource e resource group)
- Resumir conceitos de distribuição geográfica (regiões do Azure, pares de regiões e zonas de disponibilidade)

1. [Introdução aos conceitos básicos do Azure](#Introdução_aos_conceitos_básicos_do_Azure)
2. [Discutir conceitos fundamentais do Azure](#Discutir_conceitos_fundamentais_do_Azure)
3. [Descrever os principais componentes da arquitetura do Azure](#Descrever_os_principais_componentes_da_arquitetura_do_Azure)


## 🔸 <a name="Introdução_aos_conceitos_básicos_do_Azure"></a>Introdução aos conceitos básicos do Azure

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

## 🔸 <a name="Discutir_conceitos_fundamentais_do_Azure"></a>Discutir conceitos fundamentais do Azure

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

## 🔸 <a name="Descrever_os_principais_componentes_da_arquitetura_do_Azure"></a>Descrever os principais componentes da arquitetura do Azure

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

1. [Descrever os principais conceitos do Azure](#parte1-1)
2. [Descrever os principais serviços do Azure](#parte1-2)
3. [Descrever as principais soluções e ferramentas de gerenciamento no Azure](#parte1-3)
4. [Descrever os recursos gerais de segurança de rede e segurança](#parte1-4)
5. [Descrever recursos de identidade, governança, privacidade e conformidade](#parte1-5)
6. [Parte 6: descrever contratos de nível de serviço e Gerenciamento de Custos da Microsoft](#parte1-6)

---
## 🔸<a name="parte1-1"></a> Princípios básicos do Microsoft Azure: descrever os principais conceitos do Azure 

[Link para o Microsoft Learn](https://docs.microsoft.com/pt-br/learn/paths/az-900-describe-cloud-concepts/)

Ao concluir este módulo, você poderá:

- Identificar os benefícios e as considerações do uso dos serviços de nuvem.
- Descrever as diferenças entre as categorias de serviços de nuvem.
- Descrever as diferenças entre os tipos de computação em nuvem.

### Modelos de nuvem

**<u>Nuvem pública</u>** - Os serviços são oferecidos pela Internet pública e ficam disponíveis para qualquer pessoa que deseje comprá-los. Os recursos de nuvem são de propriedade e operados por um provedor de serviços de nuvem de terceiros e entregues pela Internet.

- Nenhuma despesa de capital para escalar verticalmente.
- Os aplicativos podem ser provisionados e desprovisionados rapidamente.
- As organizações pagam apenas pelo que utilizam.

**<u>Nuvem privada</u>** - Uma nuvem privada consiste em recursos de computação usados exclusivamente por usuários de uma empresa ou organização. Uma nuvem privada pode estar localizada fisicamente no datacenter (local) da organização ou ser hospedada por um provedor de serviços de terceiros.

- O hardware deve ser comprado para inicialização e manutenção.
- As organizações têm controle total sobre os recursos e a segurança.
- As organizações são responsáveis pela manutenção e pelas atualizações de hardware.

**<u>Nuvem híbrida</u>** - Uma nuvem híbrida é um ambiente de computação que combina uma nuvem pública e uma nuvem privada, permitindo que dados e aplicativos sejam compartilhados entre elas.

- Fornece a maior flexibilidade.
- As organizações determinam onde executar seus aplicativos.
- As organizações controlam a segurança, a conformidade ou os requisitos legais.

### Vantagens da computação em nuvem

- **Alta disponibilidade**: dependendo do SLA (Contrato de Nível de Serviço) que você escolher, seus aplicativos baseados em nuvem poderão oferecer uma experiência de usuário contínua, sem tempo de inatividade aparente, mesmo quando as coisas derem errado.

- **Escalabilidade**: os aplicativos na nuvem podem ser dimensionados verticalmente e horizontalmente:
    - **Dimensione verticalmente** para aumentar a capacidade de computação adicionando RAM ou CPUs a uma máquina virtual.
    - **Dimensionar horizontalmente** aumenta a capacidade de computação adicionando instâncias de recursos.

- **Elasticidade**: você pode configurar aplicativos baseados em nuvem para aproveitar o dimensionamento automático, de modo que os aplicativos sempre tenham os recursos de que precisam.

- **Agilidade**: implante e configure rapidamente os recursos baseados em nuvem à medida que os requisitos de aplicativo mudarem.

- **Distribuição geográfica**: você pode implantar aplicativos e dados em data centers regionais em todo o mundo, garantindo assim que os clientes sempre tenham o melhor desempenho em sua região.

- **Recuperação de desastre**: ao aproveitar os serviços de backup baseados em nuvem, a replicação de dados e a distribuição geográfica, você pode implantar os aplicativos com a confiança de saber que seus dados estarão seguros em caso de desastre.

### Despesas de capital vs. despesas operacionais

- **CapEx (despesas de capital)** são os gastos antecipados de dinheiro com a infraestrutura física e a posterior dedução dessas despesas antecipadas ao longo do tempo. 
O custo inicial de CapEx tem um valor que é reduzido ao longo do tempo. Como um investimento de capital foi feito, os contadores categorizam essa transação como uma CapEx. Ao longo do tempo, para considerar a vida útil limitada dos ativos, eles são depreciados ou amortizados.

- **OpEx (despesas operacionais)** são gastos atuais com serviços ou produtos, que são cobrados no ato. Você pode deduzir essas despesas no mesmo ano em que gasta. Não há nenhum custo antecipado, pois você paga por um serviço ou produto conforme o usa. Os serviços de nuvem são categorizados como uma OpEx devido ao seu modelo de consumo. Não há ativos a serem amortizados e o provedor de serviços de nuvem (Azure) gerencia os custos associados à compra e à vida útil do equipamento físico. Dessa forma, a OpEx tem impacto direto sobre o lucro líquido, a renda tributável e as despesas associadas no balanço.

Para resumir, a CapEx requer custos financeiros iniciais significativos, bem como despesas contínuas com suporte e manutenção. Por outro lado, a OpEx é um modelo baseado em consumo, portanto, você é responsável apenas pelo custo dos recursos de computação que usa.

Banefícios do modelo baseado em consumo:

- Sem custos prévios.
- Não há necessidade de comprar e gerenciar infraestrutura que seus usuários podem não usar ao máximo.
- A capacidade de pagar para obter recursos adicionais quando necessário.
- A capacidade de parar de pagar por recursos que não são mais necessários.

### Modelos de serviço de nuvem

### <u>IaaS - Infraestructure as a Seervice</u>

Esse modelo de serviço de nuvem é o mais próximo do gerenciamento de servidores físicos; um provedor de nuvem manterá o hardware atualizado, mas a manutenção do sistema operacional e a configuração da rede ficam a cargo do locatário da nuvem. 

Por exemplo, as máquinas virtuais do Azure são dispositivos de computação virtual totalmente operacionais em execução nos data centers da Microsoft. Uma vantagem desse modelo de serviço de nuvem é a implantação rápida de novos dispositivos de computação. A configuração de uma nova máquina virtual é consideravelmente mais rápida do que o processo de adquirir, instalar e configurar um servidor físico.

A IaaS é a categoria mais flexível de serviços de nuvem. Ela tem como objetivo oferecer total controle sobre o hardware que executa seu aplicativo. Com a IaaS, você aluga o hardware em vez de comprá-lo.

Vantagens:
- Não há CapEx. Os usuários não têm custos antecipados.

- **Agilidade**. Os aplicativos podem ficar acessíveis rapidamente e desprovisionados sempre que necessário.

- **Gerenciamento**. O modelo de responsabilidade compartilhada se aplica; o usuário gerencia e mantém os serviços que provisionou e o provedor de nuvem gerencia e mantém a infraestrutura de nuvem.

- **Modelo baseado em consumo**. As organizações pagam apenas pelo que usam e operam em um modelo de OpEx (despesas operacionais).

- **Habilidades**. Não são necessárias habilidades técnicas refinadas para implantar, usar e obter os benefícios de uma nuvem pública. As organizações podem usar as habilidades e a competência do provedor de nuvem para garantir que as cargas de trabalho estejam seguras, protegidas e altamente disponíveis.

- **Benefícios de nuvem**. As organizações podem usar as habilidades e a competência do provedor de nuvem para garantir que as cargas de trabalho fiquem seguras, protegidas e altamente disponíveis.

- **Flexibilidade**. O IaaS é o serviço de nuvem mais flexível, pois você tem controle para configurar e gerenciar o hardware que executa seu aplicativo.

### <u>PaaS - Platform as a Service</u>

Esse modelo de serviço de nuvem é um ambiente de hospedagem gerenciado. O provedor de nuvem gerencia as máquinas virtuais e os recursos de rede e o locatário de nuvem implanta seus aplicativos no ambiente de hospedagem gerenciado. Por exemplo, os Serviços de Aplicativos do Azure fornecem um ambiente de hospedagem gerenciado em que os desenvolvedores podem carregar os aplicativos Web sem precisar se preocupar com os requisitos de software e hardware físico.

A PaaS oferece os mesmos benefícios e considerações que a IaaS, mas há alguns benefícios adicionais a ter em mente.

Vantagens:
- Não há CapEx. Os usuários não têm custos antecipados.

- **Agilidade**. A PaaS é mais ágil do que a IaaS, e os usuários não precisam configurar servidores para a execução de aplicativos.

- **Modelo baseado em consumo**. Os usuários pagam apenas pelo que usam e operam segundo um modelo OpEx.

- **Habilidades**. Não são necessárias habilidades técnicas refinadas para implantar, usar e obter os benefícios do PaaS.

- **Benefícios de nuvem**. Os usuários podem tirar proveito das habilidades e da competência do provedor de nuvem para garantir que as cargas de trabalho fiquem seguras, protegidas e altamente disponíveis. Além disso, os usuários podem ter acesso a mais ferramentas de desenvolvimento de ponta. Eles podem aplicar essas ferramentas em todo o ciclo de vida de um aplicativo.

- **Produtividade**. Os usuários podem se concentrar apenas no desenvolvimento de aplicativos, pois o provedor de nuvem cuida de todo o gerenciamento da plataforma. Trabalhar com equipes distribuídas como serviços é mais fácil porque a plataforma é acessada pela Internet. A plataforma pode ser disponibilizada globalmente com mais facilidade.

Desvantagem:
- **Limitações da plataforma**. Pode haver algumas limitações para uma plataforma de nuvem que podem afetar a execução de um aplicativo. Quando estiver avaliando qual plataforma de PaaS é mais adequada para uma carga de trabalho, considere as limitações nessa área.

### <u>SaaS - Software as a Service</u>

Nesse modelo de serviço de nuvem, o provedor de nuvem gerencia todos os aspectos do ambiente de aplicativo, como as máquinas virtuais, os recursos de rede, o armazenamento de dados e os aplicativos. O locatário de nuvem só precisa fornecer seus dados para o aplicativo gerenciado pelo provedor de nuvem. Por exemplo, Microsoft Office 365 fornece uma versão totalmente funcional do Microsoft Office que é executada na nuvem. Você só precisa criar seu conteúdo e o Office 365 cuida de todo o resto.

SaaS é um software que é hospedado e gerenciado de maneira centralizada para você e seus usuários ou clientes. Geralmente, uma versão do aplicativo é usada para todos os clientes e é licenciada por meio de uma assinatura mensal ou anual.

O SaaS oferece os mesmos benefícios que a IaaS, mas, novamente, há alguns benefícios adicionais a ter em mente.

Vantagens:
- Não há CapEx. Os usuários não têm custos antecipados.

- **Agilidade**. Os usuários podem fornecer acesso ao software mais recente à equipe de maneira rápida e fácil.

- **Modelo de preço pago conforme o uso** (*pay as you go*). Os usuários pagam pelo software que usam em um modelo de assinatura, normalmente mensal ou anual, independentemente de quanto eles usam o software.

- **Habilidades**. Não são necessárias habilidades técnicas refinadas para implantar, usar e obter os benefícios do SaaS.

- **Flexibilidade**. Os usuários podem acessar os mesmos dados de aplicativo de qualquer lugar.

Desvantagem:
- **Limitações de software**. Pode haver algumas limitações para um aplicativo de software que podem afetar o trabalho dos usuários. Por estar usando um software no estado em que se encontra, você não tem controle direto dos recursos. Quando estiver avaliando qual plataforma de SaaS é mais adequada para uma carga de trabalho, considere todas as necessidades de negócios e as limitações de software.

**Comparação de modelos de serviço de nuvem.**

| IaaS | PaaS | SaaS |
| ----------- | ----------- | ----------- |
| O serviço de nuvem mais flexível. | Focado no desenvolvimento de aplicativos. | Modelo de preço pago conforme o uso.|
| Você configura e gerencia o hardware para seu aplicativo. | O gerenciamento de plataforma é realizado pelo provedor de nuvem. | Os usuários pagam pelo software que utilizam em um modelo de assinatura.|


![iaas-paas-saas](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/fundamental-azure-concepts/media/iaas-paas-saas-575a09e9.png)

 Níveis de responsabilidade entre um provedor de nuvem e um locatário de nuvem.

![shared-responsibility](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/fundamental-azure-concepts/media/shared-responsibility-76efbc1e.png)

### Computação sem servidor

Assim como a PaaS, a computação sem servidor permite que os desenvolvedores criem aplicativos mais rapidamente, eliminando a necessidade de gerenciar a infraestrutura. Com aplicativos sem servidor, o provedor de serviços de nuvem provisiona, escala e gerencia automaticamente a infraestrutura necessária para executar o código. As arquiteturas sem servidor são altamente escalonáveis e orientadas a eventos, usando recursos apenas quando há uma função ou um gatilho específico.

É importante observar que os servidores ainda estão executando o código. O nome "sem servidor" é proveniente do fato de que as tarefas associadas ao provisionamento e ao gerenciamento de infraestrutura são invisíveis para o desenvolvedor. Essa abordagem permite que os desenvolvedores aumentem seu foco na lógica de negócios e ofereçam mais valor ao núcleo dos negócios. A computação sem servidor ajuda as equipes a aumentar a produtividade e colocar produtos no mercado mais rapidamente, além de permitir que as organizações otimizem melhor os recursos e fiquem concentradas na inovação.

## Resumo:

Você examinou vários dos benefícios que a computação em nuvem fornece, como alta disponibilidade, escalabilidade e distribuição geográfica. Você comparou as diferenças entre as despesas de capital e as despesas operacionais em um cenário de computação em nuvem. Por fim, você aprendeu sobre as diferentes categorias (IaaS, PaaS, SaaS) e tipos (público, privado e híbrido) da computação em nuvem.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

### 🔸 <a name="parte1-2"></a> Princípios básicos do Microsoft Azure: Descrever os principais serviços do Azure

Depois de concluir este roteiro de aprendizagem, você poderá:

- Entender a variedade de serviços disponíveis no Azure, incluindo computação, rede, armazenamento e banco de dados
- Identificar serviços de virtualização, como Máquinas Virtuais do Azure, Instâncias de Contêiner do Azure, Serviço de Kubernetes do Azure e Área de Trabalho Virtual do Azure
- Comparar os serviços de banco de dados do Azure, como o Azure Cosmos DB, o SQL do Azure, o Banco de Dados do Azure para MySQL, o Banco de Dados do Azure para PostgreSQL e os serviços de Big Data e análise do Azure
- Examinar recursos de rede do Azure, como Redes Virtuais, Gateways de VPN e o ExpressRoute do Azure
- Resumir os serviços de armazenamento do Azure, como Armazenamento de Blobs do Azure, Armazenamento em Disco do Azure e Armazenamento de Arquivos do Azure

### Conceitos básicos da Rede Virtual do Azure

As redes virtuais do Azure permitem que recursos do Azure, como VMs, aplicativos Web e bancos de dados, comuniquem-se uns com os outros, com usuários na Internet e com computadores cliente locais. Você pode pensar em uma rede do Azure como uma extensão de sua rede local com recursos que vinculam outros recursos do Azure.

As redes virtuais do Azure oferecem as seguintes funcionalidades de rede essenciais:

- Isolamento e segmentação
- Comunicação pela Internet
- Comunicação entre recursos do Azure
- Comunicação com os recursos locais
- Rotear tráfego de rede
- Filtrar tráfego de rede
- Conectar redes virtuais

### Isolamento e segmentação

A rede virtual do Azure permite criar várias redes virtuais isoladas. Quando você configura uma rede virtual, define um espaço de endereço IP privado usando intervalos de endereços IP públicos ou privados. O intervalo de IP público existe somente na rede virtual e não é roteável pela Internet. Você pode dividir esse espaço de endereços IP em sub-redes e alocar parte do espaço de endereço definido para cada sub-rede nomeada.

Para a resolução de nomes, é possível usar o serviço de resolução de nomes interno do Azure. Você também pode configurar a rede virtual para usar um servidor DNS interno ou externo.

### Comunicações com a Internet

Uma VM no Azure pode se conectar à Internet por padrão. É possível habilitar conexões de entrada da Internet atribuindo um IP à VM ou colocando a VM atrás de um balanceador de carga público. Para o gerenciamento de VM, você pode se conectar por meio da CLI do Azure, do protocolo RDP ou do Secure Shell.

### Comunicação entre recursos do Azure

Convém habilitar recursos do Azure para que se comuniquem entre si com segurança. 

- **Redes virtuais** As redes virtuais podem conectar não apenas VMs, mas outros recursos do Azure, como o Ambiente do Serviço de Aplicativo para Power Apps, o Serviço de Kubernetes do Azure e os conjuntos de dimensionamento de máquinas virtuais do Azure (VM Scale Set).

- **Service endpoints** Você pode usar pontos de extremidade de serviço para se conectar a outros tipos de recursos do Azure, como bancos de dados SQL do Azure e contas de armazenamento. Essa abordagem permite vincular vários recursos do Azure às redes virtuais para melhorar a segurança e fornecer o encaminhamento ideal entre recursos.

### Comunicação com os recursos locais

Você pode criar uma rede que abranja os ambientes locais e de nuvem

**Point-to-site virtual private networks** - A abordagem típica de uma conexão de VPN (rede virtual privada) é de um computador fora da sua organização, de volta à sua rede corporativa. Nesse caso, o computador cliente inicia uma conexão VPN criptografada para conectar o computador à rede virtual do Azure.

**Site-to-site virtual private networks** - Uma VPN site a site vincula seu dispositivo VPN ou gateway de VPN local ao Gateway de VPN do Azure em uma rede virtual. Na verdade, os dispositivos no Azure podem aparecer como estando na rede local. A conexão é criptografada e funciona pela Internet.

**Azure ExpressRoute** No caso de ambientes em que você precisa de maior largura de banda e níveis de segurança ainda mais altos, o  ExpressRoute fornece uma conectividade privada dedicada para o Azure que não passa pela Internet. 

### Rotear tráfego de rede

Por padrão, o Azure faz o roteamento de tráfego entre sub-redes em redes virtuais conectadas, em redes locais e na Internet. Você também pode controlar o roteamento e substituir essas configurações da seguinte maneira:

**Route tables** - Uma tabela de rotas permite definir regras sobre como o tráfego deve ser direcionado. Você pode criar tabelas de rotas personalizadas que controlam como os pacotes são encaminhados entre as sub-redes.
**Border Gateway Protocol** - O BGP funciona com Gateways de VPN do Azure, Azure Route Server ou ExpressRoute para propagar as rotas BGP locais para redes virtuais do Azure.

### Filtrar tráfego de rede

As redes virtuais do Azure permitem filtrar o tráfego entre sub-redes usando as seguintes abordagens:

**Network security groups** - é um recurso do Azure que pode conter várias regras de segurança de entrada e saída. Você pode definir essas regras para permitir ou bloquear tráfego com base em fatores como endereço IP de origem e de destino, porta e protocolo.

**Network virtual appliances** - é uma VM especializada que pode ser comparada a um dispositivo de rede protegida. Realiza uma função de rede específica, como execução de um firewall ou otimização de WAN (rede de longa distância).

### Conectar redes virtuais

Você pode vincular redes virtuais usando o emparelhamento dessas redes. O network peering permite que os recursos em cada rede virtual se comuniquem entre si. Essas redes virtuais podem estar em regiões separadas, o que permite criar uma rede global interconectada por meio do Azure.

**User-defined routes (UDR)** são uma atualização significativa nas Redes Virtuais do Azure que permitem maior controle sobre o fluxo de tráfego de rede. Esse método permite que os administradores de rede controlem as routing tables entre sub-redes dentro de uma VNet, bem como entre VNets.

![local-or-remote-gateway-in-peered-virual-network](https://docs.microsoft.com/en-us/learn/azure-fundamentals/azure-networking-fundamentals/media/local-or-remote-gateway-in-peered-virual-network-21106a38.png)

### Configurações de Rede Virtual do Azure

Você pode criar e configurar redes virtuais do Azure via portal do Azure, Azure PowerShell, CLI do Azure, Azure Cloud Shell ou um modelo do ARM.

### Criar uma rede virtual

Você vai configurar as seguintes opções para uma rede virtual básica:

- **Subscription** Só se aplica se você tem várias assinaturas para escolher.
- **Resource group** uma rede virtual precisa existir em um grupo de recursos. 
- **Nome da rede** O nome da rede deve ser exclusivo em sua assinatura, mas não precisa ser globalmente exclusivo.
- **Região** Selecione a região onde você deseja que a rede virtual resida.
- **Address space** define o espaço de endereço interno no formato CIDR (Classless Interdomain Routing). Esse espaço de endereço deve ser exclusivo dentro de sua assinatura e quaisquer redes às quais você deseje se conectar. 
    - Vamos supor que você escolha um espaço de endereço de 10.0.0.0/24 para sua primeira rede virtual. Os endereços definidos nesse espaço variam de 10.0.0.1 a 10.0.0.254. 
    - Em seguida, você criará uma segunda rede virtual e escolherá o espaço de endereço 10.0.0.0/8. Os endereços nesse espaço variam de 10.0.0.1 a 10.255.255.254. 
    - Alguns dos endereços se sobrepõem e não podem ser usados para as duas redes virtuais.
- **Subnet** Em cada intervalo de endereços de rede virtual, você pode criar uma ou mais sub-redes que particionam o espaço de endereço da rede virtual. O roteamento entre sub-redes dependerá das rotas padrão de tráfego. Você também pode definir rotas personalizadas. Como alternativa, você pode definir uma sub-rede que abrange todos os intervalos de endereços das redes virtuais.
- **Service endpoints** Selecione na lista quais você deseja habilitar. As opções incluem o Azure Cosmos DB, o Azure Service Bus, o Azure Key Vault e outros.
- **NAT gateway** (Network Address Translation) totalmente gerenciado e altamente resiliente. Você pode configurar uma sub-rede para usar um endereço IP de saída estático ao acessar a Internet. 
- **BastionHost**  O serviço do Azure Bastion fornece conectividade de RDP/SSH contínua e segura às suas máquinas virtuais, diretamente no portal do Azure, via SSL. 
- **DDoS Protection Standard** é um serviço Premium
- **Firewall** é um serviço de segurança cloud-based gerenciado que protege seus recursos de Rede Virtual do Azure. 

### Definir configurações adicionais

Depois de criar uma rede virtual, você poderá definir outras configurações. 

- **Network security group** possui regras de segurança que permitem filtrar o tipo de tráfego de rede que pode entrar e sair das sub-redes da rede virtual e interfaces de rede. Crie o grupo de segurança de rede separadamente. Depois associe-a a cada sub-rede na rede virtual.
- **Route table** O Azure cria automaticamente uma tabela de rotas para cada sub-rede dentro de uma rede virtual do Azure e adiciona as rotas padrão de sistema à tabela. Você pode adicionar tabelas de rotas personalizadas para modificar o tráfego entre sub-redes e redes virtuais.
- **Subnet Delegation** Você pode designar a sub-rede para ser usado por um serviço dedicado.

### Configurar redes virtuais

Depois de criar uma rede virtual, você poderá alterar configurações adicionais no painel Redes virtuais no portal do Azure ou usar comandos do PowerShell ou comandos no Cloud Shell.

- **Address spaces**: você pode adicionar mais espaços de endereço à definição inicial.
- **Connected devices**: veja uma lista de todos os host conectados na rede virtual.
- **Subnets**: você pode adicionar outras sub-redes.
- **DDos protection**: você pode habilitar ou desabilitar o plano de proteção contra DDos Padrão.
- **Firewall**: defina as configurações de firewall com o serviço de Firewall do Azure para a rede virtual.
- **Security**: fornece recomendação de segurança que você pode aplicar à sua rede virtual.
- **Network Manager**: veja a configuração de administrador de segurança e conectividade à qual a rede virtual está associada.
- **DNS servers**: configure os servidores DNS internos ou externos que os recursos na rede virtual usarão.
- **Peerings**: vincule redes virtuais nas disposições de emparelhamento.
- **Service endpoints**: habilita pontos de extremidade de serviço e os aplica a várias sub-redes.
- **Private endpoints**: veja uma lista de endpoints privados habilitados em uma sub-rede.

Você também pode monitorar e exibir métricas para solucionar problemas em suas redes virtuais.

Redes virtuais são mecanismos avançados e altamente configuráveis para conectar entidades no Azure. Você pode conectar recursos do Azure entre si ou aos recursos existentes no local. Você pode isolar, filtrar e rotear o tráfego de rede. O Azure permite que você aumente a segurança onde achar necessário.

### Conceitos básicos do Gateway de VPN do Azure

VPNs usam um túnel criptografado dentro de outra rede. Normalmente, elas são implantadas para conectar duas ou mais redes privadas confiáveis entre si em uma rede não confiável (normalmente a Internet pública). O tráfego é criptografado ao viajar pela rede não confiável para evitar interceptação ou outros ataques.

### Gateways VPN

Um gateway de VPN é um tipo de gateway de rede virtual. As instâncias do Gateway de VPN do Azure são implantadas em uma subrede dedicada da rede virtual e permitem a seguinte conectividade:

- Conecte datacenters on-premises a redes virtuais por meio de uma conexão site-to-site.
- Conecte dispositivos individuais a redes virtuais por meio de uma conexão point-to-site.
- Conecte redes virtuais a outras redes virtuais por meio de uma conexão network-to-network.

![vpngateway-site-to-site-connection-diagram](https://docs.microsoft.com/en-us/learn/azure-fundamentals/azure-networking-fundamentals/media/vpngateway-site-to-site-connection-diagram-0e1e7db2.png)

- Você só poderá implantar 1 gateway de VPN em cada rede virtual, mas poderá usar um gateway para se conectar a vários locais, incluindo outras redes virtuais ou datacenters locais.
- Ao implantar um gateway de VPN, você especifica o tipo de VPN: baseada em política (policy-based) ou baseada em rota (route-based). 
    - A principal diferença entre esses dois tipos de VPN é como o tráfego a ser criptografado é especificado. 
    - Ambos usam uma chave pré-compartilhada como o único método de autenticação. 
    - Ambos os tipos também dependem do protocolo IKE na versão 1 ou na versão 2 e do protocolo IPsec. 
    - O IKE é usado para configurar uma associação de segurança (um contrato da criptografia) entre dois pontos de extremidade. Essa associação é passada para o conjunto do IPsec, que criptografa e descriptografa os pacotes de dados encapsulados no túnel VPN.

### Policy-based VPNs

Gateways de VPN baseados em política especificam estaticamente o endereço IP dos pacotes que devem ser criptografados por meio de cada túnel. Esse tipo de dispositivo avalia cada pacote de dados em relação a esses conjuntos de endereços IP para escolher o túnel para o qual o pacote será enviado.

 Principais recursos dos gateways de VPN baseados em políticas:

 - Suporte apenas para IKEv1.
- O uso do roteamento estático (static routing), em que as combinações de prefixos de endereço de ambas as redes controlam o modo como o tráfego é criptografado e descriptografado por meio do túnel VPN. A origem e o destino das redes por túnel são declarados na política e não precisam ser declarados em tabelas de roteamento.
- As VPNs baseadas em política devem ser usadas em cenários específicos que as exigem, por exemplo, para compatibilidade com os dispositivos VPN locais herdados.

### Route-based VPNs

Caso seja muito complicado definir quais endereços IP estão por trás de cada túnel, será possível usar gateways baseados em rota. Com isso, os túneis IPSec são modelados como uma interface de rede ou uma interface de túnel virtual. O roteamento de IP (protocolos de roteamento dinâmico ou rotas estáticas) decide qual dessas interfaces de túnel usar ao enviar cada pacote. VPNs baseadas em rota são o método preferido para conectar dispositivos locais. Elas são mais resilientes a alterações de topologia, como a criação de novas sub-redes.

Use um gateway de VPN baseado em rota se precisar de qualquer um dos seguintes tipos de conectividade:

- Conexões entre redes virtuais
- Conexões point-to-site
- Conexões multissite
- Coexistência com um gateway do Azure ExpressRoute

Principais recursos de gateways de VPN baseados em rota:

- Dá suporte ao IKEv2
- Usa seletores de tráfego any-to-any (wildcard)
- Pode usar protocolos de roteamento dinâmico (dynamic routing protocols), em que as tabelas de roteamento/encaminhamento direcionam o tráfego para túneis IPsec diferentes. Nesse caso, as redes de origem e de destino não são definidas estaticamente, pois estão em VPNs baseadas em políticas ou mesmo em VPNs baseadas em rota com roteamento estático. Em vez disso, os pacotes de dados são criptografados com base em tabelas de roteamento de rede que são criadas dinamicamente usando protocolos de roteamento como o BGP (Border Gateway Protocol).

### Tamanhos do gateway de VPN

|SKU|Túneis de site a site/rede a rede|Parâmetro de comparação de taxa de transferência agregada|Suporte ao BGP (Border Gateway Protocol)|
|--|--|--|--|
|Básico [Veja a Observação]|Máximo: 10|100 Mbps|Sem suporte|
|VpnGw1/Az|Máximo: 30|650 Mbps|Com suporte|
|VpnGw2/Az|Máximo: 30|1 Gbps|Com suporte|
|VpnGw3/Az|Máximo: 30|1,25 Gbps|Com suporte|
|VpnGw4/Az|Máximo: 100|5 Gbps|Com suporte|
|VpnGw5/Az|Máximo: 100|10 Gbps|Com suporte|

> Um Gateway de VPN Básico deve ser usado apenas para cargas de trabalho de Desenvolvimento/Teste. Além disso, não há suporte para migrar do Básico para os SKUs VpnGW1/2/3/Az posteriormente sem precisar remover e reimplantar o gateway.

### Deploy VPN gateways

Serão necessários os seguintes recursos do Azure antes que você possa implantar um gateway de VPN operacional:

- **Rede virtual**. Implante uma rede virtual com espaço de endereço suficiente para a sub-rede adicional que será necessária para o gateway de VPN. 
    - O espaço de endereço dessa rede virtual não pode se sobrepor à rede local à qual você se conectará. 
    - Só é possível implantar um único gateway de VPN em uma rede virtual.

- **GatewaySubnet**. Implante uma sub-rede chamada GatewaySubnet para o gateway de VPN. Use uma máscara de endereço de pelo menos /27 para garantir que você tenha endereços IP suficientes na sub-rede para crescimento futuro.    
    - Não é possível usar essa sub-rede para nenhum outro serviço.

- **Endereço IP público**. Crie um endereço IP público dinâmico do SKU Básico se você estiver usando um gateway sem reconhecimento de zona. Esse endereço fornece um endereço IP roteável público como o destino do dispositivo VPN local. 
    - Embora esse endereço IP seja dinâmico, ele não será alterado a menos que você exclua e recrie o gateway de VPN.

- **Gateway de rede local**. Crie um gateway de rede local para definir a configuração da rede local, como onde o gateway de VPN se conectará e a que ele se conectará. Essa configuração inclui o endereço IPv4 público do dispositivo VPN local e as redes roteáveis locais. Essas informações são usadas pelo gateway de VPN para rotear, por meio do túnel IPsec, pacotes destinados a redes locais.

- **Gateway de rede virtual**. Crie o gateway de rede virtual para rotear tráfego entre a rede virtual e o datacenter on-premises ou outras redes virtuais. O gateway de rede virtual pode ser um gateway de VPN ou ExpressRoute, mas esta unidade lida apenas com gateways de rede virtual de VPN. 

- **Connection**. Crie um recurso de conexão para criar uma conexão lógica entre o gateway de VPN e o gateway de rede local.
    - A conexão é realizada com o endereço IPv4 do dispositivo VPN local conforme definido pelo gateway de rede local.
    - A conexão é realizada do gateway de rede virtual e seu endereço IP público associado.

> É possível criar várias conexões.

![resource-requirements-for-vpn-gateway](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-networking-fundamentals/media/resource-requirements-for-vpn-gateway-2518703e.png)

### Recursos locais necessários

Para conectar seu datacenter a um gateway de VPN, serão necessários os seguintes recursos locais:

- Um dispositivo VPN que dá suporte a gateways de VPN baseada em política ou em rota
- Um endereço IPv4 (roteável pela Internet) voltado para o público

### Cenários de alta disponibilidade

### Active/standby

Quando a manutenção planejada ou a interrupção não planejada afeta a instância ativa, a instância de modo de espera assume automaticamente a responsabilidade pelas conexões sem nenhuma intervenção do usuário. Durante esse failover, as conexões são interrompidas, mas normalmente são restauradas em alguns segundos para manutenção planejada e dentro de 90 segundos em caso de interrupções não planejadas.

![active-standby](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-networking-fundamentals/media/active-standby-c4a3c14d.png)

### Active/active

Nessa configuração, você atribui um endereço IP público exclusivo a cada instância. Em seguida, cria túneis do dispositivo local para cada endereço IP. É possível estender a alta disponibilidade implantando um dispositivo VPN local adicional.

![dual-redundancy](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-networking-fundamentals/media/dual-redundancy-d76100c9.png)

### Failover do ExpressRoute

Outra opção de alta disponibilidade é configurar um gateway de VPN como um caminho de failover seguro para conexões ExpressRoute.

Em cenários de alta disponibilidade, nos quais há risco associado a uma interrupção de um circuito do ExpressRoute, você também pode provisionar um gateway de VPN que usa a Internet como um método alternativo de conectividade. Dessa forma, você pode garantir que sempre haja uma conexão com as redes virtuais.

### Gateways com redundância de zona

Essa configuração oferece resiliência, escalabilidade e maior disponibilidade para os gateways de rede virtual. A implantação de gateways em zonas de disponibilidade do Azure separa de forma física e lógica os gateways em uma região, enquanto protege a conectividade de rede local com o Azure contra falhas no nível da zona. Esses gateways exigem SKUs de gateway diferentes e usam os endereços IP públicos Standard em vez dos Básicos.

### Conceitos básicos do ExpressRoute do Azure

 O ExpressRoute permite que você estenda suas redes locais para a nuvem da Microsoft em uma conexão privada com a ajuda de um provedor de conectividade. 

 A conectividade pode ocorrer de uma rede any-to-any (VPN de IP), uma rede Ethernet ponto a ponto ou uma conexão cruzada virtual por meio de um provedor de conectividade em uma colocação. 
 
- As conexões não passam pela Internet pública. 
- Mais confiabilidade, mais velocidade, latências consistentes
- mais segurança do que as conexões típicas pela Internet

![azure-expressroute-overview](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-networking-fundamentals/media/azure-expressroute-overview-5520731d.png)

![azure-expressroute-overview](https://docs.microsoft.com/en-us/learn/azure-fundamentals/azure-networking-fundamentals/media/azure-expressroute-overview-5520731d.png)

Nos concentraremos em duas camadas diferentes do modelo de OSI (Open Systems Interconnection):

- **Camada 2 (L2)**: essa é a Camada de Vínculo de Dados, que fornece comunicação de nó para nó entre dois nós na mesma rede.
- **Camada 3 (L3)**: essa é a Camada de Rede, que fornece endereçamento e roteamento entre nós em uma rede de vários nós.

### Recursos e benefícios do ExpressRoute

- Conectividade de Camada 3 entre sua rede local e a Microsoft Cloud por meio de um provedor de conectividade. A conectividade pode ocorrer de uma rede any-to-any (IPVPN), de uma conexão Ethernet ponto a ponto ou por meio de uma conexão cruzada virtual via troca Ethernet.

- Conectividade com os serviços de nuvem da Microsoft em todas as regiões da região geopolítica.

- Conectividade global com os serviços da Microsoft em todas as regiões com o complemento premium do ExpressRoute.

- Roteamento dinâmico entre sua rede e a Microsoft por meio do BGP.

- Redundância interna em cada local de emparelhamento para proporcionar maior confiabilidade.

- SLAdo tempo de atividade da conexão.

- Suporte a QoS para Skype for Business.

### Conectividade de Camada 3

O ExpressRoute oferece conectividade de Camada 3 (nível do endereço) entre sua rede local e a nuvem da Microsoft é fornecida por meio de parceiros de conectividade. Essas conexões podem ser de uma rede ponto a ponto ou any-to-any. Elas também podem ser conexões cruzadas virtuais por meio de uma troca.

### Redundância interna

Cada provedor de conectividade usa dispositivos redundantes para verificar se as conexões estabelecidas com a Microsoft estão altamente disponíveis. É possível configurar vários circuitos para complementar esse recurso. Todas as conexões redundantes são configuradas com conectividade de Camada 3 para atender aos contratos de nível de serviço.

### Conectividade com serviços em nuvem da Microsoft

O ExpressRoute permite acesso direto aos seguintes serviços em todas as regiões:

- Microsoft Office 365
- Microsoft Dynamics 365
- Serviços de computação do Azure, como as Máquinas Virtuais do Azure
- Serviços de Nuvem do Azure, como o Azure Cosmos DB e o Armazenamento do Azure

### Conectividade local com Alcance Global do ExpressRoute

Você pode habilitar o Alcance Global do ExpressRoute para trocar dados entre sites locais conectando seus circuitos do ExpressRoute. Por exemplo, suponha que você tenha um datacenter privado na Califórnia conectado ao ExpressRoute no Vale do Silício. Você tem outro datacenter privado no Texas conectado ao ExpressRoute em Dallas. Com o Alcance Global do ExpressRoute, você pode conectar seus datacenters privados por meio de dois circuitos do ExpressRoute. Seu tráfego entre datacenters percorrerá a rede da Microsoft.

### Roteamento dinâmico

O ExpressRoute usa o protocolo de roteamento BGP (Border Gateway Protocol). O BGP é usado para trocar rotas entre as redes locais e os recursos em execução no Azure. Esse protocolo permite o roteamento dinâmico entre a rede local e os serviços em execução na nuvem da Microsoft.

### Modelos de conectividade do ExpressRoute

O ExpressRoute dá suporte aos seguintes modelos que podem ser usados para conectar sua rede local à nuvem da Microsoft:

- Colocação do CloudExchange
- Conexão Ethernet point-to-point
- Conexão any-to-any
- Direto de sites do ExpressRoute

![azure-connectivity-models](https://docs.microsoft.com/en-us/learn/azure-fundamentals/azure-networking-fundamentals/media/azure-connectivity-models-4deabab1.png)

![azure-connectivity-models](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-networking-fundamentals/media/azure-connectivity-models-4deabab1.png)

### Colocalização em um compartilhamento de nuvem

Normalmente, provedores colocalizados podem oferecer conexões de Camada 2 e Camada 3 entre sua infraestrutura, que podem estar localizadas nas instalações de colocalização e na nuvem da Microsoft. Por exemplo, se o seu datacenter estiver colocalizado em uma cloud exchange, como um ISP, você poderá solicitar uma conexão cruzada virtual (cross-connection) com a nuvem da Microsoft.

### Point-to-point Ethernet connection

Conexões ponto a ponto fornecem conectividade de Camada 2 e Camada 3 entre o local e o Azure. Você pode conectar seus escritórios ou data centers ao Azure usando links ponto a ponto. Por exemplo, se tiver um datacenter local, você poderá usar um link Ethernet ponto a ponto para se conectar à Microsoft.

### Any-to-any networks

Com a conectividade any-to-any, você pode integrar sua WAN (rede de longa distância) ao Azure fornecendo conexões aos seus escritórios e datacenters. O Azure é integrado à sua conexão WAN para fornecer uma conexão, da mesma forma que você teria entre o datacenter e as filiais.

Com conexões any-to-any, todos os provedores de WAN oferecem conectividade de Camada 3. Por exemplo, caso você já use Multiprotocol Label Switching para se conectar às suas filiais ou a outras unidades de sua organização, uma conexão do ExpressRoute com a Microsoft se comporta como qualquer outra localização de sua WAN privada.

### ExpressRoute Direct sites

Você pode se conectar diretamente à rede global da Microsoft em um local de emparelhamento distribuído estrategicamente em todo o mundo. O ExpressRoute Direct fornece oferece conectividade dupla de 100 Gbps ou 10 Gbps, compatível com conectividade Ativa/Ativa em escala.

### Considerações sobre segurança

Com o ExpressRoute, os seus dados não passam pela Internet pública e, portanto, não são expostos aos riscos potenciais associados às comunicações da Internet. O ExpressRoute é uma conexão particular de sua infraestrutura local com a infraestrutura do Azure. Mesmo que você tenha uma conexão do ExpressRoute, consultas DNS, verificações de listas de certificados revogados e solicitações do Azure Content Delivery Network ainda serão enviadas pela Internet pública.

### Resumo

Você conheceu os benefícios e o uso da Rede Virtual do Azure, do Gateway de VPN do Azure e do Azure ExpressRoute.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

### 🔸 <a name="parte1-3"></a> Princípios básicos do Microsoft Azure: Descrever as principais soluções e ferramentas de gerenciamento no Azure

Ao final deste roteiro de aprendizagem, você poderá:

- Escolher o serviço de Inteligência Artificial do Azure correto para lidar com diferentes tipos de desafios de negócios.
- Escolher os melhores serviços e ferramentas de processo de desenvolvimento de software para um determinado cenário de negócios.
- Escolher o serviço de monitoramento de nuvem correto para lidar com diferentes tipos de desafios de negócios.
- Escolher a ferramenta de gerenciamento do Azure correta para abordar diferentes tipos de necessidades técnicas e desafios.
- Escolher a tecnologia de computação sem servidor certa para seu cenário de negócios.
- Escolher o melhor serviço de IoT do Azure para um determinado cenário de negócios.

Depois de concluir este módulo, você poderá:

- Escolher o serviço IoT do Azure mais adequado para lidar com seu cenário de negócios.

### Identificar as opções de produto

A IoT habilita os dispositivos para coletar e retransmitir informações a fim de obter uma análise dos dados. Os dispositivos inteligentes são equipados com sensores que coletam dados. Alguns sensores comuns que medem os atributos do mundo físico incluem:

- Sensores ambientais que capturam a temperatura e os níveis de umidade.
- Códigos de barras, códigos QR ou scanners de OCR (reconhecimento óptico de caracteres).
- Sensores de proximidade e localização geográfica.
- Sensores infravermelhos, de luz e cor.
- Sensores ultrassônicos e de som.
- Sensores de movimento e toque.
- Sensores de acelerômetro e inclinação.
- Sensores de fumaça, gás e álcool.
- Sensores de erro para detectar quando há um problema com o dispositivo.
- Sensores mecânicos que detectam anomalias ou deformações.
- Sensores de fluxo, nível e pressão para medir gases e líquidos.

Ao usar os serviços IoT do Azure, os dispositivos equipados com esses tipos de sensores e que podem se conectar à Internet poderão:

- Enviar leituras do sensor a um ponto de extremidade específico no Azure por meio de uma mensagem. 
- Os dados da mensagem serão coletados e agregados
- Od dados poderão ser convertidos em relatórios e alertas. 
- Todos os dispositivos poderão ser atualizados pelos serviços IoT do Azure.

Os dados coletados desses dispositivos poderão ser combinados com os serviços de IA do Azure para ajudar você a prever:

- Quando as máquinas precisarão de uma manutenção proativa.
- Quando os inventários deverão ser reabastecidos e novos produtos solicitados aos fornecedores.

### Hub IoT do Azure

É um serviço gerenciado e hospedado na nuvem que atua como um hub central de mensagens para obter uma comunicação bidirecional entre o seu aplicativo de IoT e os dispositivos que ele gerencia.

Depois que o hub IoT recebe mensagens de um dispositivo, ele pode roteá-las para outros serviços do Azure.

De uma perspectiva de nuvem para dispositivo, o Hub IoT permite executar o comando e controle. Isso significa que você pode ter um controle remoto manual ou automatizado de dispositivos conectados para que seja possível instruir o dispositivo a fim de abrir válvulas, definir temperaturas de destino, reiniciar dispositivos travados e assim por diante.

O monitoramento do Hub IoT ajuda a manter a integridade de sua solução pelo rastreamento de eventos, como criação de dispositivo, falhas do dispositivo e conexões de dispositivo.

### Azure IoT Central

Se baseia no Hub IoT adicionando um painel que permite que você conecte, monitore e gerencie os seus dispositivos IoT. Com a UI (interface do usuário) visual é fácil se conectar rapidamente com novos dispositivos e observar quando eles começam a enviar telemetria ou mensagens de erro.

- É possível observar o desempenho geral de todos os dispositivos em agregação. 
- Você pode configurar alertas que enviam notificações quando um dispositivo específico precisa de manutenção. 
- Você pode efetuar push de atualizações de firmware para o dispositivo.
- O IoT Central fornece modelos de início para cenários comuns em vários setores, como varejo, energia, serviços de saúde e administração pública. 
- Você pode usar a interface do usuário para controlar os seus dispositivos remotamente. 
- Usando um modelo de dispositivo, você poderá conectar um dispositivo sem uma codificação no lado do serviço.
- Os desenvolvedores de dispositivos ainda precisarão criar o código a ser executado nos dispositivos.

### Azure Sphere

Cria uma solução de IoT de ponta a ponta e altamente segura para os clientes. Essa solução abrange tudo, do hardware e sistema operacional no dispositivo a um método seguro de envio de mensagens do dispositivo para o hub de mensagens. O Azure Sphere tem recursos internos de comunicação e segurança para dispositivos conectados à Internet.

O Azure Sphere é fornecido em três partes:

- A primeira parte é o MCU (unidade do microcontrolador) do Azure Sphere, que é responsável por processar o sistema operacional e enviar sinais de sensores conectados. 
- A segunda parte é um OS (sistema operacional) Linux personalizado que administra a comunicação com o serviço de segurança e pode executar o software do fornecedor.
- A terceira parte é o Serviço de Segurança do Azure Sphere, também conhecido como AS3. O trabalho dele é verificar se o dispositivo não foi comprometido de modo malicioso. Quando o dispositivo tenta se conectar ao Azure, primeiro ele precisa se autenticar, por dispositivo. Ele faz isso usando uma autenticação baseada em certificado. Caso ele seja autenticado com êxito, o AS3 faz uma verificação para garantir que o dispositivo não foi adulterado. Depois de ter estabelecido um canal seguro de comunicação, o AS3 envia por push um sistema operacional ou atualizações de software desenvolvidas pelo cliente para o dispositivo.

Depois que o sistema do Azure Sphere tiver validado a autenticidade do dispositivo e feito a autenticação dele, o dispositivo poderá interagir com outros serviços IoT do Azure enviando informações de telemetria e de erro.

### Analisar os critérios de decisão

Critérios que os especialistas empregam quando decidem qual serviço IoT usar para uma determinada necessidade comercial.

#### É essencial garantir que o dispositivo não seja comprometido?

Não em todos os casos. Os fabricantes e os clientes não querem que os respectivos dispositivos sejam comprometidos por ações mal-intencionadas e usados para fins maliciosos, mas, em alguns casos, a garantia da integridade é mais crítica do que em outros. Um exemplo seria um caixa eletrônico em comparação com uma máquina de lavar roupas. Quando a segurança é uma consideração crítica no design do seu produto, a melhor opção de produto é o Azure Sphere, que fornece uma solução abrangente de ponta a ponta para dispositivos IoT.

Como mencionamos na unidade anterior, o Azure Sphere garante um canal seguro de comunicação entre o dispositivo e o Azure controlando tudo, do hardware ao sistema operacional, além do processo de autenticação. Isso garante que a integridade do dispositivo não seja comprometida. Depois que um canal seguro for estabelecido, o dispositivo poderá receber mensagens com segurança. Além disso, as mensagens ou atualizações de software poderão ser enviadas ao dispositivo de maneira remota.

#### Preciso de um painel para relatórios e gerenciamento?

Sua próxima decisão deverá ser baseada no nível dos serviços que você exige de sua solução de IoT. Caso queira somente se conectar aos dispositivos remotos para receber telemetria e, ocasionalmente, enviar atualizações por push e não há necessidade de obter funcionalidades de relatório, talvez você prefira implementar somente o Hub IoT do Azure. Seus programadores ainda poderão criar um conjunto personalizado de ferramentas e relatórios de gerenciamento usando a API RESTful do Hub IoT.

No entanto, caso queria uma interface do usuário personalizável e pré-criada com a qual será possível exibir e controlar seus dispositivos de maneira remota, talvez você prefira começar com o IoT Central. Com essa solução, será possível controlar um dispositivo ou todos eles de uma vez. Além disso, você poderá configurar alertas para determinadas condições, como uma falha do dispositivo.

O IoT Central integra-se com muitos produtos diferentes do Azure, incluindo o Hub IoT, para criar um painel com relatórios e recursos de gerenciamento. O painel é baseado em modelos de início para cenários comuns de uso e do setor. Será possível usar o painel gerado pelo modelo de início como está ou personalizá-lo para atender às suas necessidades. Você poderá ter vários painéis e direcioná-los a uma variedade de usuários.

A IoT é uma evolução empolgante na computação que conecta os mundos físicos e digitais. Os serviços IoT do Azure fornecem uma quantidade significativa de funcionalidades para as organizações que desejam criar soluções controladas por dispositivos e sensores.


🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

### 🔸 <a name="parte1-4"></a> Princípios básicos do Microsoft Azure: Descrever os recursos gerais de segurança de rede e segurança

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

### 🔸 <a name="parte1-5"></a> Princípios básicos do Microsoft Azure: Descrever recursos de identidade, governança, privacidade e conformidade

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

### 🔸 <a name="parte1-6"></a> Princípios básicos do Microsoft Azure: Descrever contratos de nível de serviço e Gerenciamento de Custos da Microsoft

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

## ☁️ <a name="parte2"></a>