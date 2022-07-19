# Skills measured

- Describe cloud concepts (25-30%)
- Describe Azure architecture and services (35-40%)
- Describe Azure management and governance (30-35%)

## Functional groups

## Describe cloud concepts (25-30%)

### Describe cloud computing

- Define cloud computing
	- É a entrega de serviços de computação pela Internet. Esses serviços incluem servidores, armazenamentos, bancos de dados, redes, software, análises e inteligência. A computação em nuvem oferece inovação mais rápida, recursos flexíveis e economias de escala.

- Describe the shared responsibility model
	- Num datacenter corporativo tradicional a empresa é responsável por manter o espaço físico, garantir a segurança e manter ou substituir os servidores se algo acontecer. TI é responsável por manter toda a infraestrutura e o software necessários para manter o datacenter em funcionamento. É provável que eles também sejam responsáveis por manter todos os sistemas corrigidos e na versão correta.
	- Na núvem, essas responsabilidades são compartilhadas entre o provedor de nuvem e o consumidor. 
		- Responsabilidade do provedor de nuvem: Segurança física, energia, resfriamento e conectividade de rede. 
		- O consumidor: é responsável pelos dados e pelas informações armazenados na nuvem e pela segurança de acesso, o que significa que você só dá acesso àqueles que precisam.

	- Então, para algumas coisas, a responsabilidade depende da situação. 
		- A IaaS coloca a maior responsabilidade sobre o consumidor, com o provedor de nuvem sendo responsável pelas questões básicas de segurança física, energia e conectividade. 
		- O SaaS coloca a maior parte da responsabilidade no provedor de nuvem. 
		- A PaaS, sendo um meio termo entre IaaS e SaaS, distribui uniformemente a responsabilidade entre o provedor de nuvem e o consumidor.

	- Você sempre será responsável por:
		- Informações e dados armazenados na nuvem
		- Dispositivos que têm permissão para se conectar à nuvem (telefones celulares, computadores e assim por diante)
		- Contas e identidades das pessoas, serviços e dispositivos em sua organização
	- O provedor de nuvem é sempre responsável por:
		- Datacenter físico
		- Rede física
		- Hosts físicos

### Define cloud models, including public, private, and hybrid

- **Nuvem pública** - Os serviços são oferecidos pela Internet pública e disponíveis para qualquer pessoa que deseje comprá-los. 
	- Uma nuvem pública é criada, controlada e mantida por um provedor de nuvem de terceiros.
	- Nenhuma despesa de capital para escalar verticalmente.
	- Os aplicativos podem ser provisionados e desprovisionados rapidamente.
	- As organizações pagam apenas pelo que utilizam.
- **Nuvem privada** - É uma nuvem (que fornece serviços de TI pela Internet) que é criada, controlada e mantida por uma única entidade. consiste em recursos de computação usados exclusivamente por usuários de uma empresa/organização. Pode estar localizada fisicamente no datacenter (local) da organização ou hospedada por um provedor de serviços de terceiros.
	- O hardware deve ser comprado para inicialização e manutenção.
	- A nuvem privada fornece um controle muito maior para a empresa e o departamento de TI. 
	- Ela também tem mais custos e menos benefícios em relação a uma implantação de nuvem pública. 
	- As organizações são responsáveis pela manutenção e pelas atualizações de hardware.
- **Nuvem híbrida** - é um ambiente de computação que combina uma nuvem pública e uma nuvem privada, permitindo que dados e aplicativos sejam compartilhados entre elas.
	- Fornece a maior flexibilidade.
	- As organizações determinam onde executar seus aplicativos.
	- As organizações controlam a segurança, a conformidade ou os requisitos legais.

### Identify appropriate use cases for each cloud model

- **Describe the consumption-based model**
	- Na computação em nuvem, você não paga pela infraestrutura física, pela eletricidade, pela segurança nem por nada que esteja associado à manutenção de um datacenter. Você paga pelos recursos de TI que usa. 
		- **Modelo baseado em consumo**. As organizações pagam apenas pelo que usam e operam em um modelo de OpEx (despesas operacionais).
		- **OpEx** - é o gasto de capital em serviços ou produtos ao longo do tempo. O aluguel de um centro de convenções, o leasing de um veículo da empresa ou a assinatura de serviços de nuvem são exemplos de OpEx.
		- **CapEx** - normalmente é uma despesa inicial única para comprar ou proteger recursos tangíveis. Um prédio novo, a repavimentação do estacionamento, a construção de um datacenter ou a compra de um veículo da empresa são exemplos de CapEx.
	- Um modelo baseado em consumo oferece vários benefícios, como:
		- Sem custos prévios.
		- Não há necessidade de comprar nem gerenciar uma infraestrutura cara que os usuários talvez não usem na capacidade máxima.
		- A capacidade de pagar para obter mais recursos quando necessário.
		- A capacidade de parar de pagar por recursos que não são mais necessários.

	- **Compare cloud pricing models**
		- Avaliação gratuita - Uma assinatura de avaliação gratuita fornece 12 meses de serviços gratuitos populares, um crédito para explorar qualquer serviço do Azure por 30 dias e mais de 25 serviços que são sempre gratuitos. Os serviços do Azure são desabilitados quando a avaliação termina ou quando seu crédito expira para produtos pagos, a menos que você atualize para uma assinatura paga.
		- Pago conforme o uso - Uma assinatura com Pagamento Conforme o Uso permite que você pague pelo que usar vinculando um cartão de crédito ou débito à sua conta. As organizações podem se candidatar a descontos por volume e a faturamento pré-pago.
		- Ofertas de membro - Sua associação existente a determinados produtos e serviços da Microsoft pode fornecer créditos para sua conta do Azure e taxas reduzidas nos serviços do Azure. Por exemplo, ofertas de membros estão disponíveis para assinantes do Visual Studio, membros da Microsoft Partner Network, membros da Microsoft para Startups e membros do Microsoft Imagine.

### Describe the benefits of using cloud services

- Alta disponibilidade, escalabilidade e distribuição geográfica. 
- Describe the benefits of high availability and scalability in the cloud
	- **Alta disponibilidade**: dependendo do SLA que você escolher, seus aplicativos poderão oferecer uma experiência de usuário contínua, sem tempo de inatividade aparente, mesmo quando as coisas derem errado.
	
	- **Escalabilidade**: os aplicativos na nuvem podem ser dimensionados verticalmente e horizontalmente:
		- **Dimensione verticalmente** - aumentar a capacidade de computação adicionando RAM ou CPUs a uma máquina virtual.
		- **Dimensionar horizontalmente** - aumentar a capacidade de computação adicionando instâncias de recursos.

- Describe the benefits of reliability and predictability in the cloud
	- **Confiabilidade** garante que seu aplicativo possa cumprir os compromissos que você assume com seus clientes.
		- A confiabilidade é uma responsabilidade compartilhada
		- Garante que suas cargas de trabalho fiquem disponíveis e possam se recuperar de falhas em qualquer escala.
		- **Recuperação de desastre**: ao aproveitar os serviços de backup baseados em nuvem, a replicação de dados e a distribuição geográfica, você pode implantar os aplicativos com a confiança de saber que seus dados estarão seguros em caso de desastre.
	
	- **Previsibilidade** - uma solução com custo e desempenho previsíveis. A previsibilidade na nuvem permite que você avance com confiança.
		- **Previsibilidade de Desempenho** - se concentra em prever os recursos necessários para oferecer uma experiência positiva aos clientes. O dimensionamento automático, o balanceamento de carga e a alta disponibilidade são apenas alguns dos conceitos de nuvem que dão suporte à previsibilidade de desempenho.
        - **Previsibilidade de custos** - se concentra em prever o custo dos gastos com a nuvem. Operando na nuvem e usando a análise e as informações da nuvem, você pode prever custos futuros e ajustar os recursos conforme o necessário. Você pode até mesmo usar ferramentas como TCO (custo total de propriedade) ou a Calculadora de Preços para obter uma estimativa de possíveis gastos com a nuvem.

	- Describe the benefits of security and governance in the cloud
		- Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

		- **Governança** - Se você estiver implantando IaaS ou SaaS, os recursos de nuvem vão dar suporte à governança e à conformidade. 
			- Itens como modelos de conjunto ajudam a garantir que todos os seus recursos implantados atendam aos padrões corporativos e aos requisitos regulatórios governamentais. 
			- atualização dos recursos implantados com os novos padrões à medida que são alterados. 
			- Sinalização de qualquer recurso que esteja fora de conformidade e fornece estratégias de mitigação. 
			- Dependendo do modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente.

		-  **Segurança** - Se você quiser o controle máximo da segurança, a IaaS fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção.  Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de PaaS ou SaaS podem ser as melhores estratégias de nuvem para você.

	- Describe the benefits of manageability in the cloud
		- Escalar automaticamente a implantação de recursos com base na necessidade.
		- Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
		- Monitorar a integridade dos recursos e substituir automaticamente os recursos com falha.
		- Receber alertas automáticos com base em métricas configuradas, de modo a ficar ciente do desempenho em tempo real.

### Describe cloud service types

- **Describe infrastructure as a service (IaaS)**
	- O IaaS (infraestrutura como serviço) é a categoria mais flexível de serviços de nuvem, pois oferece:
	- O máximo de controle sobre os recursos de nuvem. 
	- O provedor de nuvem é responsável por manter o hardware, a conectividade de rede (com a Internet) e a segurança física. 
	- Você é responsável por todo o resto: 
		- instalação, configuração e manutenção do sistema operacional
		- configuração de rede
		- configuração de banco de dados e armazenamento e assim por diante. 

- Com o IaaS, basicamente o hardware é alugado em um datacenter de nuvem, mas cabe a você decidir o que fazer com ele.

- **Describe platform as a service (PaaS)**
	- O PaaS é adequado para fornecer um ambiente de desenvolvimento completo sem a preocupação de manter toda a infraestrutura de desenvolvimento. Em um cenário de PaaS, você não precisa se preocupar com o licenciamento nem com a aplicação de patch em sistemas operacionais e bancos de dados.
	- O provedor de nuvem é responsável por:
		- manter a infraestrutura física e o acesso à Internet, como no IaaS. 
		- o provedor de nuvem também mantém:
			- os sistemas operacionais
			- os bancos de dados 
			- ferramentas de desenvolvimento. 

- **Describe software as a service (SaaS)**

- O SaaS (software como serviço) é o modelo de serviço de nuvem mais completo do ponto de vista do produto. Com o SaaS, você está essencialmente alugando ou usando um aplicativo totalmente desenvolvido. Embora o modelo de SaaS possa ser o menos flexível, ele também é o mais fácil de colocar em funcionamento. Ele requer a menor quantidade de conhecimento técnico ou experiência para o emprego total.

- Em um ambiente de SaaS, você é responsável: 
	- pelos dados que coloca no sistema
	- pelos dispositivos que permite que se conectem ao sistema
	- pelos usuários que têm acesso. 

- O provedor de nuvem é responsável pela segurança física dos datacenters, pela energia, pela conectividade de rede e pelo desenvolvimento e aplicação de patch dos aplicativos.

- Identify appropriate use cases for each cloud service (IaaS, PaaS, SaaS)

- **IaaS**
	- Migração lift-and-shift: você conta com recursos de nuvem semelhantes aos do datacenter local e apenas migra os elementos em execução local para execução na infraestrutura IaaS.
	- Teste e desenvolvimento: você estabeleceu configurações para ambientes de desenvolvimento e teste que precisa replicar rapidamente. Você pode ativar ou desativar os diferentes ambientes rapidamente com uma estrutura de IaaS, mantendo o controle completo.
- **PaaS**
	- Est1rutura de desenvolvimento: O PaaS fornece uma estrutura que os desenvolvedores podem usar como base para desenvolver ou personalizar aplicativos baseados em nuvem. O PaaS permite aos desenvolvedores criar aplicativos usando componentes de software internos. São incluídos recursos de nuvem, como escalabilidade, alta disponibilidade e a funcionalidade de multilocatário, reduzindo a quantidade de codificação que os desenvolvedores precisam realizar.
	- Análise ou business intelligence: as ferramentas fornecidas como serviço com o PaaS permitem que as organizações analisem e minerem dados, encontrando insights e padrões e prevendo resultados para aprimorar a previsão, as decisões de design de produto, o retornos sobre investimentos e outras decisões de negócios.
- **SaaS**
	- Email e mensagens.
	- Aplicativos de produtividade empresarial.
	- Controle de finanças e despesas.

## Describe Azure architecture and services (35-40%)

- Describe the core architectural components of Azure
	- Describe Azure regional, regional pairs, and sovereign regions
	- Describe availability zones
	- Describe Azure datacenters
- Describe Azure resources and resource groups
	- Describe subscriptions
	- Describe management groups
	- Describe the hierarchy of resource groups, subscriptions, and management groups
- Describe Azure compute and networking services
	- Compare compute types, including container instances, virtual machines (VMs), and functions
	- Describe VM options, including Azure Virtual Machines, Azure Virtual Machine Scale Sets, availability sets, and Azure Virtual Desktop
	- Describe resources required for virtual machines
	- Describe application hosting options, including the Web Apps feature of Azure App Service, containers, and virtual machines
	- Describe virtual networking, including the purpose of Azure Virtual Networks, Azure virtual subnets, peering, Azure DNS, Azure VPN Gateway, and Azure ExpressRoute
	- Define public and private endpoints
- Describe Azure storage services
	- Compare Azure storage services
	- Describe storage tiers
	- Describe redundancy options
	- Describe storage account options and storage types
	- Identify options for moving files, including AzCopy, Azure Storage Explorer, and Azure File Sync
	- Describe migration options, including Azure Migrate and Azure Data Box
- Describe Azure identity, access, and security
	- Describe directory services in Azure, including Azure Active Directory (Azure AD) and Azure
- Active Directory Domain Services (Azure AD DS)
	- Describe authentication methods in Azure, including single sign-on (SSO), multifactor authentication, and passwordless
	- Describe external identities and guest access in Azure
	- Describe Azure AD Conditional Access
	- Describe Azure role-based access control (RBAC)
	- Describe the concept of Zero Trust
	- Describe the purpose of the defense in depth model
	- Describe the purpose of Microsoft Defender for Cloud

## Describe Azure management and governance (30-35%)

- Describe cost management in Azure
	- Describe factors that can affect costs in Azure
	- Compare the Pricing calculator and the Total Cost of Ownership (TCO) calculator Describe the Azure Cost Management and Billing tool
	- Describe the purpose of tags
- Describe features and tools in Azure for governance and compliance
	- Describe the purpose of Azure Blueprints
	- Describe the purpose of Azure Policy
	- Describe the purpose of resource locks
	- Describe the purpose of the Service Trust Portal
- Describe features and tools for managing and deploying Azure resources
	- Describe the Azure portal
	- Describe Azure Cloud Shell, including Azure CLI and Azure PowerShell
	- Describe the purpose of Azure Arc
		- O Azure Arc é uma ponte que estende a plataforma do Azure para ajudar na criação de aplicativos e serviços com a flexibilidade de executar em datacenters, na borda e em ambientes multinuvem. Desenvolva aplicativos nativos de nuvem com um modelo consistente de desenvolvimento, operações e segurança. O Azure Arc é executado em hardware, virtualização e plataformas de Kubernetes, dispositivos IoT e sistemas integrados novos e existentes.
		
	- Describe Azure Resource Manager and Azure Resource Manager templates (ARM templates)
- Describe monitoring tools in Azure
	- Describe the purpose of Azure Advisor
	- Describe Azure Service Health
	- Describe Azure Monitor, including Log Analytics, Azure Monitor alerts, and Application Insights



A Política de Privacidade da Microsoft fornece informações relevantes sobre serviços específicos, incluindo a Cortana.
A Política de Privacidade da Microsoft proporciona confiança na forma como a Microsoft coleta, protege e usa dados do cliente.

A Central de Confiabilidade fornece documentação sobre padrões de conformidade e sobre como o Azure pode dar suporte à sua empresa.
A Central de Confiabilidade é um excelente recurso para as pessoas de sua organização que podem desempenhar funções de segurança, privacidade e conformidade.

Os Termos dos Serviços Online são um contrato legal entre a Microsoft e o cliente que detalha as obrigações das duas partes em relação ao processamento e à segurança de dados do cliente e dados pessoais.

A documentação de conformidade do Azure inclui informações detalhadas sobre a conformidade e os padrões legais e regulatórios no Azure.
A documentação de conformidade fornece blueprints de referência, ou definições de política, para padrões comuns que podem ser aplicados à sua assinatura do Azure.
