# Skills measured

- Describe cloud concepts (25-30%)
- Describe Azure architecture and services (35-40%)
- Describe Azure management and governance (30-35%)

## Functional groups

## Describe cloud concepts (25-30%)

- Describe cloud computing
	- Define cloud computing
		- É a entrega de serviços de computação pela Internet.

	- Describe the shared responsibility model

	- Define cloud models, including public, private, and hybrid
		- **Nuvem pública** - Os serviços são oferecidos pela Internet pública e disponíveis para qualquer pessoa que deseje comprá-los. São de propriedade e operados por um provedor de serviços de nuvem de terceiros e entregues pela Internet.
			- Nenhuma despesa de capital para escalar verticalmente.
			- Os aplicativos podem ser provisionados e desprovisionados rapidamente.
			- As organizações pagam apenas pelo que utilizam.
		- **Nuvem privada** - consiste em recursos de computação usados exclusivamente por usuários de uma empresa/organização. Pode estar localizada fisicamente no datacenter (local) da organização ou hospedada por um provedor de serviços de terceiros.
			- O hardware deve ser comprado para inicialização e manutenção.
			- As organizações têm controle total sobre os recursos e a segurança.
			- As organizações são responsáveis pela manutenção e pelas atualizações de hardware.
		- **Nuvem híbrida** - é um ambiente de computação que combina uma nuvem pública e uma nuvem privada, permitindo que dados e aplicativos sejam compartilhados entre elas.
			- Fornece a maior flexibilidade.
			- As organizações determinam onde executar seus aplicativos.
			- As organizações controlam a segurança, a conformidade ou os requisitos legais.

	- Identify appropriate use cases for each cloud model
	- Describe the consumption-based model
	- Compare cloud pricing models
- Describe the benefits of using cloud services
	- Describe the benefits of high availability and scalability in the cloud
		- **Alta disponibilidade**: dependendo do SLA que você escolher, seus aplicativos poderão oferecer uma experiência de usuário contínua, sem tempo de inatividade aparente, mesmo quando as coisas derem errado.
		- **Escalabilidade**: os aplicativos na nuvem podem ser dimensionados verticalmente e horizontalmente:
    		- **Dimensione verticalmente** - aumentar a capacidade de computação adicionando RAM ou CPUs a uma máquina virtual.
    		- **Dimensionar horizontalmente** - aumentar a capacidade de computação adicionando instâncias de recursos.

	- Describe the benefits of reliability and predictability in the cloud
		- **Recuperação de desastre**: ao aproveitar os serviços de backup baseados em nuvem, a replicação de dados e a distribuição geográfica, você pode implantar os aplicativos com a confiança de saber que seus dados estarão seguros em caso de desastre.
		- 

	- Describe the benefits of security and governance in the cloud
	- Describe the benefits of manageability in the cloud
- Describe cloud service types
	- Describe infrastructure as a service (IaaS)
	- Describe platform as a service (PaaS)
	- Describe software as a service (SaaS)
	- Identify appropriate use cases for each cloud service (IaaS, PaaS, SaaS)

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
