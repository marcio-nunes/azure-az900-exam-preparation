# <a name="topo"></a>Preparação para o exame Azure AZ-900

[Microsoft Learn path](https://docs.microsoft.com/pt-br/learn/paths/az-900-describe-cloud-concepts/)

Icons ☁️🔸

- [Parte 1: Princípios básicos do Microsoft Azure: descrever os principais conceitos do Azure](#parte1)
- [Parte 2: Descrever os principais serviços do Azure](#parte2)
- [Parte 3: Descrever as principais soluções e ferramentas de gerenciamento no Azure](#parte3)
- [Parte 4: Descrever os recursos gerais de segurança de rede e segurança](#parte4)
- [Parte 5: Descrever recursos de identidade, governança, privacidade e conformidade](#parte5)
- [Parte 6: descrever contratos de nível de serviço e Gerenciamento de Custos da Microsoft](#parte6)

# ☁️ <a name="parte1"></a>Parte 1: Princípios básicos do Microsoft Azure: descrever os principais conceitos do Azure

Depois de concluir este roteiro de aprendizagem, você poderá:

- Entenderá os benefícios da computação em nuvem e como ela pode poupar tempo e dinheiro
- Explicar conceitos de nuvem (alta disponibilidade, escalabilidade, elasticidade, agilidade e recuperação de desastre)
- Descrever os principais componentes da arquitetura (subscription, managment groups, resource e resource group)
- Resumir conceitos de distribuição geográfica (regiões do Azure, pares de regiões e zonas de disponibilidade)

1. [Introdução aos conceitos básicos do Azure](#Introdução_aos_conceitos_básicos_do_Azure)
2. [Discutir conceitos fundamentais do Azure](#Discutir_conceitos_fundamentais_do_Azure)
3. [Descrever os principais componentes da arquitetura do Azure](#Descrever_os_principais_componentes_da_arquitetura_do_Azure)


## 🔸 <a name="Introdução_aos_conceitos_básicos_do_Azure"></a>Introdução aos conceitos básicos do Azure

Após concluir este módulo, você poderá:

- Descrever os conceitos básicos da computação em nuvem.
- Determinar se o Azure é a solução certa para suas necessidades de negócios.
- Diferenciar entre os diferentes métodos de criação de uma assinatura do Azure.

O Azure é uma plataforma de computação em nuvem com um conjunto de serviços em constante expansão, projetado para ajudar você a criar soluções e cumprir suas metas de negócios. 

O Azure fornece uma infinidade de serviços baseados em nuvem:

- Armazenamento remoto
- Hospedagem de banco de dados 
- Gerenciamento de conta centralizado
- Rede
- VMs
- IA 
- IoT (Internet das Coisas)
- Outros

### Preparação para o Exame AZ-900

Esse exame inclui seis áreas de domínio de conhecimento:

|Área de domínio do AZ-900|Weight|
|-|-|
|Descrever os conceitos da nuvem|20-25%|
|Descrever os principais serviços do Azure|15-20%|
|Descrever as principais soluções e ferramentas de gerenciamento no Azure|10-15%|
|Descrever os recursos gerais de segurança de rede e segurança|10-15%|
|Descrever recursos de identidade, governança, privacidade e conformidade|20-25%|
|Descrever os Contratos de Nível de Serviço e o Gerenciamento de Custos da Microsoft|10-15%|

### O que é a computação em nuvem?

É a entrega de serviços de computação pela Internet. Esses serviços incluem servidores, armazenamentos, bancos de dados, redes, software, análises e inteligência. A computação em nuvem oferece inovação mais rápida, recursos flexíveis e economias de escala.

### Por que a computação em nuvem normalmente é mais econômica?

Normalmente, você paga apenas pelos serviços de nuvem que usa, o que ajuda a:

- Reduzir os custos operacionais.
- Executar a infraestrutura com mais eficiência.
- Escale as operações de acordo com as necessidades de negócios.

A computação em nuvem é uma forma de alugar capacidade computacional e armazenamento do datacenter de terceiros. Você será cobrado apenas pelo que usar.

Em vez de manter CPUs e armazenamento no seu datacenter, você aluga esses recursos pelo tempo necessário.

O provedor em nuvem é responsável por manter a infraestrutura subjacente.

### Por que devo migrar para a nuvem?

A nuvem ajuda você a avançar com mais rapidez e a inovar de maneiras que antes eram quase impossíveis.

- As equipes entregam novos recursos aos usuários em tempo recorde.
- Os usuários esperam uma experiência cada vez mais sofisticada e envolvente em seus dispositivos e software.

Hoje em dia, as equipes lançam recursos em lotes menores, o que geralmente resulta em lançamentos semanais ou diários. Algumas equipes geram atualizações de software o tempo todo, algumas vezes disponibilizando várias versões no mesmo dia.

Para alavancar seus serviços e oferecer experiências novas e inovadoras a seus usuários, a nuvem concede acesso sob demanda a:

- Um pool quase ilimitado de componentes brutos de rede, armazenamento e computação.
- Reconhecimento de fala e outros serviços cognitivos que ajudam a dar destaque ao seu aplicativo em meio a tantos outros.
- Serviços de análise que fornecem dados de telemetria por meio de software e dispositivos.

### O que é o Azure?

O Azure é um conjunto de serviços de nuvem, em constante expansão, que ajuda sua organização a superar os desafios empresariais atuais e se preparar para os desafios futuros. O Azure oferece a liberdade de criar, gerenciar e implantar aplicativos em uma enorme rede global usando suas ferramentas e estruturas favoritas.

O Azure fornece mais de 100 serviços que permitem que você faça de tudo, desde a execução de aplicativos existentes em máquinas virtuais até a exploração de novos paradigmas de software, como bots inteligentes e realidade misturada.

### O que é o portal do Azure?

O portal do Azure é um console unificado baseado na Web que fornece uma alternativa para as ferramentas de linha de comando. 

- Compile, gerencie e monitore tudo, desde aplicativos Web simples a implantações em nuvem complexas.
- Crie painéis personalizados para ter uma exibição organizada dos recursos.
- Configure opções de acessibilidade para ter a experiência ideal.
- O portal do Azure foi projetado para ter resiliência e disponibilidade contínua. 
- Ele mantém uma presença em todos os datacenters do Azure. 
    - Essa configuração torna o portal do Azure resiliente a falhas de datacenters individuais
    - Evita a lentidão da rede ao se manter perto dos usuários. 
- O portal do Azure é atualizado continuamente e não requer nenhum tempo de inatividade para atividades de manutenção.

### O que é o Azure Marketplace?

O Azure Marketplace ajuda a conectar usuários a parceiros da Microsoft, fornecedores independentes de software e startups que estão oferecendo soluções e serviços otimizados para execução no Azure. Os clientes do Azure Marketplace podem localizar, experimentar, comprar e provisionar aplicativos e serviços de centenas dos principais provedores de serviço. Todas as soluções e serviços são certificados para execução no Azure.

### Tour pelos serviços do Azure

![azure-services](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/intro-to-azure-fundamentals/media/azure-services-6c41a736.png)

Analise mais detalhadamente as categorias mais usadas:

- Computação
- Rede
- Armazenamento
- Móvel
- Bancos de dados
- Web
- Internet das coisas (IoT)
- Big Data
- IA
- DevOps

### Computação

| Nome do serviço | Função do serviço |
|-|-|
| Azure Virtual Machines | VMs (máquinas virtuais) do Windows ou do Linux hospedadas no Azure. |
| Azure Virtual Machine Scale Sets | Escala para VMs do Windows ou do Linux hospedadas no Azure.|
| Azure Kubernetes Service | Gerenciamento de clusters para VMs que executam serviços em contêineres. |
| Azure Service Fabric | Plataforma de sistemas distribuídos executada no Azure ou localmente. |
| Azure Batch | Serviço gerenciado para aplicativos de computação paralelos e de alto desempenho. |
| Azure Container Instances | Aplicativos em contêineres executados no Azure sem o provisionamento de servidores ou de VMs. |
| Azure Functions | Um serviço de computação sem servidor controlado por eventos. |

### Rede

Vincular recursos de computação e fornecer acesso a aplicativos são as principais funções da rede do Azure. A funcionalidade de rede do Azure inclui uma série de opções para conectar o mundo exterior aos serviços e recursos dos datacenters globais do Azure.

| Nome do serviço | Função do serviço |
|-|-|
| Azure Virtual Network | Conecta VMs a conexões VPN (rede virtual privada) de entrada. |
| Azure Load Balancer | Equilibra as conexões de entrada e saída para pontos de extremidade de serviço ou aplicativos. |
| Azure Application Gateway | Otimiza a entrega de farm de servidores de aplicativo, aumentando simultaneamente a segurança do aplicativo. |
| Azure VPN Gateway | Acessa as Redes Virtuais do Azure por meio de gateways de VPN de alto desempenho. |
| Azure DNS | Fornece respostas DNS extremamente rápidas e disponibilidade de domínio extremamente alta. |
| Azure Content Delivery Network | Distribui o conteúdo de alta largura de banda para clientes no mundo todo. |
| Azure DDoS Protection | Protege os aplicativos hospedados no Azure contra ataques de DDoS (negação de serviço distribuído). |
| Azure Traffic Manager | Distribui o tráfego de rede entre as regiões do Azure no mundo todo. |
| Azure ExpressRoute | Conecta-se ao Azure por meio de conexões seguras dedicadas de alta largura de banda. |
| Azure Network Watcher | Monitora e diagnostica problemas de rede usando a análise baseada em cenário. |
| Azure Firewall | Implementa um firewall de alta segurança e alta disponibilidade com escalabilidade ilimitada. |
| Azure Virtual WAN | Cria uma WAN (rede de longa distância) unificada que conecta sites remotos e locais. |

### Armazenamento

| Nome do serviço | Função do serviço |
|-|-|
| Azure Blob storage | Serviço de armazenamento para objetos muito grandes, como arquivos de vídeo ou bitmaps. |
| Azure File storage | Compartilhamentos de arquivos que podem ser acessados e gerenciados como um servidor de arquivos. |
| Azure Queue storage | Um armazenamento de dados para o enfileiramento de mensagens e a entrega confiável delas entre aplicativos. |
| Azure Table storage | O armazenamento de tabela é um serviço que armazena dados estruturados não relacionais (também conhecidos como dados NoSQL estruturados) na nuvem, fornecendo um repositório de chave/atributo com um design sem esquema. |

Todos esses serviços compartilham algumas características comuns:

- Duráveis e altamente disponíveis com redundância e replicação.
- Seguros por meio de criptografia automática e controle de acesso baseado em função.
- Escalonáveis com um armazenamento praticamente ilimitado.
- Gerenciados, cuidando da manutenção e de quaisquer eventuais problemas críticos para você.
- Acessíveis de qualquer lugar do mundo por HTTP ou HTTPS.

### Mobile

Com o Azure, os desenvolvedores podem criar serviços móveis de back-end para aplicativos iOS, Android e Windows de maneira rápida e fácil.

Outros recursos deste serviço incluem:

- Sincronização de dados offline.
- Conectividade para dados locais.
- Difusão de notificações por push.
- Dimensionamento automático para corresponder às necessidades de negócios.

### Bancos de dados

| Nome do serviço | Função do serviço |
|-|-|
| Azure Cosmos DB | Banco de dados distribuído globalmente que dá suporte a opções de NoSQL. |
| Azure SQL Database | Banco de dados relacional totalmente gerenciado com dimensionamento automático, inteligência integral e segurança robusta. |
| Azure Database for MySQL | Banco de dados relacional MySQL totalmente gerenciado e escalonável, com alta disponibilidade e segurança. |
| Azure Database for PostgreSQL | Banco de dados relacional PostgreSQL totalmente gerenciado e escalonável, com alta disponibilidade e segurança. |
| SQL Server on Azure Virtual Machines | Serviço que hospeda aplicativos empresariais do SQL Server na nuvem. |
| Azure Synapse Analytics | Data warehouse totalmente gerenciado com segurança integral em todos os níveis de escala sem custo adicional. |
| Azure Database Migration Service | Serviço que migra bancos de dados para a nuvem sem alterações no código do aplicativo. |
| Azure Cache for Redis | Caches de serviço totalmente gerenciados usados com frequência e dados estáticos para reduzir a latência de dados e de aplicativos. |
| Azure Database for MariaDB | Banco de dados relacional MariaDB totalmente gerenciado e escalonável, com alta disponibilidade e segurança. |

### Web

O Azure inclui suporte de primeira classe para criar e hospedar aplicativos Web e serviços Web baseados em HTTP.

| Nome do serviço | Função do serviço |
|-|-|
| Azure App Service | Crie rapidamente poderosos aplicativos de nuvem baseados na Web. |
| Azure Notification Hubs | Envie notificações por push para qualquer plataforma de qualquer back-end. |
| Azure API Management | Publique APIs para desenvolvedores, parceiros e funcionários de maneira segura e em escala. |
| Azure Cognitive Search | Implante esta pesquisa totalmente gerenciada como serviço. |
| Web Apps feature of Azure App Service | Crie e implante aplicativos Web críticos em escala. |
| Azure SignalR Service | Adicione funcionalidades da Web em tempo real com facilidade. |

### IoT

Essa capacidade dos dispositivos de coletar e depois retransmitir informações para análise de dados é conhecida como IoT.

| Nome do serviço | Função do serviço |
|-|-|
| IoT Central | Solução SaaS (software como serviço) de IoT global totalmente gerenciada que torna fácil conectar, monitorar e gerenciar os ativos de IoT em escala. |
| Azure IoT Hub | Hub de mensagens que fornece comunicações seguras e monitoramento entre milhões de dispositivos IoT. |
| IoT Edge | Serviço totalmente gerenciado que permite que os modelos de análise de dados sejam enviados por push diretamente aos dispositivos de IoT, possibilitando que esses dispositivos reajam rapidamente a alterações de estado sem a necessidade de consultar modelos de IA baseados em nuvem. |

### Big Data 

Tecnologias de cluster de software livre foram desenvolvidas para lidar com esses grandes conjuntos de dados. O Azure é compatível com uma ampla variedade de tecnologias e serviços para fornecer soluções de análises e Big Data.

| Nome do serviço | Função do serviço |
|-|-|
| Azure Synapse Analytics | Execute a análise em grande escala usando um data warehouse empresarial baseado em nuvem que aproveita o processamento paralelo massivo para executar consultas complexas rapidamente sobre petabytes de dados. |
| Azure HDInsight | Processe grandes quantidades de dados com clusters gerenciados de clusters Hadoop na nuvem. |
| Azure Databricks | Integre esse serviço de análise colaborativa com base no Apache Spark com outros serviços de Big Data do Azure. |

### IA

A IA, no contexto da computação em nuvem, baseia-se em uma ampla variedade de serviços, cujo núcleo é o aprendizado de máquina. O Machine Learning é uma técnica da ciência de dados que permite que os computadores usem os dados existentes para prever tendências, resultados e comportamentos futuros.

| Nome do serviço | Função do serviço |
|-|-|
| Azure Machine Learning Service | Ambiente baseado em nuvem você pode usar para desenvolver, treinar, testar, implantar, gerenciar e acompanhar modelos de aprendizado de máquina. Pode automaticamente gerar e ajustar um modelo para você. Permitirá que você inicie o treinamento no computador local e, posteriormente, escale horizontalmente para a nuvem. |
| Azure ML Studio | Workspace visual colaborativo em que você pode criar, testar e implantar soluções de machine learning usando módulos de manipulação de dados e algoritmos de machine learning predefinidos. |

Os serviços cognitivos são um conjunto de produtos fortemente relacionados. Você pode usar essas APIs predefinidas em seus aplicativos para resolver problemas complexos.

| Nome do serviço | Função do serviço |
|-|-|
| Vision | Use algoritmos de processamento de imagens para identificar, legendar, indexar e moderar de modo inteligente suas imagens e vídeos. |
| Speech | Converta áudio falado em texto, use voz para verificação ou adicione reconhecimento de locutor ao seu aplicativo. |
| Knowledge mapping | Mapeie dados e informações complexos para executar tarefas como recomendações inteligentes e pesquisa semântica. |
| Bing Search | Adicione APIs de Pesquisa do Bing a seus aplicativos e aproveite a capacidade de vasculhar bilhões de páginas da Web, imagens, vídeos e notícias com uma única chamada à API. |
| Natural Language processing | permita que seus aplicativos processem linguagem natural com scripts pré-criados, avalie sentimentos e aprenda a reconhecer o que os usuários desejam. |

### DevOps

O DevOps reúne pessoas, processos e tecnologias, automatizando a entrega de software para fornecer valor contínuo aos usuários. Com o Azure DevOps você pode criar, compilar e lançar pipelines que fornecem integração, entrega e implantação contínuas para seus aplicativos. Você pode integrar repositórios e testes de aplicativos, executar o monitoramento de aplicativo e trabalhar com artefatos de compilação. Você também pode trabalhar os itens e inseri-los em uma lista de pendências do produto para acompanhar, automatizar a implantação de infraestrutura e integrar uma série de ferramentas e serviços de terceiros, como Jenkins e Chef. 

| Nome do serviço | Função do serviço |
|-|-|
| Azure DevOps | Use ferramentas de colaboração de desenvolvimento, tais como pipelines de alto desempenho, repositórios Git privados gratuitos, quadros Kanban configuráveis e amplos testes de carga baseados em nuvem automatizados. Anteriormente conhecido como Visual Studio Team Services. |
| Azure DevTest Labs | Crie rapidamente ambientes Windows e Linux sob demanda para testar ou demonstrar aplicativos diretamente dos pipelines de implantação. |

### Introdução a contas do Azure

Para criar e usar os serviços do Azure, você precisa de uma assinatura do Azure. 

Depois de criar uma conta do Azure, você poderá criar assinaturas adicionais. Por exemplo: a empresa pode usar apenas uma conta do Azure para os negócios, com assinaturas separadas para os departamentos de desenvolvimento, marketing e vendas. 

![scope-levels](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/intro-to-azure-fundamentals/media/scope-levels-12669ee1.png)

A conta gratuita do Azure inclui:

- Acesso gratuito a produtos populares do Azure por 12 meses.
- Um crédito a ser gasto nos primeiros 30 dias.
- Acesso a mais de 25 produtos que são sempre gratuitos.


### O que é a conta de estudante gratuita do Azure?

A oferta da conta de estudante gratuita do Azure inclui:

- Acesso gratuito a determinados produtos do Azure por 12 meses.
- Um crédito a ser usado nos primeiros 12 meses.
- Acesso gratuito a determinadas ferramentas para desenvolvedores de software.

A conta de estudante gratuita do Azure é uma oferta para estudantes que oferece US$ 100 de crédito e ferramentas para desenvolvedores gratuitas. Além disso, você pode se inscrever sem um cartão de crédito.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

## 🔸 <a name="Discutir_conceitos_fundamentais_do_Azure"></a>Discutir conceitos fundamentais do Azure

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

## 🔸 <a name="Descrever_os_principais_componentes_da_arquitetura_do_Azure"></a>Descrever os principais componentes da arquitetura do Azure

### Visão geral de assinaturas, grupos de gerenciamento e recursos do Azure

- **Resource**: recursos são instâncias de serviços que você cria, como máquinas virtuais, armazenamento ou bancos de dados SQL.

- **Resource Group**: os recursos são combinados em grupos de recursos, que atuam como um contêiner lógico no qual os recursos do Azure, como aplicativos Web, bancos de dados e contas de armazenamento, são implantados e gerenciados.

- **Subscriptions**: uma assinatura agrupa contas de usuário e os recursos que foram criados por elas. Para cada assinatura, há limites ou cotas na quantidade de recursos que você pode criar e usar. As organizações podem usar assinaturas para gerenciar os custos e os recursos criados por usuários, equipes ou projetos.

- **Management groups**: esses grupos ajudam a gerenciar o acesso, a política e a conformidade para várias assinaturas. Todas as assinaturas em um grupo de gerenciamento herdam automaticamente as condições aplicadas ao grupo de gerenciamento.

### Regiões do Azure, zonas de disponibilidade e pares de regiões

Os recursos são criados em regiões, que são diferentes localizações geográficas no mundo inteiro que contêm datacenters do Azure.

### Regiões do Azure

Uma região é uma área geográfica do planeta que contém pelo menos um, mas possivelmente vários data centers próximos e conectados a uma rede de baixa latência. 

Essas regiões dão flexibilidade para aproximar os aplicativos dos usuários, não importa onde estejam. As regiões globais proporcionam maior escalabilidade e redundância. Elas também preservam a residência de dados de seus serviços.

### Regiões especiais do Azure

Para fins de conformidade ou jurídicos.

- **US DoD Central, US Gov – Virgínia, US Gov Iowa, entre outros**: essas regiões são instâncias lógicas e físicas do Azure isoladas da rede, destinadas a parceiros e órgãos do governo dos EUA. Esses datacenters são operados por cidadãos selecionados dos EUA e incluem certificações de conformidade adicionais.

- **Leste da China, Norte da China, entre outros**: essas regiões estão disponíveis por meio de uma parceria exclusiva entre a Microsoft e a 21Vianet, segundo a qual a Microsoft não mantém diretamente os data centers.

### Zonas de disponibilidade do Azure

Zonas de disponibilidade são datacenters separados fisicamente dentro de uma região do Azure. Cada zona de disponibilidade é composta de um ou mais datacenters equipados com energia, resfriamento e rede independentes. 

Uma zona de disponibilidade é configurada para ser um limite de isolamento. Se uma zona ficar inativa, as outras continuarão funcionando. 

Zonas de disponibilidade são conectadas por meio de redes de fibra óptica privadas de alta velocidade.

![availability-zones](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-architecture-fundamentals/media/availability-zones-5c3c490c.png)

> Nem todas as regiões têm suporte para zonas de disponibilidade.

Você pode usar as zonas de disponibilidade para executar aplicativos críticos e incorporar alta disponibilidade à arquitetura do aplicativo, colocalizando seus recursos de computação, armazenamento, rede e dados em uma zona e replicando em outras zonas. Tenha em mente que pode haver um custo para duplicar seus serviços e transferir dados entre zonas.

As zonas de disponibilidade são destinadas, principalmente, a VMs, discos gerenciados, balanceadores de carga e bancos de dados SQL. As seguintes categorias de serviços do Azure dão suporte a zonas de disponibilidade:

- **Serviços em zonas (Zonal services)**: você fixa o recurso a uma zona específica (por exemplo, VMs, discos gerenciados, endereços IP).
- **Serviços com redundância de zona (Zone-redundant services)**: a plataforma replica automaticamente entre zonas (por exemplo, armazenamento com redundância de zona, Banco de Dados SQL).
- **Serviços não regionais (Non-regional services)**: os serviços estão sempre disponíveis em geografias do Azure e são resilientes a interrupções em toda a zona, bem como a interrupções em toda a região.

### Pares de regiões do Azure

Cada região do Azure é sempre emparelhada com outra região na mesma área geográfica (como EUA, Europa ou Ásia) a pelo menos 300 milhas (cerca de 480 km) de distância. Essa abordagem permite a replicação de recursos, como o armazenamento de VM, em uma geografia, o que ajuda a reduzir a probabilidade de interrupções devido a eventos como desastres naturais, conflitos civis, quedas de energia ou interrupções de rede física afetarem as duas regiões ao mesmo tempo. Se uma região em um par de regiões fosse afetada por um desastre natural, por exemplo, os serviços fariam failover automaticamente para a outra região desse par.

Como o par de regiões está diretamente conectado e suficientemente afastado para ser isolado contra desastres regionais, você pode usá-lo para fornecer redundância de dados e serviços confiáveis. Alguns serviços oferecem armazenamento com redundância geográfica automática usando pares de regiões.

#### Vantagens adicionais dos pares de regiões:

- Se ocorrer uma interrupção ampla do Azure, uma região de cada par será priorizada para que pelo menos uma seja restaurada o quanto antes para os aplicativos hospedados nesse par de regiões.
- As atualizações planejadas do Azure são distribuídas para regiões emparelhadas uma por vez, de modo a minimizar o tempo de inatividade e o risco de interrupção dos aplicativos.
- Os dados continuam residindo na mesma geografia que seu par (com exceção do Sul do Brasil) para fins de jurisdição do imposto e aplicação da lei.

> Ter um conjunto de datacenters distribuído em larga escala permite que o Azure forneça uma garantia de alta disponibilidade.

### Recursos do Azure e Azure Resource Manager

- **Recurso**: um item gerenciável disponibilizado por meio do Azure. VMs (máquinas virtuais), contas de armazenamento, aplicativos Web, bancos de dados e redes virtuais são exemplos de recursos.

- **Grupo de recursos**: um contêiner que armazena os recursos relacionados de uma solução do Azure. O grupo de recursos inclui os recursos que você deseja gerenciar como um grupo. Você decide quais recursos pertencem a um grupo de recursos com base no que faz mais sentido para sua organização.

### Grupos de recursos do Azure

- Um grupo de recursos é um contêiner lógico para recursos implantados no Azure. Esses recursos são tudo o que você cria em uma assinatura do Azure, como VMs, instâncias do Gateway de Aplicativo do Azure e instâncias do Azure Cosmos DB. 
- Todos os recursos precisam estar em um grupo, e um recurso pode ser um membro de apenas um grupo de recursos. 
- Muitos recursos podem ser movidos entre grupos de recursos com alguns serviços que têm limitações ou requisitos específicos de movimentação. 
- Os grupos de recursos não podem ser aninhados. 
- Para que qualquer recurso possa ser provisionado, é necessário colocá-lo em um grupo de recursos.

### Agrupamento lógico

Os grupos de recursos existem para ajudar a gerenciar e organizar seus recursos do Azure. 

### Ciclo de vida

Se você excluir um grupo de recursos, todos os recursos contidos nele também serão excluídos. Organizar recursos por ciclo de vida pode ser útil em ambientes de não produção, em que você pode realizar um experimento e, depois, descartá-lo. Os grupos de recursos facilitam a remoção de um conjunto de recursos de uma só vez.

### Autorização

Grupos de recursos também são um escopo para a aplicação de permissões de RBAC (Role-based Access Control). Ao aplicar permissões de RBAC a um grupo de recursos, você pode facilitar a administração e limitar o acesso, a fim de permitir apenas o que é necessário.

### Azure Resource Manager

O Azure Resource Manager é o serviço de implantação e gerenciamento do Azure. Ele fornece uma camada de gerenciamento que lhe permite criar, atualizar e excluir recursos em sua conta do Azure. Você usa recursos de gerenciamento como controle de acesso, bloqueios e marcas para proteger e organizar seus recursos após a implantação.

Quando um usuário envia uma solicitação de ferramentas, APIs ou SDKs do Azure, o Resource Manager recebe a solicitação. Ele autentica e autoriza a solicitação. O Resource Manager envia a solicitação para o serviço do Azure, que executa a ação solicitada. Como todas as solicitações são manipuladas por meio da mesma API, você verá funcionalidades e resultados uniformes em todas as diferentes ferramentas.

![consistent-management-layer](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-architecture-fundamentals/media/consistent-management-layer-feef9259.png)

Todos os recursos disponíveis no portal do Azure também estão disponíveis por meio do PowerShell, da CLI do Azure, das APIs REST e dos SDKs de cliente. 

### Os benefícios de usar o Gerenciador de Recursos

Com o Resource Manager, você pode:

- Gerenciar sua infraestrutura por meio de modelos declarativos em vez de scripts. Um modelo do Resource Manager é um arquivo JSON que define o que você deseja implantar no Azure.
- Implantar, gerenciar e monitorar todos os recursos da sua solução como um grupo em vez de tratá-los individualmente.
- Reimplantar a solução durante o ciclo de vida de desenvolvimento e ter confiança de que os recursos serão implantados em um estado consistente.
- Definir as dependências entre os recursos para que eles sejam implantados na ordem correta.
- Aplicar o controle de acesso a todos os serviços porque o RBAC é integrado nativamente à plataforma de gerenciamento.
- Aplicar marcas aos recursos para organizar de modo lógico todos os recursos em sua assinatura.
- Esclarecer a cobrança da organização exibindo os custos de um grupo de recursos que compartilham a mesma marca.

### Assinaturas e Grupos de Gerenciamento do Azure

### Assinaturas do Azure

A utilização do Azure exige uma Assinatura do Azure. Uma assinatura fornece a você acesso autenticado e autorizado a serviços e produtos do Azure. Ela também permite que você provisione recursos. Uma assinatura do Azure é uma unidade lógica de serviços do Azure que se vincula a uma conta do Azure, que é uma identidade no Azure AD (Azure Active Directory) ou em um diretório no qual o Azure AD confia.

Uma conta pode ter uma ou várias assinaturas com diferentes modelos de cobrança e às quais você aplica diferentes políticas de gerenciamento de acesso. Você pode usar as assinaturas do Azure para definir limites em relação a produtos, serviços e recursos do Azure. Você pode usar dois tipos de limites de assinatura:

- **Limite de cobrança**: Esse tipo de assinatura determina como uma conta do Azure é cobrada pelo uso do Azure. Você pode criar várias assinaturas para atender a diferentes tipos de requisitos de cobrança. O Azure gera relatórios de cobrança e faturas separados para cada assinatura, para que você possa organizar e gerenciar os custos.

- **Limite de controle de acesso**: O Azure aplica políticas de gerenciamento de acesso no nível da assinatura, e você pode criar assinaturas separadas para refletir diferentes estruturas organizacionais. Um exemplo disso é que, em um negócio, você tem diferentes departamentos aos quais aplica políticas de assinatura do Azure distintas. Esse modelo de cobrança permite gerenciar e controlar o acesso aos recursos que os usuários provisionam com assinaturas específicas.

### Criar assinaturas adicionais do Azure

Talvez você queira criar assinaturas adicionais para fins de gerenciamento de recursos ou orçamento. Por exemplo, é possível criar assinaturas adicionais para separar:

- **Ambientes**: Ao gerenciar seus recursos, você pode optar por criar assinaturas adicionais a fim de configurar ambientes separados para desenvolvimento e teste, segurança ou para isolar dados por motivos de conformidade. Esse design é particularmente útil porque o controle de acesso ao recurso ocorre no nível da assinatura.

- **Estruturas organizacionais**: É possível criar assinaturas para refletir diferentes estruturas organizacionais. Você poderia, por exemplo, limitar a equipe a recursos de baixo custo, enquanto permite uma gama completa para o departamento de TI. Esse design permite gerenciar e controlar o acesso aos recursos que os usuários provisionam em cada assinatura.

- **Cobrança**: Talvez você também queira criar assinaturas adicionais para fins de cobrança. Como os custos são agregados primeiro no nível da assinatura, talvez você queira criar assinaturas para gerenciar e controlar os custos com base em suas necessidades. Por exemplo, talvez você queira criar uma assinatura para as cargas de trabalho de produção e outra para as cargas de trabalho de desenvolvimento e teste.

Talvez você também precise de assinaturas adicionais devido a:

**Limites da assinatura**: As assinaturas estão associadas a algumas limitações rigorosas. Por exemplo, o número máximo de circuitos do Azure ExpressRoute por assinatura é 10. Esses limites devem ser considerados enquanto você cria assinaturas em sua conta. Se for preciso ultrapassar esses limites em cenários específicos, talvez seja necessário ter assinaturas adicionais.

## Personalizar a cobrança para atender às suas necessidades

Se você tiver várias assinaturas, poderá organizá-las em seções de fatura. Cada seção de fatura é um item de linha na fatura que mostra os encargos incorridos nesse mês. Por exemplo, você pode precisar de uma única fatura para sua organização, mas deseja organizar os encargos por departamento, equipe ou projeto.

Dependendo de suas necessidades, é possível configurar várias faturas dentro da mesma conta de cobrança. Para fazer isso, crie perfis de cobrança adicionais. Cada perfil de cobrança tem sua própria fatura mensal e formas de pagamento.

O diagrama a seguir mostra uma visão geral de como a cobrança é estruturada. 


![billing-structure-overview](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-architecture-fundamentals/media/billing-structure-overview-2c81a8ad.png)

### Grupos de gerenciamento do Azure

Se a organização tiver muitas assinaturas, talvez você precise de uma forma de gerenciar o acesso, as políticas e a conformidade com eficiência para essas assinaturas. 

Os grupos de gerenciamento do Azure fornecem um nível de escopo acima das assinaturas. 

Você organiza as assinaturas em contêineres chamados grupos de gerenciamento e aplica suas condições de governança a esses grupos. 

Todas as assinaturas dentro de um grupo de gerenciamento herdam automaticamente as condições aplicadas ao grupo de gerenciamento. 

Os grupos de gerenciamento fornecem gerenciamento de nível empresarial em larga escala, independentemente do tipo de assinaturas que você possa ter. Todas as assinaturas dentro de um grupo de gerenciamento devem confiar no mesmo locatário do Azure AD.

Por exemplo, você pode aplicar políticas a um grupo de gerenciamento para limitar as regiões disponíveis para criação de VMs. Essa política seria aplicada a todos os grupos de gerenciamento, assinaturas e recursos nesse grupo de gerenciamento, permitindo que as VMs fossem criadas nessa região.

### Hierarquia de grupos de gerenciamento e assinaturas

É possível compilar uma estrutura flexível de grupos de gerenciamento e assinaturas para organizar seus recursos em uma hierarquia para políticas unificadas e gerenciamento de acesso. O diagrama a seguir mostra um exemplo de criação de uma hierarquia de governança usando grupos de gerenciamento.

![management-groups-and-subscriptions](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-architecture-fundamentals/media/management-groups-and-subscriptions-bba71896.png)

Você pode criar uma hierarquia que aplica uma política. Por exemplo, você pode limitar os locais de VM à região Oeste dos EUA em um grupo chamado Produção. Essa política herdará todas as assinaturas do Contrato Enterprise que são descendentes desse grupo de gerenciamento e será aplicada a todas as VMs nessas assinaturas. Essa política de segurança não pode ser alterada pelo proprietário da assinatura nem do recurso, o que permite uma governança aprimorada.

Outro cenário em que você usaria grupos de gerenciamento é fornecer acesso de usuário a várias assinaturas. Ao mover várias assinaturas nesse grupo de gerenciamento, você poderá criar uma atribuição de RBAC (controle de acesso baseado em função) no grupo de gerenciamento, que herdará esse acesso a todas as assinaturas. Uma atribuição no grupo de gerenciamento pode permitir que os usuários tenham acesso a tudo o que precisam em vez de fazer script de atribuições de RBAC em várias assinaturas.

### Fatos importantes sobre os grupos de gerenciamento

- 10.000 grupos de gerenciamento podem ter suporte em um único diretório.
- Uma árvore do grupo de gerenciamento pode dar suporte a até seis níveis de profundidade. Esse limite não inclui o nível raiz nem o nível da assinatura.
- Cada grupo de gerenciamento e assinatura podem dar suporte a somente um pai.
- Cada grupo de gerenciamento pode ter vários elementos filhos.
- Todas as assinaturas e todos os grupos de gerenciamento estão em uma única hierarquia em cada diretório.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

# ☁️ <a name="parte2"></a>Parte 2: Princípios básicos do Microsoft Azure: Descrever os principais serviços do Azure

Depois de concluir este roteiro de aprendizagem, você poderá:

- Entender a variedade de serviços disponíveis no Azure, incluindo computação, rede, armazenamento e banco de dados
- Identificar serviços de virtualização, como Máquinas Virtuais do Azure, Instâncias de Contêiner do Azure, Serviço de Kubernetes do Azure e Área de Trabalho Virtual do Azure
- Comparar os serviços de banco de dados do Azure, como o Azure Cosmos DB, o SQL do Azure, o Banco de Dados do Azure para MySQL, o Banco de Dados do Azure para PostgreSQL e os serviços de Big Data e análise do Azure
- Examinar recursos de rede do Azure, como Redes Virtuais, Gateways de VPN e o ExpressRoute do Azure
- Resumir os serviços de armazenamento do Azure, como Armazenamento de Blobs do Azure, Armazenamento em Disco do Azure e Armazenamento de Arquivos do Azure

1. [Explorar os serviços de computação do Azure](#Explorar_os_serviços_de_computação_do_Azure)
2. [Explorar os serviços de rede do Azure](#Explorar_os_serviços_de_rede_do_Azure)
3. [Explorar os serviços do Armazenamento do Azure](#Explorar_os_serviços_do_Armazenamento_do_Azure)
4. [Explorar os serviços de banco de dados e análise do Azure](#Explorar_os_serviços_de_banco_de_dados_e_análise_do_Azure)

## 🔸 <a name="Explorar_os_serviços_de_computação_do_Azure"></a>Explorar os serviços de computação do Azure

Depois de concluir este módulo, você poderá descrever os benefícios e o uso destes serviços:

- Máquinas Virtuais do Azure
- Serviço de aplicativo do Azure
- Instâncias de Contêiner do Azure
- Serviço de Kubernetes do Azure
- Azure Functions
- Área de Trabalho Virtual do Azure

## Visão geral dos serviços de computação do Azure

A computação do Azure é um serviço de computação sob demanda para execução de aplicativos baseados em nuvem. Ela fornece recursos de computação, como discos, processadores, memória, rede e sistemas operacionais. Os recursos estão disponíveis sob demanda e normalmente podem ser disponibilizados em minutos ou até mesmo segundos. Você só paga pelos recursos utilizados e apenas pelo tempo que utilizar.

### Virtual machines

Máquinas virtuais são emulações de software de computadores físicos. Elas incluem um processador virtual, memória, armazenamento e recursos de rede. As VMs hospedam um sistema operacional, e você pode instalar e executar o software como se fosse um computador físico. Utilize um cliente da Área de Trabalho Remota para usar e controlar a VM como se estivesse na frente dela.

As Máquinas Virtuais fornecem IaaS (infraestrutura como serviço) e podem ser usadas de maneiras diferentes. Quando você precisa ter controle total sobre um sistema operacional e ambiente, as VMs são a opção ideal. 

### Virtual machine scale sets

são um recurso de computação do Azure que você pode usar para implantar e gerenciar um conjunto de VMs idênticas. Com todas as VMs configuradas da mesma forma, os conjuntos de dimensionamento de máquinas virtuais têm a finalidade de dar suporte ao verdadeiro dimensionamento automático. Nenhum provisionamento prévio das VMs é necessário. Por esse motivo, é mais fácil criar serviços de grande escala direcionados a grandes cargas de trabalho de computação, Big Data e em contêineres. Conforme a demanda aumenta, mais instâncias de VM podem ser adicionadas. Conforme a demanda diminui, instâncias de VM podem ser removidas. O processo pode ser manual, automatizado ou uma combinação de ambos.

### Contêineres e Kubernetes

As Instâncias de Contêiner e o Serviço de Kubernetes do Azure são recursos de Computação do Azure que você pode usar para implantar e gerenciar contêineres. Contêineres são ambientes de aplicativos leves e virtualizados. Eles foram projetados para serem criados rapidamente, escalados horizontalmente e interrompidos dinamicamente. Você pode executar várias instâncias de um aplicativo em contêineres em um computador host.

### App Service

Com o Serviço de Aplicativo do Azure, você pode criar, implantar e dimensionar rapidamente aplicativos Web, móveis e de API de nível empresarial executados em qualquer plataforma. Você pode atender a requisitos rigorosos de desempenho, escalabilidade, segurança e conformidade ao usar uma plataforma totalmente gerenciada para executar a manutenção de infraestrutura. O Serviço de Aplicativo é uma oferta de PaaS (plataforma como serviço).

### Functions

As funções são ideais quando você está preocupado apenas com o código que executa o serviço, e não com a plataforma ou a infraestrutura subjacente. Elas costumam ser usadas quando você precisa executar um trabalho em resposta a um evento (geralmente por meio de uma solicitação REST), um temporizador ou uma mensagem de outro serviço do Azure, e quando esse trabalho pode ser concluído dentro de segundos.

## Decidir quando usar Máquinas Virtuais do Azure

Como em um computador físico, você pode personalizar todos os programas de software em execução na VM. As VMs são uma opção ideal quando você precisa de:

- Controle total sobre o SO (sistema operacional).
- Capacidade para executar um software personalizado.
- Usar configurações personalizadas de hospedagem.

Uma VM do Azure oferece a flexibilidade da virtualização sem a necessidade de comprar e manter o hardware físico que a executa. Você ainda precisa configurar, atualizar e manter o software executado na VM.

Uma imagem é um modelo usado para criar uma VM. Esses modelos já incluem um sistema operacional e, muitas vezes, outros programas de software, como ferramentas de desenvolvimento ou ambientes de hospedagem na Web.

### Exemplos de quando usar VMs

- **Durante o teste e o desenvolvimento**. As VMs fornecem uma maneira rápida e fácil de criar diferentes configurações de sistema operacional e de aplicativo. A equipe de teste e desenvolvimento pode excluir facilmente as VMs quando não precisarem mais delas.

- **Ao executar aplicativos na nuvem**. A capacidade de executar determinados aplicativos na nuvem pública, em vez de criar uma infraestrutura tradicional para executá-los, pode trazer benefícios econômicos substanciais. Por exemplo, um aplicativo pode precisar lidar com flutuações na demanda. Desligar VMs quando elas não são necessárias ou iniciá-las rapidamente para atender a um aumento repentino na demanda significa que você paga apenas pelos recursos que usa.

- **Ao estender seu datacenter para a nuvem**. Uma organização pode estender os recursos de sua própria rede local criando uma rede virtual no Azure e adicionando VMs a ela. Aplicativos como o SharePoint podem, então, ser executados em uma VM do Azure em vez de localmente. É mais fácil ou menos caro implantar dessa forma do que em um ambiente local.

- **Durante a recuperação de desastre**. Assim como acontece com a execução de determinados tipos de aplicativos na nuvem e com a extensão de uma rede local para a nuvem, você pode conseguir economias significativas usando uma abordagem baseada em IaaS para a recuperação de desastre. Se um datacenter primário falhar, você poderá criar VMs em execução no Azure para executar seus aplicativos críticos e desligá-los quando o datacenter primário ficar operacional novamente.

### Migrar para a nuvem com VMs

As VMs também são uma excelente opção quando você migra de um servidor físico para a nuvem (também conhecido como lift-and-shift). Você pode criar uma imagem do servidor físico e hospedá-la em uma VM com poucas ou nenhuma alteração. Assim como um servidor físico local, você deve manter a VM. Atualize o sistema operacional instalado e o software em que ele é executado.

### Dimensionar VMs no Azure

Você pode executar VMs únicas para teste, desenvolvimento ou para tarefas secundárias. Ou pode agrupar VMs para fornecer alta disponibilidade, escalabilidade e redundância. Independentemente dos seus requisitos de tempo de atividade, o Azure conta com diversos recursos para atendê-los. Esses recursos incluem:

- Virtual machine scale sets
- Azure Batch

### O que são os Virtual machine scale sets?

- Permitem criar e gerenciar um grupo de VMs idênticas e com balanceamento de carga. 
- Permitem que você gerencie, configure e atualize centralmente um grande número de VMs em minutos para fornecer aplicativos de alta disponibilidade. O número de instâncias de VM pode aumentar ou diminuir automaticamente em resposta à demanda ou a um agendamento definido. 

### O que é o Azure Batch?

O Azure Batch, trabalhos em lotes paralelos e de HPC (computação de alto desempenho) de grande escala com a capacidade de dimensionar dezenas, centenas ou milhares de VMs.

Quando você estiver pronto para executar um trabalho, o Batch fará o seguinte:

- Iniciar um pool de VMs de computação para você.
- Instalar aplicativos e dados de preparo.
- Executar trabalhos com todas as tarefas que você tiver.
- Identificar falhas.
- Colocar o trabalho em filas.
- Reduzir verticalmente o pool conforme o trabalho for concluído.
- Pode haver situações em que você precise de potência de computação bruta ou de potência de computação no nível de supercomputador. O Azure fornece esses recursos.

## Decidir quando usar o Azure App Service

O Serviço de Aplicativo permite que você crie e hospede aplicativos Web, trabalhos em segundo plano, back-ends de dispositivos móveis e APIs RESTful na linguagem de programação de sua escolha sem gerenciar a infraestrutura. Ele oferece dimensionamento automático e alta disponibilidade. O Serviço de Aplicativo é compatível com Windows e Linux e permite implantações automatizadas do GitHub, Azure DevOps ou qualquer repositório Git para dar suporte a um modelo de deploy contínuo.

Esse ambiente de PaaS (plataforma como serviço) permite que você se concentre no site e na lógica da API, enquanto o Azure manipula a infraestrutura para executar e dimensionar seus aplicativos Web.

### Custos do App Service

Você paga pelos recursos de Computação do Azure que o seu aplicativo usa ao processar solicitações com base no plano do App Service que você escolher. O plano do App Service determina a quantidade de hardware dedicada ao host. Por exemplo, o plano determina se ele tem hardware dedicado ou compartilhado e a quantidade de memória reservada para ele. Há até mesmo uma camada gratuita que você pode usar para hospedar sites pequenos e de baixo tráfego.

### Tipos de serviços de aplicativos

- Aplicativos Web
- Aplicativos de API
- WebJobs
- Aplicativos móveis

O Serviço de Aplicativo cuida da maioria das decisões de infraestrutura com as quais você lida ao hospedar aplicativos acessíveis pela Web:

- A implantação e o gerenciamento são integrados à plataforma.
- Pontos de extremidade podem ser protegidos.
- Sites podem ser dimensionados rapidamente para lidar com cargas de alto tráfego.
- O balanceamento de carga interno e o gerenciador de tráfego fornecem alta disponibilidade.

Todos esses estilos de aplicativos são hospedados na mesma infraestrutura e compartilham esses benefícios. Essa flexibilidade torna o Serviço de Aplicativo a escolha ideal para hospedar aplicativos voltados para a Web.

### Aplicativos Web

Da mesma forma como se hospeda um site, você pode criar APIs Web baseadas em REST usando a linguagem e a estrutura que você quiser. Receba o suporte completo do Swagger e a capacidade de empacotar e publicar sua API no Azure Marketplace. Os aplicativos produzidos podem ser consumidos em qualquer cliente baseado em HTTP ou HTTPS.

### WebJobs

Você pode usar o recurso do WebJobs para executar um script (.cmd, .bat, PowerShell ou Bash) ou um programa (.exe, Java, PHP, Python ou Node.js) no mesmo contexto de um aplicativo Web, aplicativo de API ou aplicativo móvel. Eles também podem ser agendados ou executados por um gatilho. O WebJobs geralmente é usado para executar tarefas em segundo plano como parte da lógica do aplicativo.

### Aplicativos móveis

Use o recurso Aplicativos Móveis do Serviço de Aplicativo para criar rapidamente um back-end para aplicativos iOS e Android. Com apenas alguns cliques no portal do Azure, você pode:

- Armazenar dados de aplicativo móvel em um Banco de Dados SQL baseado em nuvem.
- Autenticar os clientes em relação a provedores sociais comuns, como MSA, Google, Twitter e Facebook.
- Enviar notificações por push.
- Executar a lógica personalizada de back-end no C# ou Node.js.

No lado do aplicativo móvel, há suporte do SDK para aplicativos nativos para iOS, Android, Xamarin e React.

## Decidir quando usar as Instâncias de Contêiner do Azure ou o Serviço de Kubernetes do Azure

Embora as máquinas virtuais sejam uma excelente maneira de reduzir os custos em comparação com os investimentos necessários para o hardware físico, elas ainda estão limitadas a um sistema operacional por máquina virtual. Se você quer executar várias instâncias de um aplicativo em um só computador host, os contêineres são uma ótima opção.

### O que são contêineres?

Contêineres são um ambiente de virtualização. Assim como a execução de várias máquinas virtuais em um só host físico, você pode executar vários contêineres em apenas um host físico ou virtual. 

Diferentemente das máquinas virtuais, você não gerencia o sistema operacional para um contêiner. As máquinas virtuais parecem ser uma instância de um sistema operacional ao qual você pode se conectar e que você pode gerenciar, mas os contêineres são leves e projetados para serem criados, dimensionados e interrompidos dinamicamente. 

Embora seja possível criar e implantar máquinas virtuais à medida que a demanda do aplicativo aumenta, os contêineres são projetados para permitir que você responda às alterações sob demanda. Com contêineres, você pode reiniciar rapidamente no caso de uma falha ou de uma interrupção de hardware. 

### Gerenciar contêineres

Os contêineres são gerenciados por meio de um orquestrador de contêineres, que pode iniciar, interromper e dimensionar as instâncias do aplicativo conforme necessário. Há duas maneiras de gerenciar contêineres baseados no Docker e na Microsoft no Azure: Instâncias de Contêiner do Azure e AKS (Serviço de Kubernetes do Azure).

### Instâncias de Contêiner do Azure

As Instâncias de Contêiner do Azure oferecem a maneira mais rápida e simples de executar um contêiner no Azure, sem a necessidade de gerenciar máquinas virtuais nem adotar serviços adicionais. Trata-se de uma oferta de PaaS (plataforma como serviço) que permite que você carregue contêineres, que ela executará para você.

### Serviço de Kubernetes do Azure

A tarefa de automatizar, gerenciar e interagir com um grande número de contêineres é conhecida como orquestração. O Serviço de Kubernetes do Azure é um serviço de orquestração completa para contêineres com arquiteturas distribuídas e grandes volumes de contêineres.

### Usar contêineres em suas soluções

Contêineres geralmente são usados para criar soluções que utilizam uma arquitetura de microsserviço. Essa arquitetura é onde você divide as soluções em partes menores e independentes. Por exemplo, você pode dividir um site em um contêiner que hospeda o front-end, outro que hospeda o back-end e um terceiro para o armazenamento. Essa divisão permite separar as partes do aplicativo em seções lógicas que podem ser mantidas, dimensionadas ou atualizadas de forma independente.

Imagine que o back-end do site atingiu a capacidade, mas o front-end e o armazenamento não estão sob pressão. Você pode:

- Dimensionar o back-end separadamente para aprimorar o desempenho.
- Optar por usar outro serviço de armazenamento.
- Substituir o contêiner de armazenamento sem afetar o restante do aplicativo.

## Decidir quando usar o Azure Functions

- A computação sem servidor é a abstração de servidores, infraestrutura e sistemas operacionais. 
- Com a computação sem servidor, o Azure cuida do gerenciamento da infraestrutura de servidor e da alocação e desalocação de recursos com base na demanda. 
- Você não precisa se preocupar com a infraestrutura. A colocação em escala e o desempenho são manipulados automaticamente. 
- Você é cobrado apenas pelos recursos exatos que usa. Não é necessário ter capacidade reserva.

A computação sem servidor inclui a abstração de servidores, uma escala controlada por eventos e uma microcobrança:

- **Abstraction of servers**: 
    - a computação sem servidor abstrai os servidores em que você executa. 
    - Você nunca reserva instâncias de servidor explicitamente. A plataforma gerencia isso para você. 
    - A execução de cada função pode ser executada em uma instância de computação diferente. Esse contexto de execução é transparente para o código. 
    - Com a arquitetura sem servidor, você implanta seu código, que, por sua vez, é executado com alta disponibilidade.

- **Event-driven scale**: 
    - A computação sem servidor é uma opção excelente para cargas de trabalho que respondem a eventos de entrada. Os eventos incluem gatilhos por:
        - Temporizadores, por exemplo, se uma função precisar ser executada todos os dias às 10h00 UTC.
        - HTTP, por exemplo, em cenários com API e webhook.
        - Filas, por exemplo, com o processamento em ordem.
        - E muito mais.

Em vez de escrever um aplicativo inteiro, o desenvolvedor cria uma função, que contém o código e os metadados sobre seus gatilhos e associações. 

A plataforma agenda automaticamente a função para execução e dimensiona o número de instâncias de computação com base na taxa de eventos de entrada. 

Gatilhos definem como uma função é invocada. As associações fornecem uma forma declarativa de conectar-se a serviços de dentro do código.

- **Microcobrança**: 
    - a computação tradicional cobra por um bloco de tempo, por exemplo, com o pagamento de uma taxa mensal ou anual pela hospedagem de sites. Esse método de cobrança é conveniente, mas nem sempre é econômico. Mesmo que o site de um cliente receba apenas uma visita por dia, ele ainda pagará pela disponibilidade de um dia inteiro. 
    - Com a computação sem servidor, ele paga apenas pelo tempo em que seu código é executado. Se nenhuma execução de função ativa ocorrer, ele não será cobrado. Por exemplo, se o código for executado uma vez por dia por dois minutos, ele será cobrado por uma execução e dois minutos de tempo de computação.

### Computação sem servidor no Azure

O Azure tem duas implementações de computação sem servidor:

- **Azure Functions**: o Functions pode executar o código praticamente em qualquer linguagem de programação moderna.
- **Azure Logic Apps**: os aplicativos lógicos foram desenvolvidos em um designer baseado na Web e podem executar a lógica disparada pelos serviços do Azure sem escrever nenhum código.

### Azure Functions

O Azure Functions é ideal para você caso esteja preocupado apenas com o código do serviço. As funções costumam ser usadas quando você precisa executar um trabalho em resposta a um evento (geralmente por meio de uma solicitação REST), um temporizador ou uma mensagem de outro serviço do Azure.

As funções são dimensionadas automaticamente com base na demanda; assim sendo, trata-se de uma boa opção quando a demanda é variável. Por exemplo, você pode receber mensagens de uma solução de IoT (Internet das Coisas) usada para monitorar uma frota de veículos de entrega. Provavelmente, a maioria dos dados é recebida durante o horário comercial.

Usando uma abordagem baseada em máquina virtual, você incorreria em custos mesmo quando a máquina virtual estivesse ociosa. Com funções, o Azure executa o código quando este é disparado e desaloca os recursos automaticamente quando a função é concluída. Neste modelo, você só é cobrado pelo tempo de CPU usado durante a execução da função.

As funções podem ser sem estado (stateless) ou com estado (stateful). 
- Quando são sem estado (o padrão), elas se comportam como se fossem reiniciadas sempre que respondem a um evento. 
- Quando são com estado (chamadas de Durable Functions), um contexto é passado pela função para acompanhar a atividade anterior.

As funções são um componente chave da computação sem servidor. Elas também são uma plataforma de computação geral para executar qualquer tipo de código. Se as necessidades do aplicativo do desenvolvedor forem alteradas, você poderá implantar o projeto em um ambiente que não seja sem servidor. Essa flexibilidade permite gerenciar o dimensionamento, executar em redes virtuais e até mesmo isolar completamente as funções.

### Azure Logic Apps

Os aplicativos lógicos são semelhantes às funções. Ambos permitem que você dispare lógica com base em um evento. Enquanto as funções executam código, os aplicativos lógicos executam fluxos de trabalho criados para automatizar cenários de negócios com base em blocos de lógica predefinida.

- Cada fluxo de trabalho de aplicativo lógico do Azure começa com um gatilho, que é acionado quando um evento específico ocorre ou quando novos dados disponíveis atendem a critérios específicos. 

- Vários gatilhos incluem recursos básicos de agendamento, para que os desenvolvedores possam especificar a regularidade das execuções das suas cargas de trabalho. 

- Cada vez que o gatilho é acionado, o mecanismo de Aplicativos Lógicos cria uma instância de aplicativo lógico que executa as ações no fluxo de trabalho. Essas ações também podem incluir 
    - conversões de dados
    - controles de fluxo, como instruções condicionais
    - instruções de comutação
    - loops e ramificações.

Você cria fluxos de trabalho de aplicativo lógico usando um designer visual no portal do Azure ou no Visual Studio. Os fluxos de trabalho são mantidos como um arquivo JSON com um esquema de fluxo de trabalho conhecido.

O Azure fornece mais de 200 conectores e blocos de processamento para você interagir com diferentes serviços. Você também pode criar etapas de fluxo de trabalho e conectores personalizados caso o serviço com o qual precisa interagir não esteja coberto. 

Você passa dados pelo fluxo de trabalho para fazer o processamento personalizado, geralmente sem escrever nenhum código.

Por exemplo, digamos que chegou um tíquete no Zendesk. Você pode:

- Detectar a intenção da mensagem com os serviços cognitivos.
- Criar um item no SharePoint para acompanhar o problema.
- Adicionar o cliente ao seu sistema de CRM do Dynamics 365 caso ele não esteja no banco de dados.
- Envie um email de acompanhamento para confirmar a solicitação.
- Ideal para uma função de analista de negócios.

### Functions vs. Aplicativos Lógicos

O Functions e os Aplicativos Lógicos podem criar orquestrações complexas. Uma orquestração é uma coleção de funções ou etapas que são executadas para realizar uma tarefa complexa.

- Com o Functions, você escreve código para concluir cada etapa.
- Com os Aplicativos Lógicos, você usa uma GUI para definir as ações e como elas se relacionam entre si.

Você pode combinar serviços ao compilar uma orquestração, chamando funções de aplicativos lógicos e chamando aplicativos lógicos de funções. No entanto, há algumas diferenças entre essas implementações.

||Funções|Aplicativos Lógicos|
|-|-|-|
|Estado|Normalmente sem estado, mas as Durable Functions fornecem o estado.|Com estado.|
|Desenvolvimento|Code First (imperativo).Designer First (declarativo).|
|Conectividade|Cerca de uma dezena de tipos de associação internos. Escrever código para associações personalizadas.|Ampla coleção de conectores. Enterprise Integration Pack para cenários B2B. Crie conectores personalizados.|
|Ações|Cada atividade é uma função do Azure. Escreva o código para as funções de atividade.|Ampla coleção de ações prontas.|
|Monitoramento|Azure Application Insights.|Portal do Azure, Log Analytics.|
|Gerenciamento|API REST, Visual Studio.|Portal do Azure, API REST, PowerShell, Visual Studio.|
|Contexto de execução|Podem ser executadas no local ou na nuvem.|São executados somente na nuvem.|

## Decidir quando usar Azure Virtual Desktop

A Área de Trabalho Virtual do Azure é um serviço de virtualização de área de trabalho e aplicativos que é executado na nuvem. 

- Ele permite que os usuários usem uma versão do Windows hospedada na nuvem em qualquer localização. 
- Funciona em dispositivos como Windows, Mac, iOS, Android e Linux. 
- Funciona com aplicativos de acesso de Áreas de Trabalho Remotas (Remote Desktop). 
- Pode usar os navegadores para acessar experiências hospedadas na Azure Virtual Desktop.

### Fornecer a melhor experiência do usuário

Os usuários têm a liberdade de se conectar à Área de Trabalho Virtual do Azure com qualquer dispositivo pela Internet.

Você pode garantir que suas VMs (máquinas virtuais) do host de sessão sejam executadas perto de aplicativos e serviços que se conectam ao seu datacenter ou à nuvem. 

A conexão do usuário na Área de Trabalho Virtual do Azure é rápida porque os perfis de usuário são colocados em contêineres usando o FSLogix.

Você pode fornecer propriedade individual por meio de áreas de trabalho pessoais (persistentes). Por exemplo, talvez seja interessante fornecer Áreas de Trabalho Remotas pessoais para membros de uma equipe de engenharia. Eles podem adicionar ou remover programas sem afetar outros usuários nessa Área de Trabalho Remota.

### Aprimorar a segurança

- A Azure Virtual Desktop oferece gerenciamento de segurança centralizado para as áreas de trabalho dos usuários com o Azure AD (Azure Active Directory). 
- Você pode habilitar a autenticação multifator para proteger as entradas do usuário. 
- Você também pode proteger o acesso aos dados atribuindo RBACs (Role-based Access Control) granulares aos usuários.
- Os dados e aplicativos ficam separados do hardware local. O risco de dados confidenciais serem deixados em um dispositivo pessoal é reduzido.
- As sessões de usuário são isoladas em ambientes de sessão única e de várias sessões.

A Azure Virtual Desktop também aprimora a segurança usando a tecnologia de conexão reversa. Esse tipo de conexão é mais seguro do que o protocolo RDP. Não abrimos portas de entrada para as VMs do host de sessão.

### Quais são alguns dos principais recursos do Azure Virtual Desktop?

#### Gerenciamento simplificado

- Você usa o Azure AD e RBACs para gerenciar o acesso aos recursos. 
- Com o Azure, você também obtém ferramentas para automatizar implantações de VM, gerenciar atualizações de VM e fornecer recuperação de desastre. 
- Usa o Azure Monitor para monitoramento e alertas. Essa padronização permite que os administradores identifiquem problemas por meio de uma interface.

#### Gerenciamento de desempenho

A Azure Virtual Desktop oferece opções para balancear a carga dos usuários em seus pools de host de VM. Os pools de host são coleções de VMs com a mesma configuração atribuída a vários usuários. Para obter o melhor desempenho, você pode configurar o balanceamento de carga para ocorrer conforme os usuários entram (breadth mode). 

Com o breadth mode, os usuários são alocados sequencialmente no pool de host para sua carga de trabalho. Para economizar custos, você pode configurar suas VMs para o balanceamento de carga do modo de profundidade, em que os usuários são totalmente alocados em uma VM antes de passar para a próxima. 

A Azure Virtual Desktop fornece ferramentas para provisionar automaticamente VMs adicionais quando a demanda de entrada excede um limite especificado.

#### Implantação do Windows 10 multissessão

A Azure Virtual Desktop permite que você use a multissessão do Windows 10 Enterprise, o único sistema operacional baseado em cliente Windows que habilita vários usuários simultâneos em uma VM. A Área de Trabalho Virtual do Azure também fornece uma experiência mais consistente com suporte a aplicativos mais amplo em comparação com sistemas operacionais baseados no Windows Server.

### Como você pode reduzir os custos com a Azure Virtual Desktop?

#### Traga sua própria licença

A Azure Virtual Desktop estará disponível para você sem custos adicionais se você tiver uma licença do Microsoft 365 qualificada. Pague apenas pelos recursos do Azure usados pela Azure Virtual Desktop.

- Traga sua licença do Windows ou Microsoft 365 qualificada para obter aplicativos e áreas de trabalho do Windows 10 Enterprise e Windows 7 Enterprise sem custo adicional.
- Se você for um cliente com licença de acesso para cliente aos Serviços de Área de Trabalho Remota da Microsoft, os aplicativos e as áreas de trabalho dos Serviços de Área de Trabalho Remota do Windows Server estarão disponíveis sem custo adicional.

#### Economize em custos de computação

Compre Instâncias de Máquinas Virtuais Reservadas do Azure de um ou de três anos para economizar até 72% em relação aos preços pagos conforme o uso. Você pode pagar por uma reserva de forma antecipada ou mensal. As reservas fornecem um desconto de cobrança e não afetam o estado de runtime dos recursos.

## Resumo

Você aprendeu a usar:

- O Azure App Service para criar os front-ends de site.
- O Azure Functions criar uma lógica de aplicativo controlada por evento que só é executada quando você precisa dela.
- Azure Virtual Desktop para fornecer rapidamente um ambiente personalizado de software e sistema operacional para seus funcionários remotos.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

## 🔸 <a name="Explorar_os_serviços_de_rede_do_Azure"></a>Explorar os serviços de rede do Azure

Neste módulo, você examinará vários dos principais recursos de rede que estão disponíveis no Azure. Você aprenderá sobre a Rede Virtual do Azure, que pode ser configurada em um ambiente de rede personalizado que atenda às necessidades da sua empresa. Você também aprenderá a usar o Gateway de VPN do Azure e o Azure ExpressRoute para criar túneis de comunicação segura entre as diferentes localizações da sua empresa.

Depois de concluir este módulo, você poderá:

- Descrever os principais recursos de rede que estão disponíveis no Azure.
- Descrever os benefícios e o uso da Rede Virtual, do Gateway de VPN e do ExpressRoute.

## Conceitos básicos da Rede Virtual do Azure

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

## Configurações de Rede Virtual do Azure

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

## Conceitos básicos do Gateway de VPN do Azure

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

## Conceitos básicos do ExpressRoute do Azure

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

# 🔸 <a name="Explorar_os_serviços_do_Armazenamento_do_Azure"></a>Explorar os serviços do Armazenamento do Azure

Depois de concluir este módulo, você poderá descrever os benefícios e o uso destes serviços:

- Azure Blob Storage
- Azure Disk Storage
- Azure Files
- Camadas de acesso do Azure Blob 

## Conceitos básicos da conta do Azure Storage 

É um serviço que você pode usar para armazenar arquivos, mensagens, tabelas e outros tipos de informações.

Você pode criar uma conta de Armazenamento do Azure usando o portal do Azure, o PowerShell ou a CLI do Azure.

Uma conta de armazenamento fornece um namespace exclusivo para os dados do Armazenamento do Microsoft Azure, que podem ser acessados de qualquer lugar do mundo por HTTP ou HTTPS. Os dados nesta conta são seguros, altamente disponíveis, duráveis e maciçamente escalonáveis.

## Conceitos básicos do Disk storage

O Armazenamento em Disco fornece discos para máquinas virtuais do Azure. Aplicativos e outros serviços podem acessar e usar os discos conforme necessário, do mesmo modo que aconteceria em cenários locais. O Armazenamento em Disco permite que os dados sejam armazenados de forma persistente e acessados de um disco rígido virtual anexado.

Os discos são apresentados em vários tamanhos e níveis de desempenho diferentes, de SSDs até HDs tradicionais, com diferentes níveis de desempenho. 

É possível usar discos SSD e HDD padrão para cargas de trabalho menos críticas, discos SSD premium para aplicativos de produção críticos e discos ultra para cargas de trabalho com uso intensivo de dados, como SAP HANA, bancos de dados de nível superior e cargas de trabalho com muitas transações. 

O Azure tem fornecido consistentemente a durabilidade de nível empresarial para laas (infraestrutura como serviço), com uma taxa de falha anual de 0% líder no setor.

A ilustração a seguir mostra uma máquina virtual do Azure que usa discos separados para armazenar dados diferentes.

![azure-disks](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-storage-fundamentals/media/azure-disks-7841e01e.png)

## Conceitos básicos do Azure Blob storage

O Armazenamento de Blobs do Azure é uma solução de armazenamento de objetos para a nuvem. Ele pode armazenar grandes quantidades de dados, como texto ou dados binários. O Armazenamento de Blobs do Azure não é estruturado, o que significa que não há nenhuma restrição quanto aos tipos de dados que ele pode armazenar. O Armazenamento de Blobs pode gerenciar milhares de carregamentos simultâneos, grandes quantidades de dados de vídeo, arquivos de log em constante crescimento e pode ser acessado de qualquer lugar com uma conexão com a Internet.

Os blobs não estão limitados a formatos de arquivo comuns. Um blob pode conter gigabytes de dados binários transmitidos de um instrumento científico, uma mensagem criptografada para outro aplicativo ou dados em um formato personalizado para um aplicativo que você está desenvolvendo. 

Uma vantagem do armazenamento de blobs sobre o armazenamento em disco é que os desenvolvedores não precisam pensar em discos nem gerenciá-los. Os dados são carregados como blobs, e o Azure cuida das necessidades do armazenamento físico.

O Armazenamento de Blobs é ideal para:

- Fornecimento de imagens ou de documentos diretamente a um navegador.
- Armazenamento de arquivos para acesso distribuído.
- Transmissão por streaming de áudio e vídeo.
- Armazenamento de dados de backup e restauração, recuperação de desastres e arquivamento.
- Armazenamento de dados para análise por um serviço local ou hospedado no Azure.
- Armazenamento de até 8 TB de dados para máquinas virtuais.

Você pode armazenar os blobs em contêineres, o que ajuda a organizá-los de acordo com suas necessidades de negócios.

O diagrama a seguir ilustra como você pode usar contas, contêineres e blobs do Azure.

![account-container-blob](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-storage-fundamentals/media/account-container-blob-4da0ac47.png)

## Conceitos básicos do Azure Files

Os Arquivos do Azure oferecem compartilhamentos de arquivo totalmente gerenciados na nuvem que são acessíveis por meio dos protocolos SMB e Network File System (versão prévia) padrão do setor. 

Os compartilhamentos de arquivos do Azure podem ser montados de maneira simultânea por implantações locais ou na nuvem do Windows, do Linux e do MacOS. 

Aplicativos executados em máquinas virtuais do Azure ou em serviços de nuvem podem montar um compartilhamento de armazenamento de arquivo para acessar dados de arquivos, assim como um aplicativo de área de trabalho montaria um compartilhamento SMB típico. 

Qualquer quantidade de máquinas virtuais ou funções do Azure podem montar e acessar o compartilhamento de armazenamento de arquivos simultaneamente. Um cenário de uso típico seria compartilhar arquivos em qualquer lugar no mundo, bem como dados de diagnóstico ou compartilhamento de dados do aplicativo.

Use Arquivos do Azure para as seguintes situações:

- Muitos aplicativos locais usam compartilhamentos de arquivos. Os Arquivos do Azure facilitam a migração desses aplicativos que compartilham dados para o Azure. Se você montar o compartilhamento de arquivo do Azure na mesma letra da unidade que o aplicativo local usa, a parte do aplicativo que acessa o compartilhamento de arquivo deverá funcionar com alterações mínimas, se houver.

- Armazene arquivos de configuração em um compartilhamento de arquivos e acesse-os de várias VMs. As ferramentas e utilitários usados por vários desenvolvedores em um grupo podem ser armazenados em um compartilhamento de arquivos, garantindo que todas as pessoas possam encontrá-los, e que usem a mesma versão.

- Grave dados em um compartilhamento de arquivos e processe ou analise os dados mais tarde. Por exemplo, talvez você queira fazer isso com logs de diagnóstico, métricas e despejos de memória.

A ilustração a seguir mostra os Arquivos do Azure usados para compartilhar dados entre dois locais geográficos. Os Arquivos do Azure garantem que os dados sejam criptografados em repouso, e o protocolo SMB garante que eles sejam criptografados em trânsito.

![azure-files](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-storage-fundamentals/media/azure-files-5f942c3e.png)

Uma característica que distingue os Arquivos do Azure dos arquivos de um compartilhamento corporativo é que você pode acessá-los em qualquer lugar do mundo usando uma URL que aponte para eles. Você também pode usar tokens SAS (Shared Access Signature) para permitir o acesso a um ativo privado por um período específico.

Veja um exemplo de um URI de SAS de serviço, mostrando o URI de recurso e o token SAS:

![sas-storage-uri](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-storage-fundamentals/media/sas-storage-uri-037308fa.png)

## Noções básicas sobre as camadas de acesso de blobs

Os dados armazenados na nuvem podem crescer em um ritmo exponencial. Para gerenciar os custos de suas necessidades cada vez maiores de armazenamento, é útil organizar seus dados com base em atributos como frequência de acesso e período de retenção planejado. 

Alguns dados são ativamente acessados e modificados durante seu ciclo de vida. Alguns dados são acessados com frequência no início do seu tempo de vida, mas esse acesso cai drasticamente à medida que os dados envelhecem. Alguns dados permanecem ociosos na nuvem e raramente são acessos depois de armazenados, talvez nunca. 

O Armazenamento do Azure oferece diferentes camadas de acesso para seu armazenamento de blobs, ajudando você a armazenar dados de objeto da maneira mais econômica. 

- **Hot access tier**: otimizada para armazenar dados que são acessados com frequência (por exemplo, imagens de seu site).
- **Cool access tier**: otimizada para dados acessados com menos frequência e armazenados por pelo menos 30 dias (por exemplo, faturas de seus clientes).
- **Archive access tier**: adequada para dados acessados raramente e armazenados por pelo menos 180 dias, com requisitos de latência flexíveis (por exemplo, backups de longo prazo).

As seguintes considerações se aplicam às diferentes camadas de acesso:

- Apenas as camadas de acesso Hot e Cool podem ser definidas no nível da conta. A camada de acesso aos arquivos não está disponível no nível da conta.
- Camadas de acesso frequente, esporádico e de arquivos podem ser definidas no nível do blob, durante ou após o upload.
- Os dados na camada de acesso Cool podem tolerar uma disponibilidade ligeiramente inferior, mas ainda requerem alta durabilidade, latência de recuperação e características de taxa de transferência semelhantes a dados de acesso frequente. Para dados de acesso esporádico, um SLA (contrato de nível de serviço) de disponibilidade ligeiramente inferior e custos de acesso mais altos comparados com os dados de acesso frequente são compensações aceitáveis para custos de armazenamento mais baixos.
- O armazenamento de arquivos armazena dados offline e oferece os custos de armazenamento mais baixos, mas também os mais altos custos para reidratar e acessar dados.

### Resumo

Neste módulo, você descobriu como o Armazenamento do Azure pode fornecer à sua empresa uma variedade de opções para armazenar seus dados. Por exemplo, você aprendeu que sua primeira etapa ao usar o Armazenamento do Azure é criar uma conta de armazenamento. Depois que você faz isso, o Azure fornece várias opções para armazenar seus dados.

Além disso, o Azure fornece várias camadas de acesso que você pode usar para equilibrar custos de armazenamento com suas necessidades de negócios.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

## 🔸 <a name="Explorar_os_serviços_de_banco_de_dados_e_análise_do_Azure"></a> Explorar os serviços de banco de dados e análise do Azure

Depois de concluir este módulo, você poderá descrever os benefícios e o uso destes serviços:

- Azure Cosmos DB
- Banco de Dados SQL do Azure
- Instância Gerenciada do Azure SQL
- Banco de Dados do Azure para MySQL
- Banco de Dados do Azure para PostgreSQL
- Azure Synapse Analytics
- Azure HDInsight
- Azure Databricks
- Análise Azure Data Lake

## Explorar o Azure Cosmos DB

O Azure Cosmos DB é um serviço de multimodelo de banco de dados distribuído globalmente. Você pode escalar de modo elástico e independente a taxa de transferência e o armazenamento em qualquer número de regiões do Azure em todo o mundo. Você pode aproveitar o acesso a dados rápido e em poucos milissegundos usando uma das várias APIs populares. O Azure Cosmos DB fornece contratos de nível de serviço abrangentes para taxa de transferência, latência, disponibilidade e garantias de consistência.

O Azure Cosmos DB dá suporte a dados sem esquema, o que permite criar aplicativos "Always On" altamente responsivos para dar suporte a dados em constante mudança. Você pode usar esse recurso para armazenar dados que são atualizados e mantidos por usuários em todo o mundo.

O Azure Cosmos DB é flexível. No nível mais baixo, o Azure Cosmos DB armazena dados no formato ARS (atom-record-sequence). Os dados são então abstraídos e projetados como uma API, que você especifica ao criar o seu banco de dados. Suas opções incluem SQL, MongoDB, Cassandra, Tables e Gremlin. Esse nível de flexibilidade significa que, conforme você migra os bancos de dados da empresa para o Azure Cosmos DB, os desenvolvedores podem continuar usando as APIs com as quais se sentem mais confortáveis.

## Explorar o Banco de Dados SQL do Azure

O Banco de Dados SQL do Azure é um banco de dados relacional baseado na última versão estável do mecanismo de banco de dados do Microsoft SQL Server. O Banco de Dados SQL é um banco de dados confiável, totalmente gerenciado, seguro e de alto desempenho. Ele pode ser usado para criar aplicativos orientados a dados e sites na linguagem de programação de sua escolha, sem a necessidade de gerenciar a infraestrutura.

### Recursos

- O Banco de Dados SQL do Azure é um mecanismo de banco de dados de PaaS (plataforma como serviço). 
- Ele lida com a maioria das funções de gerenciamento de banco de dados – como atualização, aplicação de patches, backups e monitoramento – sem envolvimento do usuário. 
- O Banco de Dados SQL fornece 99,99% de disponibilidade. 
- As funcionalidades de PaaS internas do Banco de Dados SQL permitem que você se concentre nas atividades de administração e otimização de banco de dados específicas do domínio que são críticas para a sua empresa. 
- O Banco de Dados SQL é um serviço totalmente gerenciado que tem alta disponibilidade interna, backups e outras operações de manutenção comuns. 
- A Microsoft administra todas as atualizações para o código do sistema operacional e do SQL. Não é preciso gerenciar a infraestrutura subjacente.

O Banco de Dados SQL pode ser a escolha certa para diversos aplicativos de nuvem modernos, pois permite processar dados relacionais e estruturas não relacionais, como grafos, JSON, espaciais e XML.

Você recebe as funcionalidades mais recentes do SQL Server sem a sobrecarga de atualizações ou upgrades, testadas em milhões de bancos de dados.

### Migração

Você pode migrar os seus bancos de dados existentes do SQL Server com o tempo de inatividade mínimo usando o Serviço de Migração de Banco de Dados do Azure. O Assistente de Migração de Dados da Microsoft pode gerar relatórios de avaliação que fornecem recomendações para orientar você quanto às alterações necessárias antes de executar uma migração. Após avaliar e resolver qualquer correção necessária, você estará pronto para iniciar o processo de migração. O Serviço de Migração de Banco de Dados do Azure executa todas as etapas necessárias. Você apenas altera a cadeia de conexão em seus aplicativos.

## Explorar o banco de dados do Azure para MySQL

- O Banco de Dados do Azure para MySQL é um serviço de banco de dados relacional na nuvem que se baseia no mecanismo de banco de dados MySQL Community Edition, nas versões 5.6, 5.7 e 8.0. 
- Tem um SLA de 99,99% de disponibilidade no Azure, capacitado por uma rede global de datacenters gerenciados pela Microsoft. Isso ajuda a manter o seu aplicativo em execução 24/7. 
- Você tira proveito dos recursos internos de segurança, tolerância a falhas e proteção de dados que, em outras situações, seria necessário comprar ou projetar, criar e gerenciar. 
- Você pode usar a restauração pontual para recuperar um servidor para um estado anterior, com alcance de até 35 dias.

O Banco de Dados do Azure para MySQL fornece:

- Alta disponibilidade interna sem nenhum custo adicional.
- Desempenho previsível e pagamento conforme o uso inclusivo.
- Escale em segundos, conforme o necessário.
- Capacidade de proteger dados confidenciais inativos e em uso.
- Backups automáticos.
- Segurança e conformidade de nível empresarial.

Esses recursos não precisam de quase nenhuma administração e todos são fornecidos sem nenhum custo adicional. Eles permitem que você se concentre no desenvolvimento rápido de aplicativos e acelere o tempo de colocação no mercado, em vez de precisar gerenciar as máquinas virtuais e a infraestrutura. Além disso, você pode migrar os seus bancos de dados MySQL existentes com tempo de inatividade mínimo usando o Serviço de Migração de Banco de Dados do Azure. Depois de concluir a migração, você poderá continuar a desenvolver o seu aplicativo com as ferramentas de software livre e a plataforma de sua escolha. Você não precisa aprender novas habilidades.

O Banco de Dados do Azure para MySQL oferece várias camadas de serviço e cada uma oferece desempenho e funcionalidades diferentes para dar suporte a cargas de trabalho de banco de dados leves e pesadas. Você pode criar seu primeiro aplicativo em um banco de dados pequeno por poucos dólares ao mês e depois ajustar a escala para atender às necessidades da solução. A escalabilidade dinâmica permite que o banco de dados responda de forma transparente a mudanças rápidas nos requisitos de recursos. Você paga apenas pelos recursos de que precisa, e somente quando precisa deles.

## Explorar o Banco de Dados do Azure para PostgreSQL

O Banco de Dados do Azure para PostgreSQL é um serviço de banco de dados relacional na nuvem. O software para servidores se baseia na versão da comunidade do mecanismo de banco de dados PostgreSQL de software livre. 

Além disso, o Banco de Dados do Azure para PostgreSQL oferece os seguintes benefícios:
 
- Alta disponibilidade interna em comparação com recursos locais. Não há nenhuma configuração, replicação ou custo adicionais necessários para garantir que os seus aplicativos estejam sempre disponíveis.
- Preços simples e flexíveis. Você tem um desempenho previsível com base em uma opção de tipo de preço selecionada que inclui aplicação de patch de software, backups automáticos, monitoramento e segurança.
- Escale ou reduza verticalmente conforme necessário em segundos. Você pode dimensionar a computação ou o armazenamento de forma independente, conforme necessário, para garantir a adaptação do serviço para que ele corresponda ao uso.
- Backups automáticos ajustáveis e restauração pontual por até 35 dias.
- Segurança e conformidade de nível corporativo para proteger dados confidenciais em repouso e em movimento. Essa segurança aborda a criptografia de dados em disco e a criptografia SSL na comunicação entre o cliente e o servidor.

O Banco de Dados do Azure para PostgreSQL está disponível em duas opções de implantação: Servidor Único e Hiperescala (Citus).

### Servidor único

A opção de implantação Servidor Único oferece:

- Alta disponibilidade interna sem custo adicional (99,99% de SLA).
- Desempenho previsível e pagamento conforme o uso inclusivo.
- Escale verticalmente em segundos, conforme o necessário.
- Monitoramento e alertas para avaliar o servidor.
- Segurança e conformidade de nível empresarial.
- Capacidade de proteger dados confidenciais em repouso e em movimento.
- Backups automáticos e restauração pontual por até 35 dias.

A opção de implantação Servidor Único oferece três tipos de preço: Básico, Uso Geral e Otimizado para Memória. Cada tipo oferece recursos diferentes para dar suporte a suas cargas de trabalho do banco de dados.

### Hiperescala (Citus)

A opção de Hiperescala (Citus) escala horizontalmente as consultas em vários computadores usando a fragmentação. Seu mecanismo de consulta faz a correspondência entre consultas SQL recebidas nesses servidores para obter respostas mais rápidas em grandes conjuntos de dados. Ele serve para aplicativos que exigem maior escala e desempenho, que geralmente são as cargas de trabalho que estão se aproximando ou já excederam 100 GB de dados.

A opção de implantação de Hiperescala (Citus) dá suporte para aplicativos multilocatários, análise operacional em tempo real e cargas de trabalho transacionais com alta taxa de transferência. Os aplicativos criados para o PostgreSQL podem executar consultas distribuídas em Hiperescala (Citus) com bibliotecas de conexão padrão e alterações mínimas.

## Explorar o Azure SQL Managed Instance

A Instância Gerenciada de SQL do Azure é um serviço de dados de nuvem escalonável que fornece a mais ampla compatibilidade do mecanismo de banco de dados do SQL Server com todos os benefícios de uma plataforma como serviço totalmente gerenciada. Dependendo do cenário, a Instância Gerenciada de SQL do Azure pode oferecer mais opções para suas necessidades de banco de dados.

Assim como o Banco de Dados SQL do Azure, a Instância Gerenciada de SQL do Azure é um mecanismo de banco de dados PaaS (plataforma como serviço), o que significa que sua empresa poderá tirar proveito dos melhores recursos ao mover seus dados para a nuvem em um ambiente totalmente gerenciado.

Por exemplo, a empresa não precisará mais comprar e gerenciar hardwares caros, e você não precisará manter a sobrecarga adicional de gerenciar a infraestrutura local. Sua empresa também se beneficiará dos recursos de provisionamento rápido e dimensionamento de serviços do Azure, bem como da aplicação de patch automatizada e das atualizações de versão. Além disso, você poderá ter a certeza de que seus dados sempre estarão lá quando você precisar deles, por meio de recursos internos de alta disponibilidade e de um SLA (contrato de nível de serviço) de 99,99% de tempo de atividade. Você também poderá proteger os dados com backups automatizados e um período de retenção de backup configurável.

No entanto, a Instância Gerenciada de SQL do Azure fornece várias opções que podem não estar disponíveis no Banco de Dados SQL do Azure. 

### Migração

A Instância Gerenciada de SQL do Azure facilita a migração de dados locais no SQL Server para a nuvem usando o DMS (Serviço de Migração de Banco de Dados) do Azure ou backup e a restauração nativos. Depois de descobrir todos os recursos que sua empresa usa, você precisa avaliar quais instâncias do SQL Server locais pode migrar para a Instância Gerenciada de SQL do Azure para ver se há algum problema de bloqueio. Após resolver possíveis problemas, você pode migrar os dados e fazer a transferência do SQL Server local para a Instância Gerenciada de SQL do Azure alterando a cadeia de conexão em seus aplicativos.

## Explorar Big Data e Analytics

Tecnologias de cluster de software livre foram desenvolvidas, com o passar do tempo, para lidar com esses grandes conjuntos de dados. O Microsoft Azure dá suporte a uma ampla variedade de tecnologias e serviços para fornecer Big Data e soluções analíticas, incluindo o Azure Synapse Analytics, o Azure HDInsight, o Azure Databricks e o Azure Data Lake Analytics.

### Azure Synapse Analytics

O Azure Synapse Analytics (antigo SQL Data Warehouse do Azure) é um serviço de análise ilimitado que reúne data warehouse corporativo e análise de Big Data. Você pode consultar dados da maneira que preferir, usando recursos sem servidor ou provisionados em escala. Você tem uma experiência unificada para ingerir, preparar, gerenciar e fornecer dados para atender às necessidades imediatas de business intelligence e de aprendizado de máquina.

### Azure HDInsight

O Azure HDInsight é um serviço de análise de software livre totalmente gerenciado para empresas. Trata-se de um serviço de nuvem que torna mais fácil, mais rápido e mais econômico o processamento de grandes quantidades de dados. Você pode executar estruturas de software livre populares e criar tipos de cluster como Apache Spark, Apache Hadoop, Apache Kafka, Apache HBase, Apache Storm e Serviços de Machine Learning. O HDInsight também dá suporte a uma ampla gama de cenários, como ETL (extração, transformação e carregamento), data warehousing, machine learning e IoT.

### Azure Databricks

O Azure Databricks ajuda a descobrir insights dos seus dados e a criar soluções de inteligência artificial. Você pode configurar seu ambiente do Apache Spark em minutos, dimensioná-lo automaticamente e colaborar em projetos compartilhados em um workspace interativo. O Azure Databricks dá suporte a Python, Scala, R, Java e SQL, bem como a bibliotecas e estruturas de ciência de dados, incluindo TensorFlow, PyTorch e scikit-learn.

### Azure Data Lake Analytics

O Azure Data Lake Analytics é um serviço de trabalho de análise sob demanda que simplifica Big Data. Em vez de implantar, configurar e ajustar o hardware, você cria consultas para transformar os dados e extrair insights importantes. O serviço de análise pode manipular trabalhos de qualquer escala de maneira instantânea, simplesmente configurando o controle para a quantidade de potência necessária. Você pagará pelo trabalho somente quando ele estiver em execução, tornando-o mais econômico.

### Resumo

Você viu como o Banco de Dados SQL do Azure, o Banco de Dados do Azure para MySQL e o Banco de Dados do Azure para PostgreSQL permitem que a empresa migre os bancos de dados existentes do SQL Server, do MySQL e do PostgreSQL para a nuvem. Você pode fazer isso ao mesmo tempo que preserva os pontos fortes da administração de banco de dados e o desenvolvimento da sua empresa.

Além disso, você viu como o Azure Cosmos DB funciona com uma variedade de APIs populares, incluindo o SQL, o MongoDB, o Cassandra, o Tables e o Gremlin. Você pode usá-los para migrar os seus dados para a nuvem e manter ou aprimorar as habilidades dos seus desenvolvedores. Você também aprendeu a usar os serviços de análise e de Big Data, como o Azure Synapse Analytics, o Azure HDInsight, o Azure Databricks e o Azure Data Lake Analytics, para analisar grandes volumes de dados.

---

# ☁️ <a name="parte3"></a> Princípios básicos do Microsoft Azure: Descrever as principais soluções e ferramentas de gerenciamento no Azure

1. [Escolha o serviço de IoT do Azure mais adequado para o seu aplicativo](#Escolha_o_serviço_de_IoT_do_Azure_mais_adequado_para_o_seu_aplicativo)
2. [Escolha o melhor serviço de IA para suas necessidades](#Escolha_o_melhor_serviço_de_IA_para_suas_necessidades)
3. [Escolher a melhor tecnologia sem servidor do Azure para seu cenário empresarial](#Escolher_a_melhor_tecnologia_sem_servidor_do_Azure_para_seu_cenário_empresarial)
4. [Escolha as melhores ferramentas para ajudar as organizações a criar soluções melhores](#Escolha_as_melhores_ferramentas_para_ajudar_as_organizações_a_criar_soluções_melhores)
5. [Escolha as melhores ferramentas para gerenciar e configurar seu ambiente do Azure](#Escolha_as_melhores_ferramentas_para_gerenciar_e_configurar_seu_ambiente_do_Azure)
6. [Escolher o melhor serviço de monitoramento para visibilidade, insight e mitigação de interrupções](#Escolher_o_melhor_serviço_de_monitoramento_para_visibilidade_insight_e_mitigação_de_interrupções)

Ao final deste roteiro de aprendizagem, você poderá:

- Escolher o serviço de Inteligência Artificial do Azure correto para lidar com diferentes tipos de desafios de negócios.
- Escolher os melhores serviços e ferramentas de processo de desenvolvimento de software para um determinado cenário de negócios.
- Escolher o serviço de monitoramento de nuvem correto para lidar com diferentes tipos de desafios de negócios.
- Escolher a ferramenta de gerenciamento do Azure correta para abordar diferentes tipos de necessidades técnicas e desafios.
- Escolher a tecnologia de computação sem servidor certa para seu cenário de negócios.
- Escolher o melhor serviço de IoT do Azure para um determinado cenário de negócios.

## 🔸 <a name="Escolha_o_serviço_de_IoT_do_Azure_mais_adequado_para_o_seu_aplicativo">Escolha o serviço de IoT do Azure mais adequado para o seu aplicativo
#estouaqui
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