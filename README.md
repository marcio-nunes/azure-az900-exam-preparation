# <a name="topo"></a>Preparação para o exame Azure AZ-900

- [Microsoft Learn path](https://docs.microsoft.com/pt-br/learn/paths/az-900-describe-cloud-concepts/)
- [AZ-900: Microsoft Azure Fundamentals Sample Questions](https://docs.microsoft.com/en-us/learn/certifications/resources/az-900-sample-questions?azure-portal=true)
- [Exame AZ-900: Fundamentos do Microsoft Azure](https://docs.microsoft.com/pt-br/learn/certifications/exams/az-900)
- [Study Guide](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3VwUY)
- https://emojipedia.org/symbols/

## Preparação para o Exame AZ-900

Esse exame inclui seis áreas de domínio de conhecimento:

|Área de domínio do AZ-900|Weight|
|-|-|
|Descrever os conceitos da nuvem|20-25%|
|Descrever os principais serviços do Azure|15-20%|
|Descrever as principais soluções e ferramentas de gerenciamento no Azure|10-15%|
|Descrever os recursos gerais de segurança de rede e segurança|10-15%|
|Descrever recursos de identidade, governança, privacidade e conformidade|20-25%|
|Descrever os Contratos de Nível de Serviço e o Gerenciamento de Custos da Microsoft|10-15%|

Icons: ☁️🔸

# ☁️ Princípios básicos do Microsoft Azure

- [Parte 1: Descrever os principais conceitos do Azure](#parte1)
    - [Descrever os conceitos de nuvem](#parte1-2)
- [Parte 2: Descrever os principais serviços do Azure](#parte2)
- [Parte 3: Descrever as principais soluções e ferramentas de gerenciamento no Azure](#parte3)
- [Parte 4: Descrever os recursos gerais de segurança de rede e segurança](#parte4)
- [Parte 5: Descrever recursos de identidade, governança, privacidade e conformidade](#parte5)
- [Parte 6: Descrever contratos de nível de serviço e Gerenciamento de Custos da Microsoft](#parte6)

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

### <u>IaaS - Infraestructure as a Service</u>

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

# ☁️ <a name="parte1-2"></a> Parte 1-2: Princípios básicos do Microsoft Azure: descrever os conceitos de nuvem

Depois de concluir este módulo, você poderá:

- Definir computação em nuvem.
- Descrever o modelo de responsabilidade compartilhada.
- Definir modelos de nuvem, incluindo público, privado e híbrido.
- Identificar os casos de uso apropriados para cada modelo de nuvem.
- Descrever o modelo baseado no consumo.
- Comparar os modelos de preços de nuvem.

1. [Descrever a computação em nuvem](#Descrever_a_computação_em_nuvem)
2. [Descrever os benefícios do uso de serviços de nuvem](#Descrever_os_benefícios_do_uso_de_serviços_de_nuvem)
3. [Descrever os tipos de serviço de nuvem](#Descrever_os_tipos_de_serviço_de_nuvem)

## 🔸 <a name=""></a> Descrever a computação em nuvem

## O que é computação em nuvem

A computação em nuvem é a entrega de serviços de computação pela Internet. Os serviços de computação incluem infraestrutura de TI comum, como máquinas virtuais, armazenamento, bancos de dados e rede. Os serviços de nuvem também expandem as ofertas tradicionais de TI para incluir itens como IoT (Internet das Coisas), ML (machine learning) e IA (inteligência artificial).

Como a computação em nuvem usa a Internet para fornecer esses serviços, ela não precisa ficar restrita pela infraestrutura física da mesma forma que um datacenter tradicional. Isso significa que, se você precisar aumentar rapidamente sua infraestrutura de TI, não precisará esperar para construir um novo datacenter; você pode usar a nuvem para expandir rapidamente seu volume de TI.

## Descrever o modelo de responsabilidade compartilhada

Num datacenter corporativo tradicional a empresa é responsável por manter o espaço físico, garantir a segurança e manter ou substituir os servidores se algo acontecer. TI é responsável por manter toda a infraestrutura e o software necessários para manter o datacenter em funcionamento. É provável que eles também sejam responsáveis por manter todos os sistemas corrigidos e na versão correta.

Com o modelo de responsabilidade compartilhada, essas responsabilidades são compartilhadas entre o provedor de nuvem e o consumidor. 
- Segurança física, energia, resfriamento e conectividade de rede são responsabilidade do provedor de nuvem. 
- O consumidor é responsável pelos dados e pelas informações armazenados na nuvem e pela segurança de acesso, o que significa que você só dá acesso àqueles que precisam.

Então, para algumas coisas, a responsabilidade depende da situação. 

- A IaaS coloca a maior responsabilidade sobre o consumidor, com o provedor de nuvem sendo responsável pelas questões básicas de segurança física, energia e conectividade. 
- O SaaS coloca a maior parte da responsabilidade no provedor de nuvem. 
- A PaaS, sendo um meio termo entre IaaS e SaaS, distribui uniformemente a responsabilidade entre o provedor de nuvem e o consumidor.

Você sempre será responsável por:

- Informações e dados armazenados na nuvem
- Dispositivos que têm permissão para se conectar à nuvem (telefones celulares, computadores e assim por diante)
- Contas e identidades das pessoas, serviços e dispositivos em sua organização

O provedor de nuvem é sempre responsável por:

- Datacenter físico
- Rede física
- Hosts físicos

Seu modelo de serviço determinará a responsabilidade por coisas como:

- Sistemas operacionais
- Controles de rede
- Aplicativos
- Identidade e infraestrutura

## Definir modelos de nuvem

Os modelos de nuvem definem o tipo de implantação de recursos de nuvem. 

### Nuvem privada

É uma nuvem (que fornece serviços de TI pela Internet) que é criada, controlada e mantida por uma única entidade. 

- A nuvem privada fornece um controle muito maior para a empresa e o departamento de TI. 
- Ela também tem mais custos e menos benefícios em relação a uma implantação de nuvem pública. 
- Pode ser hospedada em seu datacenter local. Ela também pode ser hospedada em um datacenter dedicado externo, até mesmo por terceiros que tenham dedicado esse datacenter à sua empresa.

### Nuvem pública

Uma nuvem pública é criada, controlada e mantida por um provedor de nuvem de terceiros. Com uma nuvem pública, qualquer pessoa que queira comprar serviços de nuvem pode acessar e usar os recursos. A disponibilidade pública geral é uma diferença fundamental entre nuvens públicas e privadas.

### Nuvem híbrida

Uma nuvem híbrida é um ambiente de computação que usa nuvens públicas e privadas em um ambiente interconectado. Um ambiente de nuvem híbrida pode ser usado para permitir que uma nuvem privada escale para atender a uma demanda maior temporária implantando recursos de nuvem pública. A nuvem híbrida pode ser usada para fornecer uma camada adicional de segurança. Por exemplo, os usuários podem escolher com flexibilidade quais serviços manter na nuvem pública e quais implantar na infraestrutura de nuvem privada.

| Nuvem pública | Nuvem privada | Nuvem híbrida |
|-|-|-|
| Nenhuma despesa de capital para escalar verticalmente | As organizações têm controle total sobre os recursos e a segurança | Fornece a maior flexibilidade |
| Os aplicativos podem ser provisionados e desprovisionados rapidamente | Os dados não são colocados com os dados de outras organizações | As organizações determinam o local para executar os aplicativos |
| As organizações pagam apenas pelo que utilizam | O hardware deve ser comprado para o início e a manutenção | As organizações controlam a segurança, a conformidade ou os requisitos legais |
|As organizações não têm controle total sobre os recursos e a segurança | As organizações são responsáveis pela manutenção e pelas atualizações de hardware | - |

### Várias nuvens

Em um cenário de várias nuvens, você usa vários provedores de nuvem pública. 

- Talvez você use recursos diferentes de diferentes provedores de nuvem. 
- Você pode ter iniciado seu percurso de nuvem com um provedor e esteja em processo de migração para um provedor diferente. 

Independentemente disso, em um ambiente de várias nuvens, você lida com dois (ou mais) provedores de nuvem pública e gerencia recursos e segurança em ambos os ambientes.

### Azure Arc

O Azure Arc é um conjunto de tecnologias que ajuda a gerenciar seu ambiente de nuvem. O Azure Arc pode ajudar a gerenciar sua nuvem pública de nuvem exclusivamente no Azure, em uma nuvem privada em seu datacenter, em uma configuração híbrida ou até mesmo em um ambiente de várias nuvens em execução em vários provedores de nuvem ao mesmo tempo.

### Solução VMware no Azure

E se você já estiver estabelecido com o VMware em um ambiente de nuvem privada, mas quiser migrar para uma nuvem pública ou híbrida? A Solução VMware no Azure permite executar suas cargas de trabalho do VMware no Azure com integração e escalabilidade total.

## Descrever o modelo baseado em consumo

Há dois tipos de despesas a serem consideradas:

- **CapEx** - normalmente é uma despesa inicial única para comprar ou proteger recursos tangíveis. Um prédio novo, a repavimentação do estacionamento, a construção de um datacenter ou a compra de um veículo da empresa são exemplos de CapEx.
- **OpEx** - é o gasto de capital em serviços ou produtos ao longo do tempo. O aluguel de um centro de convenções, o leasing de um veículo da empresa ou a assinatura de serviços de nuvem são exemplos de OpEx.

Na computação em nuvem, você não paga pela infraestrutura física, pela eletricidade, pela segurança nem por nada que esteja associado à manutenção de um datacenter. Você paga pelos recursos de TI que usa. 

Um modelo baseado em consumo oferece vários benefícios, como:

- Sem custos prévios.
- Não há necessidade de comprar nem gerenciar uma infraestrutura cara que os usuários talvez não usem na capacidade máxima.
- A capacidade de pagar para obter mais recursos quando necessário.
- A capacidade de parar de pagar por recursos que não são mais necessários.

A nuvem permite que você supere rapidamente os desafios empresariais mais difíceis e ofereça soluções de ponta para seus usuários.

- Planeje e gerencie os custos operacionais.
- Executar a infraestrutura com mais eficiência.
- Escale as operações de acordo com as necessidades de negócios.

### Resumo

Neste módulo, você aprendeu os conceitos gerais de nuvem. No início, você entendeu o que é a computação em nuvem. Você também entendeu o modelo de responsabilidade compartilhada e como você e o provedor de nuvem compartilham a responsabilidade de manter a segurança das informações na nuvem. Abordamos rapidamente as diferenças entre os modelos de nuvem (público, privado, híbrido e multinuvem). Depois, concluímos com uma unidade explicando como a nuvem muda os gastos de TI de despesa de capital para despesa operacional.

## 🔸 <a name=""></a> Descrever os benefícios do uso de serviços de nuvem

Ao concluir este módulo, você será capaz de:

- Descrever os benefícios da alta disponibilidade e da escalabilidade na nuvem.
- Descrever os benefícios da confiabilidade e da previsibilidade na nuvem.
- Descrever os benefícios da segurança e da governança na nuvem.
- Descrever os benefícios da capacidade de gerenciamento na nuvem.

## Descrever os benefícios da alta disponibilidade e da escalabilidade na nuvem

- **Alta disponibilidade** - Quando você está implantando qualquer recurso de TI, é importante que os recursos estejam disponíveis quando necessário. A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer. Ao arquitetar sua solução, você precisará considerar as garantias de disponibilidade do serviço. O Azure é um ambiente de nuvem altamente disponível com garantias de tempo de atividade, dependendo do serviço. Essas garantias fazem parte dos SLAs (Contratos de Nível de Serviço).

- **Escalabilidade** - Outro grande benefício da computação em nuvem é a escalabilidade dos recursos de nuvem. A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda. Se você experimentar um pico repentino de tráfego e seus sistemas ficarem sobrecarregados, a capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda. O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços. Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa. Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.

A escala geralmente vem em duas variedades:
- A escala vertical se concentra em aumentar ou diminuir a capacidade dos recursos. 
- A escala horizontal é adição ou subtração do número de recursos.

## Descrever os benefícios da confiabilidade e da previsibilidade na nuvem

- **Confiabilidade** - Resiliência é a capacidade que um sistema tem de se recuperar de falhas e continuar funcionando. 
    - Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo. Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.
- **Previsibilidade** - A previsibilidade na nuvem permite que você avance com confiança. 
    - Pode se concentrar na previsibilidade de desempenho ou na previsibilidade de custo. 
    - Ambos são bastante influenciadas pelo Microsoft Azure Well-Architected Framework. Implante uma solução criada com base nessa estrutura e você terá uma solução com custo e desempenho previsíveis.
        - **Previsibilidade de Desempenho** - se concentra em prever os recursos necessários para oferecer uma experiência positiva aos clientes. O dimensionamento automático, o balanceamento de carga e a alta disponibilidade são apenas alguns dos conceitos de nuvem que dão suporte à previsibilidade de desempenho.
        - **Previsibilidade de custos** - se concentra em prever o custo dos gastos com a nuvem. Operando na nuvem e usando a análise e as informações da nuvem, você pode prever custos futuros e ajustar os recursos conforme o necessário. Você pode até mesmo usar ferramentas como TCO (custo total de propriedade) ou a Calculadora de Preços para obter uma estimativa de possíveis gastos com a nuvem.

## Descrever os benefícios da segurança e da governança na nuvem

- **Governança** - Se você estiver implantando infraestrutura como serviço ou software como serviço, os recursos de nuvem vão dar suporte à governança e à conformidade. Itens como modelos de conjunto ajudam a garantir que todos os seus recursos implantados atendam aos padrões corporativos e aos requisitos regulatórios governamentais. Além disso, você pode atualizar todos os seus recursos implantados com novos padrões à medida que os padrões são alterados. A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação. Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.

- **Segurança** - Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção. Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.

Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

## Descrever os benefícios da capacidade de gerenciamento na nuvem

### Gerenciamento da nuvem

O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Na nuvem, você pode:

- Escalar automaticamente a implantação de recursos com base na necessidade.
- Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
- Monitorar a integridade dos recursos e substituir automaticamente os recursos com falha.
- Receber alertas automáticos com base em métricas configuradas, de modo a ficar ciente do desempenho em tempo real.

### Gerenciamento na nuvem

O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Você pode gerenciá-los:

- Por meio de um portal da Web.
- Usando uma interface de linha de comando.
- Usando APIs.
- Usando o PowerShell.



🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

## 🔸 <a name=""></a> Descrever os tipos de serviço de nuvem

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
🔼 [Voltar ao índice](#parte2)

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
🔼 [Voltar ao índice](#parte2)

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
🔼 [Voltar ao índice](#parte2)

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

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte2)

---

# ☁️ <a name="parte3"></a> Parte 3: Princípios básicos do Microsoft Azure: Descrever as principais soluções e ferramentas de gerenciamento no Azure

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

## 🔸 <a name="Escolha_o_serviço_de_IoT_do_Azure_mais_adequado_para_o_seu_aplicativo"></a>Escolha o serviço de IoT do Azure mais adequado para o seu aplicativo

Depois de concluir este módulo, você poderá:

- Escolher o serviço IoT do Azure mais adequado para lidar com seu cenário de negócios.

## Identificar as opções de produto

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

## Analisar os critérios de decisão

Critérios que os especialistas empregam quando decidem qual serviço IoT usar para uma determinada necessidade comercial.

### É essencial garantir que o dispositivo não seja comprometido?

Não em todos os casos. Os fabricantes e os clientes não querem que os respectivos dispositivos sejam comprometidos por ações mal-intencionadas e usados para fins maliciosos, mas, em alguns casos, a garantia da integridade é mais crítica do que em outros. Um exemplo seria um caixa eletrônico em comparação com uma máquina de lavar roupas. Quando a segurança é uma consideração crítica no design do seu produto, a melhor opção de produto é o Azure Sphere, que fornece uma solução abrangente de ponta a ponta para dispositivos IoT.

Como mencionamos na unidade anterior, o Azure Sphere garante um canal seguro de comunicação entre o dispositivo e o Azure controlando tudo, do hardware ao sistema operacional, além do processo de autenticação. Isso garante que a integridade do dispositivo não seja comprometida. Depois que um canal seguro for estabelecido, o dispositivo poderá receber mensagens com segurança. Além disso, as mensagens ou atualizações de software poderão ser enviadas ao dispositivo de maneira remota.

### Preciso de um painel para relatórios e gerenciamento?

Sua próxima decisão deverá ser baseada no nível dos serviços que você exige de sua solução de IoT. Caso queira somente se conectar aos dispositivos remotos para receber telemetria e, ocasionalmente, enviar atualizações por push e não há necessidade de obter funcionalidades de relatório, talvez você prefira implementar somente o Hub IoT do Azure. Seus programadores ainda poderão criar um conjunto personalizado de ferramentas e relatórios de gerenciamento usando a API RESTful do Hub IoT.

No entanto, caso queria uma interface do usuário personalizável e pré-criada com a qual será possível exibir e controlar seus dispositivos de maneira remota, talvez você prefira começar com o IoT Central. Com essa solução, será possível controlar um dispositivo ou todos eles de uma vez. Além disso, você poderá configurar alertas para determinadas condições, como uma falha do dispositivo.

O IoT Central integra-se com muitos produtos diferentes do Azure, incluindo o Hub IoT, para criar um painel com relatórios e recursos de gerenciamento. O painel é baseado em modelos de início para cenários comuns de uso e do setor. Será possível usar o painel gerado pelo modelo de início como está ou personalizá-lo para atender às suas necessidades. Você poderá ter vários painéis e direcioná-los a uma variedade de usuários.

A IoT é uma evolução empolgante na computação que conecta os mundos físicos e digitais. Os serviços IoT do Azure fornecem uma quantidade significativa de funcionalidades para as organizações que desejam criar soluções controladas por dispositivos e sensores.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte3)

---

## 🔸 <a name="Escolha_o_melhor_serviço_de_IA_para_suas_necessidades"></a> Escolha o melhor serviço de IA para suas necessidades

Após concluir este módulo, você conseguirá:

- Escolher os serviços de IA do Azure que melhor atendam aos desafios comerciais de sua empresa.

### Identificar as opções de produto

A IA é uma classificação de computação ampla que permite a um sistema de software perceber seu ambiente e tomar medidas que maximizem sua chance de atingir as metas. Umas das metas da IA é criar um sistema de software capaz de adaptar-se ou de aprender algo por conta própria sem ser explicitamente programado para isso.

Há duas abordagens básicas à IA. A primeira é empregar um sistema de aprendizado profundo modelado na rede neural da mente humana, permitindo que ele descubra, aprenda e cresça com a experiência.

A segunda abordagem é o machine learning, uma técnica de ciência de dados que usa dados existentes para treinar um modelo, testá-lo e, em seguida, aplicar esse modelo a novos dados para prever comportamentos, resultados e tendências futuros.

As estimativas ou previsões de aprendizado de máquina podem tornar aplicativos e dispositivos mais inteligentes.

Praticamente todos os dispositivos ou sistemas de software que coletam dados textuais, visuais e de áudio podem alimentar um modelo de machine learning que torna esse dispositivo ou sistema de software mais inteligente sobre como ele funciona no futuro.

### Opções de produto do Azure

#### Azure Machine Learning

O Azure Machine Learning é uma plataforma para fazer previsões. Ele consiste em ferramentas e serviços que permitem que você se conecte a dados para treinar e testar modelos para encontrar um que preveja com mais precisão um resultado futuro. Depois de executar experimentos para testar o modelo, você pode implantar e usá-lo em tempo real por meio de um ponto de extremidade da API Web.

Com o Azure Machine Learning, você pode:

- Criar um processo que define como obter dados, como lidar com casos de dados ausentes ou inválidos, como dividir os dados em um conjunto de treinamento ou de teste e como entregar os dados ao processo de treinamento.
- Treinar e avaliar modelos de previsão usando ferramentas e linguagens de programação familiares aos cientistas de dados.
- Criar pipelines que definem onde e quando executar os experimentos com uso intensivo de computação necessários para pontuar os algoritmos com base nos dados de treinamento e teste.
- Implantar o algoritmo de melhor desempenho como uma API para um ponto de extremidade para que ele possa ser consumido em tempo real por outros aplicativos.

Escolha o Azure Machine Learning quando os cientistas de dados precisarem de controle total sobre o design e o treinamento de um algoritmo usando os próprios dados. 

### Azure Cognitive Services

Os Serviços Cognitivos do Azure fornecem modelos de machine learning pré-criados que permitem que os aplicativos vejam, ouçam, falem, entendam e até mesmo comecem a raciocinar. Use os Serviços Cognitivos do Azure para resolver problemas gerais, como análise de texto quanto a sentimentos emocionais ou análise de imagens para reconhecer objetos ou rostos. Você não precisa de machine learning especial nem de conhecimento de ciência de dados para usar esses serviços. Os desenvolvedores acessam os Serviços Cognitivos do Azure por meio de APIs e podem facilmente incluir esses recursos em apenas algumas linhas de código.

Os Serviços Cognitivos do Azure podem ser divididos nas seguintes categorias:

- **Language services**: permita que seus aplicativos processem linguagem natural com scripts pré-criados, avalie sentimentos e aprenda a reconhecer o que os usuários desejam.
- **Speech services**: converta fala em texto e texto em fala natural. Traduza de um idioma para outro e habilite o reconhecimento e a verificação do locutor.
- **Vision services**: adicione funcionalidades de reconhecimento e identificação ao analisar imagens, vídeos e outros conteúdos visuais.
- **Decision services**: adicione recomendações personalizadas para cada usuário que melhorem automaticamente a cada vez que forem usadas, conteúdo moderado para monitorar e remover conteúdo ofensivo ou arriscado e detectar anormalidades nos dados de série temporal.

### Serviço de Bot do Azure

O Serviço de Bot do Azure e o Bot Framework são plataformas para a criação de agentes virtuais que compreendem e respondem a perguntas como um ser humano. Ele cria um agente virtual capaz de se comunicar de maneira inteligente com humanos. Nos bastidores, o bot que você cria usa outros serviços do Azure, como os Serviços Cognitivos do Azure, para entender o que as suas contrapartes humanas estão solicitando.

Os bots podem ser usados para deslocar tarefas simples e repetitivas, como fazer uma reserva de jantar ou coletar informações de perfil, para sistemas automatizados que podem não exigir mais intervenção humana direta. Os usuários conversam com os bots usando texto, cartões interativos e fala. Uma interação de bot pode ser uma pergunta e resposta rápidas, ou pode ser uma conversa sofisticada que fornece acesso aos serviços de forma inteligente.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte3)

---

## 🔸 <a name="Escolher_a_melhor_tecnologia_sem_servidor_do_Azure_para_seu_cenário_empresarial"></a>Escolher a melhor tecnologia sem servidor do Azure para seu cenário empresarial

A computação sem servidor é um termo usado para descrever um ambiente de execução configurado e gerenciado para você. Você só precisa especificar o que deseja que aconteça escrevendo código ou conectando e configurando componentes em um editor visual e, então, especificar as ações que disparam sua funcionalidade, como um temporizador ou uma solicitação HTTP. Seu código pode ser dimensionado instantaneamente para atender à demanda, e você só paga pelo uso real dele.

Depois de concluir este módulo, você poderá:

- Escolher a tecnologia de computação sem servidor que melhor atende ao seu cenário empresarial.

### Identificar as opções de produto

A ideia principal é que você não seja responsável por configurar nem por manter esse servidor. Você não precisará se preocupar em dimensioná-lo quando houver aumento da demanda, nem com interrupções. O fornecedor de nuvem cuida de todas as questões de manutenção e dimensionamento para você.

Você cria uma instância do serviço e adiciona seu código. Nenhuma configuração ou manutenção da infraestrutura é necessária, nem mesmo permitida. 

Você configura os aplicativos sem servidor para responder a eventos. Um evento pode ser um ponto de extremidade REST, um temporizador periódico ou até mesmo uma mensagem recebida de outro serviço do Azure.

Você é cobrado apenas pelos recursos que utiliza. Você nem precisa reservar recursos.

A computação sem servidor é normalmente usada para lidar com cenários de back-end. Em outras palavras, a computação sem servidor é responsável por enviar mensagens de um sistema para outro ou processar mensagens que foram enviadas de outros sistemas. 

### Azure Functions

Com o serviço do Azure Functions, você pode hospedar um único método ou função usando uma linguagem de programação popular na nuvem que é executada em resposta a um evento. Um exemplo de evento pode ser uma solicitação HTTP, uma nova mensagem em uma fila ou uma mensagem em um temporizador.

O Azure Functions é dimensionado automaticamente, e as cobranças são geradas apenas quando uma função é disparada. Essas qualidades tornam o Azure Functions uma escolha sólida quando a demanda é variável. 

Uma função do Azure é um ambiente sem estado (stateless). Essa função se comporta como se fosse reiniciada sempre que responde a um evento. Esse recurso é ideal para o processamento de dados de entrada. E, se o estado for necessário, a função poderá ser conectada a uma conta de armazenamento do Azure.

O Azure Functions pode executar tarefas de orquestração usando uma extensão chamada Durable Functions, que permite aos desenvolvedores encadear funções mantendo o estado.

### Azure Logic Apps

Os Aplicativos Lógicos são uma plataforma de desenvolvimento de código baixo/sem código hospedada como um serviço de nuvem. O serviço ajuda a automatizar e orquestrar tarefas, processos empresariais e fluxos de trabalho quando você precisa integrar aplicativos, dados, sistemas e serviços em empresas ou organizações.

Os Aplicativos Lógicos do Azure são projetados em um designer baseado na Web e podem executar a lógica disparada pelos serviços do Azure sem haver necessidade de codificação. Você cria um aplicativo vinculando gatilhos a ações com conectores. 

Existem ações lógicas como aquelas que você encontra na maioria das linguagens de programação. Exemplos de ações incluem trabalho com variáveis, loops e instruções de decisão e tarefas de análise e modificação de dados.

Para criar soluções de integração corporativa com Aplicativos Lógicos do Azure, você pode escolher em uma galeria crescente de mais de 200 conectores.

Se você não encontrar a ação ou o conector de que precisa, poderá criar o seu usando código personalizado.

O Azure Functions é um serviço de computação sem servidor, enquanto os Aplicativos Lógicos do Azure se destinam a ser um serviço de orquestração sem servidor. Embora você possa usar o Azure Functions para orquestrar um processo empresarial de longa execução que envolva diversas conexões, esse não era o caso de uso principal dele quando foi projetado.

Os dois serviços também têm preços diferentes. O preço do Azure Functions é baseado no número de execuções e no tempo de execução de cada uma. O preço dos Aplicativos Lógicos é baseado no número de execuções e no tipo de conectores que elas utilizam.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte3)

---

## 🔸 <a name=""></a> Escolha as melhores ferramentas para ajudar as organizações a criar soluções melhores

Depois de concluir este módulo, você será capaz de:

- Escolher os serviços e as ferramentas de processo de desenvolvimento de software que melhor atendem a cenários de negócios específicos.

A Microsoft criou um conjunto abrangente de ferramentas que ajudam as organizações a implementar práticas de DevOps, desenvolver soluções e economizar dinheiro no processo. Neste módulo, você vai aprender a escolher as ferramentas corretas para dar suporte a essas práticas.

## Entender as opções de produtos

O DevOps é um conceito que combina filosofias e práticas para auxiliar as equipes técnicas nos esforço para alcançar metas comuns. Para chegar a esse alinhamento, as organizações empregam práticas e processos que automatizam o desenvolvimento, a manutenção e a implantação contínuos dos sistemas de software. O objetivo é agilizar o lançamento de alterações de software, garantir a implantabilidade contínua do sistema e assegurar que todas as alterações atendam a um elevado padrão de qualidade.

O DevOps requer uma mudança de mentalidade fundamental de cima para baixo. As organizações não podem simplesmente instalar ferramentas de software nem adotar serviços e esperar obter todos os benefícios prometidos pelo DevOps.

As ferramentas da Microsoft permitem gerenciamento de código-fonte, CI/CD (integração contínua e entrega contínua) e automatizam a criação de ambientes de teste. 

### Azure DevOps Services

O Azure DevOps Services é um conjunto de serviços que lidam com cada fase do ciclo de vida do desenvolvimento de software.

- O **Azure Repos** é um repositório de código-fonte centralizado no qual profissionais de desenvolvimento de software, engenharia de DevOps e documentação podem publicar código para revisão e colaboração.
- O **Azure Boards** é um pacote de gerenciamento de projetos ágil que inclui quadros Kanban, relatórios e acompanhamento de ideias e trabalho, de epics de alto nível a itens de trabalho e problemas.
- O **Azure Pipelines** é uma ferramenta de automação do pipeline de CI/CD.
- O **Azure Artifacts** é um repositório para hospedagem de artefatos, como o código-fonte compilado, que podem ser inseridos nas etapas dos pipelines de teste ou de implantação.
- O **Azure Test Plans** é uma ferramenta de teste automatizado que pode ser usada em um pipeline de CI/CD para garantir a qualidade antes da liberação de um software.

O Azure DevOps é uma ferramenta madura, com um grande conjunto de recursos, que começou como um software para servidores local e evoluiu para uma oferta de SaaS (software como serviço) da Microsoft.

### GitHub e GitHub Actions

O GitHub é, sem dúvida, o repositório de código mais popular do mundo para software livre. O Git é uma ferramenta de gerenciamento de código-fonte descentralizada, e o GitHub é uma versão hospedada do Git que serve como o remoto primário. O GitHub se baseia no Git para fornecer serviços relacionados para coordenar trabalhos, relatar e discutir problemas, fornecer documentação e muito mais. Ele oferece a seguinte funcionalidade:

- Trata-se de um repositório de código-fonte compartilhado, incluindo ferramentas que permitem aos desenvolvedores executar revisões de código adicionando comentários e perguntas em uma exibição da Web do código-fonte antes que ele possa ser mesclado na base de código principal.
- Ele facilita o gerenciamento de projetos, incluindo quadros Kanban.
- Ele dá suporte para relatórios, discussões e acompanhamento de problemas.
- Ele conta com ferramentas de automação do pipeline de CI/CD.
- Ele inclui um wiki para documentação colaborativa.
- Ele pode ser executado na nuvem ou no local

Mais relevante para este módulo, o GitHub Actions permite a automação do fluxo de trabalho com gatilhos para muitos eventos do ciclo de vida. Um exemplo seria automatizar uma cadeia de ferramentas de CI/CD.

Uma cadeia de ferramentas é uma combinação de ferramentas de software que auxiliam na entrega, no desenvolvimento e no gerenciamento de aplicativos de software durante o ciclo de vida de desenvolvimento de um sistema. 
- A saída de uma ferramenta na cadeia de ferramentas é a entrada da próxima ferramenta na cadeia de ferramentas. 
- Funções típicas das ferramentas vão desde:
    - executar atualizações de dependência automatizadas até a criação e a configuração do software
    - a entrega dos artefatos de build a vários locais
    - a realização de testes e assim por diante.

Embora o Azure DevOps e o GitHub permitam repositórios de código públicos e privados, o GitHub tem um longo histórico com repositórios públicos e conta com a confiança de dezenas de milhares de proprietários de projetos de software livre.

- O GitHub é uma ferramenta mais leve do que o Azure DevOps, com foco em desenvolvedores individuais que contribuem para o código de software livre. 
- O Azure DevOps, por outro lado, é mais focado em desenvolvimento corporativo, com ferramentas de planejamento e gerenciamento de projeto mais pesadas e controle de acesso mais refinado.

> Suas opções não estão limitadas ao Azure DevOps Services ou ao GitHub e o GitHub Actions. Na prática, você pode misturar e combinar esses serviços conforme necessário. Por exemplo, você pode usar repositórios GitHub com Azure Boards para acompanhamento de item de trabalho.

### Azure DevTest Labs

O Azure DevTest Labs fornece um meio automatizado de gerenciar o processo de criação, configuração e remoção de VMs (máquinas virtuais) que contêm builds de seus projetos de software. Dessa maneira, desenvolvedores e testadores podem executar testes em uma variedade de ambientes e builds. E isso não fica limitado às VMs. Tudo o que você pode implantar no Azure por meio de um modelo do ARM pode ser provisionado pelo DevTest Labs. O provisionamento de ambientes de laboratório pré-criados com as ferramentas e as configurações necessárias já instaladas economiza muito tempo para desenvolvedores e profissionais de garantia de qualidade.

Suponha que você precise testar um novo recurso em uma versão antiga de um sistema operacional. O Azure DevTest Labs pode configurar tudo automaticamente após a solicitação. Depois que o teste for concluído, os DevTest Labs poderão desligar e desprovisionar a VM, o que economiza dinheiro quando ela não está em uso. A fim de controlar custos, a equipe de gerenciamento pode restringir quantos laboratórios podem ser criados, por quanto tempo eles são executados e assim por diante.

No entanto, você pode automatizar o provisionamento de novos laboratórios como parte de uma cadeia de ferramentas usando o GitHub Actions ou o Azure Pipelines.

O GitHub funciona em um modelo simples de permissões de leitura/gravação para cada recurso. Já o Azure DevOps tem um conjunto muito mais granular de permissões que possibilita às organizações refinar quem pode executar a maioria das operações em todo o conjunto de ferramentas.

Embora o GitHub tenha itens de trabalho, problemas e um quadro Kanban, o gerenciamento de projeto e os relatórios são as áreas de excelência do Azure DevOps. O Azure DevOps é altamente personalizável, o que permite que um administrador adicione campos personalizados para capturar metadados e outras informações junto com cada item de trabalho. Por outro lado, o recurso de Problemas do GitHub usa marcações como o principal meio de ajudar uma equipe a categorizar os problemas.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte3)

---

## 🔸 <a name="">Escolha_as_melhores_ferramentas_para_gerenciar_e_configurar_seu_ambiente_do_Azure</a> Escolha as melhores ferramentas para gerenciar e configurar seu ambiente do Azure

Depois de concluir este módulo, você poderá:

- Escolher as ferramentas de gerenciamento do Azure que atendem melhor às necessidades e aos desafios técnicos de sua organização.

Usando as ferramentas de gerenciamento, os administradores, desenvolvedores e gerentes do Azure podem interagir com o ambiente de nuvem para executar tarefas como:

- Implantação de dezenas ou centenas de recursos de cada vez.
- Configuração programática de serviços individuais.
- Exibição de relatórios avançados sobre uso, integridade, custos e muito mais.

### Identificar as opções de produto

Em termos gerais, há duas categorias amplas de ferramentas de gerenciamento: ferramentas visuais e ferramentas baseadas em código.

As ferramentas visuais fornecem acesso completo e de fácil visualização a todas as funcionalidades do Azure. No entanto, as ferramentas visuais podem não ser tão úteis quando você tenta configurar uma grande implantação de recursos com interdependências e opções de configuração.

Quando você tenta instalar e configurar rapidamente recursos do Azure, uma ferramenta baseada em código geralmente é a melhor opção. Embora possa levar algum tempo para entender os comandos e parâmetros certos primeiro, depois de terem sido inseridos, eles podem ser salvos em arquivos e usados repetidamente conforme a necessidade. Além disso, o código que executa a instalação e configuração pode ser armazenado, ter a versão controlada e ser mantido junto com o código-fonte do aplicativo em uma ferramenta de gerenciamento de código-fonte como o Git. Essa abordagem para gerenciar recursos de hardware e de nuvem que os desenvolvedores usam quando escrevem código do aplicativo é conhecida como infraestrutura como código.

Há duas abordagens de infraestrutura como código: código imperativo e declarativo. 
- O código imperativo detalha cada etapa individual que deve ser executada para alcançar um resultado desejado. 
- O código declarativo detalha apenas um resultado desejado e permite que um interpretador decida como alcançar melhor esse resultado. 

Essa distinção é importante porque as ferramentas baseadas em código declarativo podem fornecer uma abordagem mais robusta para a implantação de dezenas ou centenas de recursos de maneira simultânea e confiável.

### O portal do Azure

O portal do Azure fornece uma interface gráfica do usuário amigável para exibir todos os serviços que você está usando, criar serviços, configurar seus serviços e exibir relatórios. A portal do Azure é como a maioria dos usuários experimenta o Azure primeiro. 

### O aplicativo móvel do Azure

O aplicativo móvel do Azure fornece acesso do iOS e do Android aos recursos do Azure quando você está longe do seu computador. Com ele, você pode:

- Monitorar a integridade e o status de seus recursos do Azure.
- Verificar se há alertas, diagnosticar e corrigir problemas rapidamente e reiniciar um aplicativo Web ou VM (máquina virtual).
- Executar comandos da CLI do Azure ou do Azure PowerShell para gerenciar seus recursos do Azure.

### Azure PowerShell

O Azure PowerShell é um shell com o qual os desenvolvedores, DevOps e profissionais de TI podem executar comandos chamados cmdlets (pronuncia-se command-lets). Esses comandos chamam a API REST do Azure para executar toda tarefa de gerenciamento possível no Azure. Os cmdlets podem ser executados de forma independente ou combinados em um arquivo de script e executados juntos para orquestrar:

- A configuração, desinstalação e manutenção de rotina de um único recurso ou de vários recursos conectados.
- A implantação de uma infraestrutura inteira, que pode conter dezenas ou centenas de recursos, de um código imperativo.

O Windows PowerShell ajudou as organizações de TI com foco no Windows a automatizar muitas de suas operações locais durante anos, e essas organizações criaram um grande catálogo de cmdlets e scripts personalizados, além de acumular experiência.

### A CLI do Azure

A interface de linha de comando CLI do Azure é um programa executável com o qual um desenvolvedor, DevOps profissional ou profissional de TI pode executar comandos no Bash. Os comandos chamam a API REST do Azure para executar toda tarefa de gerenciamento possível no Azure. Você pode executar os comandos de maneira independente ou combinados em um script e executados juntos na configuração, remoção e manutenção de rotina de um único recurso ou de um ambiente inteiro.

A principal diferença é a sintaxe usada. Se você já domina o PowerShell ou o Bash, pode usar a ferramenta que preferir.

### Modelos de ARM

Embora seja possível escrever um código imperativo no Azure PowerShell ou na CLI do Azure para configurar e remover um recurso do Azure ou orquestrar uma infraestrutura contendo centenas de recursos, há um modo mais adequado de implementar essa funcionalidade.

Ao usar os modelos do ARM (modelos do Azure Resource Manager), você pode descrever os recursos que deseja usar em um formato JSON declarativo. O benefício é que todo o modelo do ARM é verificado antes de algum código ser executado para fazer com que os recursos sejam criados e conectados corretamente. Em seguida, o modelo orquestra a criação desses recursos em paralelo. Ou seja, se você precisar de 50 instâncias do mesmo recurso, todas as 50 instâncias serão criadas ao mesmo tempo.

No fim das contas, o desenvolvedor, o DevOps profissional ou o profissional de TI precisa apenas definir o estado desejado e a configuração de cada recurso no modelo do ARM e o modelo fará o resto. Os modelos podem até mesmo executar scripts do PowerShell e Bash antes ou depois da configuração de um recurso.

Ao contrário da CLI do Azure e do PowerShell, os modelos do ARM (modelos do Azure Resource Manager) definem os requisitos de infraestrutura em seu aplicativo para implantações repetíveis. Embora os modelos do ARM não se destinem a cenários pontuais, é possível usá-los para essa finalidade. No entanto, para cenários únicos, você pode preferir ferramentas mais ágeis como PowerShell, scripts da CLI do Azure ou o portal do Azure.

Os modelos do ARM podem incluir scripts do PowerShell e/ou da CLI do Azure, o que lhe dará a capacidade de utilizar scripts para tarefas que podem não ser possíveis com o próprio modelo do ARM.

O portal do Azure pode executar a maioria (se não todas) das ações administrativas e de gerenciamento. Se você está apenas aprendendo a usar o Azure e/ou precisa configurar e gerenciar recursos com pouca frequência (ou prefere uma interface visual para exibir relatórios), faz sentido tirar proveito da apresentação visual que o portal do Azure oferece.

É totalmente possível usar o PowerShell ou a CLI do Azure para configurar todos os recursos para uma implantação. No entanto, não há nenhuma etapa de validação nessas ferramentas. Se um script encontrar um erro, os recursos de dependência não podem ser revertidos facilmente, as implantações acontecem em série e apenas algumas operações são idempotentes.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte3)

---

## 🔸 <a name="Escolher_o_melhor_serviço_de_monitoramento_para_visibilidade_insight_e_mitigação_de_interrupções"></a> Escolher o melhor serviço de monitoramento para visibilidade, insight e mitigação de interrupções

Os sistemas de software modernos em execução na nuvem são complexos, e obter visibilidade sobre a integridade e o desempenho de seu ambiente de hospedagem de aplicativos em todas as suas camadas de serviços é desafiador. Felizmente, a Microsoft oferece várias soluções que podem ajudar você a reagir rapidamente a interrupções, pesquisar problemas intermitentes, otimizar o uso e ser proativo no tratamento de futuros tempos de inatividade planejados.

Depois de concluir este módulo, você poderá:

- Escolher o serviço de monitoramento em nuvem que melhor atende aos desafios comerciais de sua empresa.

### Identificar suas opções de produto

Todas as empresas que usam a nuvem têm várias perguntas ou preocupações básicas.

- Estamos usando a nuvem corretamente? Podemos obter mais desempenho dos nossos gastos com a nuvem?
- Estamos gastando mais do que precisamos?
- Nossos sistemas estão protegidos adequadamente?
- Qual é o grau de resiliência dos nossos recursos? Se passássemos por uma interrupção regional, poderíamos fazer failover para outra região?
- Como é possível diagnosticar e corrigir problemas que ocorrem de modo intermitente?
- Como podemos determinar rapidamente a causa de uma interrupção?
- Como podemos aprender sobre o tempo de inatividade planejado?

Felizmente, ao usar uma combinação de soluções de monitoramento no Azure, você pode:

- Obter respostas, insights e alertas para ajudar a garantir que tenha otimizado o uso da nuvem.
- Verificar a causa raiz de problemas não planejados.
- Preparar-se antecipadamente para interrupções planejadas.

### Opções do produto

Em um alto nível, há três ofertas principais de monitoramento do Azure, cada uma voltada a um público-alvo e a um caso de uso específicos e fornecendo um conjunto diversificado de ferramentas, serviços, APIs programáticas e muito mais.

### Azure Advisor

O Azure Advisor avalia seus recursos do Azure e faz recomendações para ajudar a melhorar a confiabilidade, a segurança e o desempenho, alcançar a excelência operacional e reduzir os custos. O Assistente foi projetado para ajudar você a poupar tempo na otimização da nuvem. O serviço de recomendação inclui ações sugeridas que você pode adotar imediatamente, adiar ou ignorar.

As recomendações estão disponíveis por meio do portal do Azure e da API, e é possível configurar notificações para alertar você sobre novas recomendações.

Quando você estiver no portal do Azure, o painel do Azure Advisor exibirá recomendações personalizadas para todas as suas assinaturas, e você poderá usar filtros para selecionar recomendações de serviços, grupos de recursos ou assinaturas específicas. As recomendações são divididas em cinco categorias:

- **Confiabilidade**: usada para garantir e aprimorar a continuidade dos seus aplicativos comercialmente críticos.
- **Segurança**: usada para detectar ameaças e vulnerabilidades que podem levar a violações de segurança.
- **Desempenho**: usado para aprimorar a velocidade de seus aplicativos.
- **Custo**: usado para otimizar e reduzir seus gastos gerais com o Azure.
- **Excelência operacional**: usada para ajudar você a obter eficiência de processo e fluxo de trabalho, gerenciamento de recursos e melhores práticas de implantação.

### Azure Monitor

O Azure Monitor é uma plataforma para coleta, análise, visualização e potencial execução de ações com base dos dados de registro em log e de métrica de todo o ambiente do Azure e local.

![identify-product-options](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/monitoring-fundamentals/media/2-identify-product-options-01.png)

- À esquerda fica uma lista das fontes dos dados de registro em log e de métrica que podem ser coletados em cada camada na arquitetura do aplicativo, indo do aplicativo ao sistema operacional e à rede.
- No centro, é possível ver como os dados de registro em log e de métrica são armazenados em repositórios centrais.
- À direita, os dados são usados de várias maneiras. 
    - Você pode exibir o desempenho histórico e em tempo real em cada camada da arquitetura ou informações agregadas e detalhadas. 
    - Os dados são exibidos em diferentes níveis para públicos-alvo diferentes. 
    - É possível exibir relatórios de alto nível no painel do Azure Monitor ou criar modos de exibição personalizados usando consultas do Power BI e do Kusto.

Além disso, os dados podem ser usados para ajudar você a reagir a eventos críticos em tempo real, por meio de alertas entregues às equipes por SMS, email etc.

Outra opção é usar limites a fim de disparar a funcionalidade de dimensionamento automático para aumentar ou reduzir conforme a demanda.

Alguns produtos populares, como o **Application Insights** do Azure, um serviço para envio de informações de telemetria do código-fonte do aplicativo para o Azure, usam o Azure Monitor nos bastidores. Com o Application Insights, os desenvolvedores de aplicativos podem aproveitar a poderosa plataforma de análise de dados no Azure Monitor para ter insights aprofundados sobre as operações de um aplicativo e diagnosticar erros sem ter que esperar que um usuário os relate.

### Azure Service Health

A Integridade do Serviço do Azure fornece uma exibição personalizada da integridade dos serviços, regiões e recursos do Azure dos quais você depende. O site status.azure.com, que exibe apenas os principais problemas que afetam amplamente os clientes do Azure, não fornece o panorama completo. 

Você pode configurar alertas que ajudam a fazer a triagem de interrupções e manutenção planejada. Após uma interrupção, a Integridade do Serviço fornece relatórios oficiais de incidentes, chamados de RCAs (root cause analyses), que podem ser compartilhados com os stakeholders.

O Service Health ajuda você a ficar atento a vários tipos de evento:

- **Problemas de serviço** são problemas no Azure, como interrupções, que afetam você no momento. Você pode analisar detalhadamente o impacto em serviços e regiões, atualizações de suas equipes de engenharia e encontrar maneiras de compartilhar e acompanhar as informações mais recentes.

- Os eventos de **manutenção planejada** podem afetar sua disponibilidade. Você pode analisar detalhadamente os serviços, as regiões e os detalhes afetados para mostrar como um evento afetará você e o que é necessário fazer. No caso raro em que uma reinicialização seja necessária, o Service Health permite que você escolha quando realizar a manutenção para minimizar o tempo de inatividade.

- Os **Health advisories** são problemas que exigem que você aja para evitar a interrupção do serviço, incluindo descontinuações de serviço e alterações significativas. Os comunicados de integridade são anunciados com antecedência para permitir que você se planeje.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte3)

---

# ☁️ <a name="parte4"></a> Parte 4: Descrever os recursos gerais de segurança de rede e segurança

Ter uma boa estratégia de segurança é essencial no mundo digital atual. Cada aplicativo e serviço, seja local ou na nuvem, precisa ser projetado tendo a segurança em mente. A segurança precisa ocorrer no nível do aplicativo, no nível dos dados e no nível da rede.

1. [Proteger contra ameaças à segurança no Azure](#Proteger_contra_ameaças_à_segurança_no_Azure)
2. [Conectividade de rede segura no Azure](#Conectividade_de_rede_segura_no_Azure)

Depois de concluir este módulo, você poderá:

- Fortalecer sua postura de segurança e se proteger contra ameaças usando a Central de Segurança do Azure.
- Coletar dados de segurança de várias fontes diferentes e atuar sobre eles usando o Azure Sentinel.
- Armazenar e acessar informações confidenciais (como senhas e chaves de criptografia) com segurança no Azure Key Vault.
- Gerenciar servidores físicos dedicados para hospedar suas VMs do Azure para Windows e Linux usando o Host Dedicado do Azure.

## 🔸 <a name="Proteger_contra_ameaças_à_segurança_no_Azure"></a> Proteger-se contra ameaças à segurança usando Azure Security Center

A Central de Segurança do Azure é um serviço de monitoramento que fornece visibilidade da postura de segurança em todos os serviços, tanto no Azure quanto localmente. O termo postura de segurança se refere a políticas e controles de segurança cibernética, bem como à sua capacidade de prever, impedir e responder com sucesso às ameaças de segurança.

A Central de Segurança pode:

- Monitorar as configurações de segurança das cargas de trabalho locais e na nuvem.
- Aplicar automaticamente as configurações de segurança obrigatórias aos novos recursos à medida que ficarem online.
- Fornecer recomendações de segurança baseadas nas configurações, nos recursos e nas redes atuais.
- Monitorar continuamente os recursos e realizar avaliações de segurança automáticas para identificar possíveis vulnerabilidades antes que elas possam ser exploradas.
- Usar machine learning para detectar e bloquear a instalação de malwares em VMs (máquinas virtuais) e em outros recursos. Você também pode usar os controles de aplicativo adaptáveis (adaptive application controls) para definir regras que listam os aplicativos permitidos a fim de verificar se somente os aplicativos que você permitir serão executados.
- Detectar e analisar possíveis ataques de entrada e investigar ameaças e qualquer atividade pós-violação que possa ter ocorrido.
- Fornecer controle de acesso just-in-time para as portas de rede. Isso reduz a superfície de ataque, garantindo que a rede só permita o tráfego exigido por você, no momento necessário.

### Entender a postura de segurança

### O que é a classificação de segurança?

A classificação de segurança é uma medida da postura de segurança de uma organização.

A classificação de segurança é baseada em controles de segurança ou grupos de recomendações de segurança relacionadas. A pontuação é baseada no percentual de controles de segurança que você atende. Quanto mais controles de segurança você atender, maior será a pontuação recebida. Sua pontuação melhora quando você corrige todas as recomendações para um recurso dentro de um controle.

![single-secure-score-via-ui](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/protect-against-security-threats-azure/media/2-single-secure-score-via-ui-602159ab.png)

De um painel centralizado na Central de Segurança do Azure, as organizações podem monitorar e trabalhar na segurança dos recursos do Azure, como identidades, dados, aplicativos, dispositivos e infraestrutura.

A classificação de segurança ajuda você a:

- Relatar o estado atual da postura de segurança da organização.
- Melhorar a postura de segurança fornecendo capacidade de descoberta e de visibilidade, além de diretrizes e controle.
- Comparar com parâmetros de comparação e estabelecer KPIs (indicadores chave de desempenho).

### Proteção contra ameaças

A Central de Segurança inclui funcionalidades avançadas de defesa de nuvem para VMs, segurança de rede e integridade de arquivo. 

- **Just-in-time VM access**. Esse acesso bloqueia por padrão o tráfego para portas de rede específicas de VMs, mas permite o tráfego por um período especificado quando um administrador o solicita e aprova.
- **Adaptive application controls**. Em segundo plano, a Central de Segurança usa machine learning para examinar os processos em execução em uma VM. Ela cria regras de exceção para cada grupo de recursos que contém as VMs e fornece recomendações. Esse processo fornece alertas que informam a empresa sobre aplicativos não autorizados em execução em suas VMs.
- **Adaptive network hardening**. A Central de Segurança pode monitorar os padrões de tráfego de Internet das VMs e comparar esses padrões com as configurações atuais de NSG (network security group) da empresa. Em seguida, a Central de Segurança pode recomendar que os NSGs sejam bloqueados ainda mais e fornecer etapas de correção.
- **File integrity monitoring** Também pode-se configurar o monitoramento de alterações em arquivos importantes no Windows e no Linux, de configurações do Registro, de aplicativos e de outros aspectos que possam indicar um ataque de segurança.

### Responder a alertas de segurança

Pode-se usar a Central de Segurança para ter uma visão centralizada de todos os alertas de segurança. Com isso, a empresa pode ignorar falsos alertas, investigar mais a fundo, corrigir alertas manualmente ou usar uma resposta automatizada com uma automação de fluxo de trabalho.

A automação do fluxo de trabalho usa os Aplicativos Lógicos do Azure e os conectores da Central de Segurança. O aplicativo lógico pode ser disparado por um alerta de detecção de ameaças ou por uma recomendação da Central de Segurança, filtrada por nome ou pela severidade. Em seguida, você pode configurar o aplicativo lógico para executar uma ação, como enviar um email ou postar uma mensagem em um canal do Microsoft Teams.

## Detectar e responder a ameaças de segurança usando o Azure Sentinel

O gerenciamento da segurança em grande escala pode se beneficiar de um sistema de SIEM (security information and event management) dedicado. O sistema de SIEM agrega dados de segurança de várias fontes diferentes (contanto que essas fontes sejam compatíveis com um formato padrão aberto de registro em log). Ele também fornece recursos de detecção e resposta a ameaças.

O Azure Sentinel é o sistema de SIEM baseado em nuvem da Microsoft. Ele usa análise de segurança e análise de ameaças inteligentes.

O Azure Sentinel permite que você:

- **Coletar dados de nuvem em escala** - Colete dados de todos os usuários, dispositivos, aplicativos e infraestrutura, tanto locais quanto de várias nuvens.
- **Detectar ameaças não detectadas anteriormente** - Minimize falsos positivos usando a análise abrangente e a inteligência contra ameaças da Microsoft.
- **Investigar ameaças com inteligência artificial** - Examine atividades suspeitas em escala, aproveitando a longa experiência em segurança cibernética da Microsoft.
- **Responder a incidentes rapidamente** - Use a orquestração e a automação internas para tarefas comuns.

### Conectar suas fontes de dados

O Azure Sentinel é compatível com várias fontes de dados, que podem ser analisadas em busca de eventos de segurança. Essas conexões são gerenciadas por conectores internos ou por APIs e formatos de log padrão do setor.
 
- **Conectar soluções da Microsoft** - Os conectores fornecem integração em tempo real para serviços como as soluções de Proteção contra Ameaças da Microsoft, as fontes do Microsoft 365 (incluindo o Office 365), o Azure Active Directory e o Windows Defender Firewall.
- **Conectar outros serviços e soluções** - Há conectores disponíveis para serviços e soluções comuns de terceiros, incluindo AWS CloudTrail, Citrix Analytics (Security), Sophos XG Firewall, VMware Carbon Black Cloud e Okta SSO.
- **Conectar fontes de dados padrão do setor** - O Azure Sentinel dá suporte a dados de outras fontes que usam o padrão de mensagens CEF (Common Event Format), o Syslog ou a API REST.

### Detectar ameaças

A **Built in analytics** usa modelos criados pela equipe de analistas e especialistas em segurança da Microsoft com base em ameaças conhecidas, em vetores de ataque comuns e nas cadeias de escalonamento de atividades suspeitas. Esses modelos podem ser personalizados e pesquisar em todo o ambiente por qualquer atividade que pareça suspeita. Alguns modelos usam a análise comportamental de machine learning, que se baseia em algoritmos proprietários da Microsoft.

A **Custom analytics** são regras que você cria para pesquisar critérios específicos em seu ambiente. Você pode visualizar o número de resultados que a consulta geraria (com base nos eventos de log anteriores) e definir uma agenda para a execução da consulta. Você também pode definir um limite de alerta.

Com o grafo de investigação, a empresa pode analisar informações de entidades conectadas diretamente ao alerta e ver consultas de exploração comuns para ajudar a orientar a investigação.

![investigate-incidents](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/protect-against-security-threats-azure/media/3-investigate-incidents-54765923.png)

A empresa também usará as Azure Monitor Workbooks do Azure Monitor para automatizar as respostas a ameaças. Por exemplo, eles podem definir um alerta que procura endereços IP mal-intencionados que acessam a rede, além de criar uma Workbook que realiza as seguintes etapas:

- Quando o alerta for disparado, abra um tíquete no sistema de gerenciamento de tíquetes de TI.
- Envie uma mensagem ao canal de operações de segurança do Microsoft Teams ou do Slack para verificar se os analistas de segurança estão cientes do incidente.
- Envie todas as informações do alerta para o administrador de rede sênior e para o administrador de segurança. A mensagem de email inclui dois botões de opção do usuário: Bloquear ou Ignorar.

Quando um administrador escolhe Bloquear, o endereço IP é bloqueado no firewall e o usuário é desabilitado no Azure Active Directory. Quando um administrador escolhe Ignorar, o alerta é fechado no Azure Sentinel e o incidente é fechado no sistema de gerenciamento de tíquetes de TI.

A Workbook continua sendo executada após receber uma resposta dos administradores.

As Workbook podem ser executadas manualmente ou automaticamente quando uma regra dispara um alerta.

## Configurar e gerenciar segredos usando o Azure Key Vault

O Azure Key Vault é um serviço de nuvem centralizado para armazenar segredos do aplicativo em um só local centralizado. Ele oferece acesso seguro a informações confidenciais fornecendo controle de acesso e funcionalidades de registro em log.

O Azure Key Vault pode ajudar você a:

- **Manage secrets** - Você pode usar o Key Vault para armazenar tokens, senhas, certificados, chaves de API e outros segredos e controlar com segurança o acesso a eles.
- **Gerenciar chaves de criptografia** - Você pode usar o Key Vault como uma solução de gerenciamento de chaves. O Key Vault facilita a criação e o controle das chaves de criptografia usadas para criptografar os dados.
- **Gerenciar certificados SSL/TLS** - O Key Vault permite provisionar, gerenciar e implantar certificados SSL/TLS públicos e privados para recursos do Azure e recursos internos.
- **Armazenar segredos com o suporte de HSMs (hardware security modules)** - Esses segredos e chaves podem ser protegidos por software ou por HSMs validados pelo FIPS 140-2 Nível 2.

Os benefícios de usar o Key Vault incluem:

- **Segredos de aplicativos centralizados** - A centralização do armazenamento de segredos de aplicativos permite que você controle a distribuição e reduz as chances de vazamento acidental de segredos.
- **Chaves e segredos armazenados com segurança** - O Azure usa algoritmos, comprimentos de chave e HSMs padrão do setor. O acesso ao Key Vault exige autenticação e autorização adequadas.
- **Monitoramento e controle de acesso** - Usando o Key Vault, você pode monitorar e controlar o acesso aos segredos de aplicativos.
- **Administração simplificada de segredos de aplicativos** O Key Vault facilita o registro e a renovação de certificados de CAs (autoridades de certificação) públicas. Você também pode escalar verticalmente e replicar o conteúdo dentro das regiões e usar ferramentas padrão para o gerenciamento de certificados.
- **Integração com outros serviços do Azure** - Você pode integrar o Key Vault com contas de armazenamento, registros de contêiner, hubs de eventos e muitos outros serviços do Azure. Então, esses serviços podem referenciar com segurança os segredos armazenados no Key Vault.

Na prática, há várias maneiras de adicionar segredos ao – e ler segredos do – Key Vault. Você pode usar o portal do Azure, a CLI do Azure ou o Azure PowerShell. Usando sua linguagem de programação favorita, seus aplicativos também podem acessar com segurança os segredos necessários.

## Hospedar suas máquinas virtuais do Azure em servidores físicos dedicados usando o Azure Dedicated Host

No Azure, as VMs (máquinas virtuais) são executadas em hardware compartilhado gerenciado pela Microsoft. Embora o hardware subjacente seja compartilhado, suas cargas de trabalho de VM são isoladas das cargas de trabalho executadas por outros clientes do Azure.

Algumas organizações precisam aderir à conformidade regulatória que exige que elas sejam o único cliente usando o computador físico que hospeda as máquinas virtuais.

O Host Dedicado do Azure:

- Fornece visibilidade e controle sobre a infraestrutura de servidor que está executando as VMs do Azure.
- Ajuda a endereçar os requisitos de conformidade implantando as cargas de trabalho em um servidor isolado.
- Permite que você escolha o número de processadores, as funcionalidades do servidor, a série de VMs e os tamanhos de VM dentro do mesmo host.

### Considerações de disponibilidade para o Host Dedicado

Depois que um host dedicado é provisionado, o Azure o atribui ao servidor físico no datacenter de nuvem da Microsoft.

Para alta disponibilidade, você pode provisionar vários hosts em um grupo de hosts e implantar suas VMs nesse grupo. VMs em hosts dedicados também podem aproveitar o controle de manutenção. Esse recurso permite controlar quando ocorrem atualizações de manutenção regulares, dentro de uma janela ininterrupta de 35 dias.

### Considerações de preço

Você é cobrado pelo host dedicado, independentemente do número de VMs implantadas. O preço do host é baseado na família, no tipo (tamanho do hardware) e na região da VM.

O licenciamento de software, o armazenamento e o uso de rede são cobrados separadamente do host e das VMs. 

### Resumo

Neste módulo, você aprendeu sobre os serviços do Azure relacionados à segurança. Confira abaixo um breve resumo:

- A Central de Segurança do Azure fornece visibilidade da postura de segurança em todos os serviços, tanto no Azure quanto localmente.
- O Azure Sentinel agrega dados de segurança de várias fontes diferentes e fornece funcionalidades adicionais para a detecção de – e a resposta a – ameaças.
- O Azure Key Vault armazena os segredos dos aplicativos (como senhas, chaves de criptografia e certificados) em um só local centralizado.
- O Host Dedicado do Azure fornece servidores físicos dedicados para hospedar as VMs do Azure para Windows e Linux.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte4)

---

## 🔸 <a name="Conectividade_de_rede_segura_no_Azure"></a> Conectividade de rede segura no Azure

Depois de concluir este módulo, você poderá:

- Identificar as camadas que compõem uma estratégia de defesa em profundidade.
- Explicar como o Firewall do Azure possibilita o controle do tráfego permitido na rede.
- Configurar grupos de segurança de rede para filtrar o tráfego de rede proveniente dos recursos do Azure e destinado a eles em uma Rede Virtual do Microsoft Azure.
- Explicar como a Proteção contra DDoS do Azure ajuda a proteger os recursos do Azure contra ataques de DDoS.

Cada aplicativo e serviço, seja local ou na nuvem, precisa ser projetado tendo a segurança em mente. Há coisas demais em risco. Por exemplo, um ataque de negação de serviço pode impedir que os clientes acessem seu site ou seus serviços e impedir que você faça negócios. Seu site também poderia ser desfigurado, causando danos à sua reputação. Uma violação de dados seria ainda pior, pois poderia arruinar uma confiança arduamente conquistada, além de causar danos pessoais e financeiros consideráveis.

### O que é defesa profunda (defense in depth)?

O objetivo da defesa profunda é proteger as informações e impedir que elas sejam roubadas por pessoas que não estão autorizadas a acessá-las.

Uma estratégia de defesa em profundidade usa uma série de mecanismos para reduzir o avanço de um ataque que busca obter acesso não autorizado aos dados.

### Camadas da defesa em profundidade

Você pode visualizar a defesa em profundidade como um conjunto de camadas, com os dados a serem protegidos no centro.

![defense-depth](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/secure-network-connectivity-azure/media/2-defense-depth.png)

Cada camada fornece proteção, de modo que se uma camada for violada, uma camada seguinte já estará em vigor para impedir a exposição adicional. Essa abordagem elimina a dependência de qualquer camada única de proteção. Ela desacelera um ataque e fornece telemetria de alerta sobre a qual as equipes de segurança podem agir, seja automática ou manualmente.

Aqui está uma breve visão geral da função de cada camada:

- A camada de segurança física é a primeira linha de defesa para proteger o hardware de computação no datacenter.
- A camada de identidade e acesso controla o acesso à infraestrutura e ao controle de alterações.
- A camada de perímetro usa a proteção contra DDoS (ataque de negação de serviço distribuído) para filtrar ataques em grande escala antes que eles possam causar uma negação de serviço para os usuários.
- A camada de rede limita a comunicação entre recursos por meio de controles de acesso e segmentação.
- A camada de computação protege o acesso a máquinas virtuais.
- A camada de aplicativo ajuda a garantir que os aplicativos estejam seguros e livres de vulnerabilidades de segurança.
- A camada de dados controla o acesso aos dados corporativos e do cliente que você precisa proteger.

O Azure fornece ferramentas e recursos de segurança em todos os níveis do conceito de defesa em profundidade.

#### Segurança física

Proteger fisicamente o acesso a edifícios e controlar o acesso ao hardware de computação no datacenter é a primeira linha de defesa.

Com a segurança física, a intenção é fornecer garantias físicas contra o acesso aos ativos. Essas garantias asseguram que outras camadas não possam ser ignoradas e que a perda ou o roubo seja tratado de maneira adequada. A Microsoft usa vários mecanismos de segurança físicos em seus datacenters de nuvem.

#### Identidade e acesso

Nessa camada, é importante:

- Controle o acesso à infraestrutura e o controle de alterações.
- Usar o SSO (logon único) e a autenticação multifator.
- Faça a auditoria de eventos e alterações.
- A camada de identidade e acesso refere-se a garantir que as identidades estejam seguras, o acesso seja concedido apenas ao que é necessário e os eventos de entrada e as alterações sejam registrados.

#### Perímetro

Nessa camada, é importante:

- Usar a Proteção contra DDoS para filtrar ataques em grande escala antes que eles possam afetar a disponibilidade de um sistema para os usuários.
- Use firewalls de perímetro para identificar e alertar sobre ataques maliciosos contra a rede.

#### Rede

Nessa camada, é importante:

- Limite a comunicação entre os recursos.
- Negue por padrão.
- Restringir o acesso à Internet de entrada e limitar o acesso de saída quando apropriado.
- Implemente a conectividade segura com as redes locais.

Essa camada concentra-se em limitar a conectividade de rede entre todos os recursos para permitir apenas o necessário. Ao limitar essa comunicação, você reduz o risco de uma disseminação de ataques para outros sistemas na rede.

#### Computação

Nessa camada, é importante:

- Proteger o acesso às máquinas virtuais.
- Implementar o Endpoint Protection em dispositivos e manter os sistemas atualizados e com patches.

Malware, sistemas sem patches e sistemas sem proteção adequada abrem o ambiente para ataques. Essa camada tem como foco garantir que os recursos de computação estejam seguros e que haja controles adequados em vigor para minimizar os problemas de segurança.

#### Aplicativo

Nessa camada, é importante:

- Verificar se os aplicativos estão seguros e livres de vulnerabilidades.
- Armazene os segredos de aplicativos confidenciais em uma mídia de armazenamento seguro.
- Faça com que a segurança seja um requisito de design em todo o desenvolvimento do aplicativo.

A integração da segurança no ciclo de vida de desenvolvimento do aplicativo ajuda a reduzir o número de vulnerabilidades introduzidas no código. Toda equipe de desenvolvimento deve garantir que seus aplicativos sejam seguros por padrão.

#### Dados

Em quase todos os casos, os invasores estão em busca de dados:

- Armazenados em um banco de dados.
- Armazenados em disco em máquinas virtuais.
- Armazenados em aplicativos SaaS (software como serviço), como o Office 365.
- Gerenciados por meio do armazenamento em nuvem.

Quem armazena dados e controla o acesso a eles é responsável por garantir que estejam protegidos adequadamente. É comum que requisitos regulatórios determinem os controles e os processos que precisam estar em vigor para garantir a confidencialidade, a integridade e a disponibilidade dos dados.

### Postura de segurança

Sua postura de segurança é a capacidade da sua organização de se proteger e responder a ameaças de segurança. Os princípios comuns usados para definir uma postura de segurança são confidencialidade, integridade e disponibilidade, conhecidas coletivamente como CIA.

#### Confidencialidade

O princípio de privilégios mínimos significa restringir o acesso a informações somente a indivíduos com acesso explícito, apenas no nível de que precisam para realizar seu trabalho. Essas informações incluem proteção de senhas de usuário, conteúdo de email e níveis de acesso para aplicativos e infraestrutura subjacente.

#### Integridade

Impedir alterações não autorizadas a informações:

- Em repouso: quando estão armazenadas.
- Em trânsito: quando estão sendo transferidas de um local para outro, incluindo de um computador local para a nuvem.

Uma abordagem comum adotada na transmissão de dados é o remetente criar uma impressão digital exclusiva dos dados usando um algoritmo de hash unidirecional. O hash é enviado para o receptor juntamente com os dados. O destinatário recalcula o hash dos dados e o compara com o original, a fim de garantir que os dados não tenham sido perdidos nem modificados em trânsito.

#### Disponibilidade

Garantir que os serviços estejam funcionando e possam ser acessados somente por usuários autorizados. Os ataques de negação de serviço são projetados para degradar a disponibilidade de um sistema, afetando seus usuários.

## Proteger redes virtuais usando o Firewall do Azure

Um firewall é um dispositivo de segurança de rede que monitora o tráfego de rede de entrada e saída e decide se deve permitir ou bloquear o tráfego específico com base em um conjunto definido de regras de segurança. Você pode criar regras de firewall que especificam intervalos de endereços IP específicos. Somente clientes com endereços IP concedidos dentro desses intervalos têm permissão para acessar o servidor de destino. Em geral, as regras de firewall também podem incluir informações de porta e protocolo de rede específicas.

### O que é o Firewall do Azure?

O Firewall do Azure é um serviço de segurança de rede gerenciado e baseado em nuvem que ajuda a proteger recursos nas redes virtuais do Azure. Uma rede virtual é semelhante a uma rede tradicional que você operaria em seu datacenter. É um bloco de construção fundamental para sua rede privada que permite que máquinas virtuais e outros recursos de computação se comuniquem com segurança entre si, pela Internet e pelas redes locais.

![firewall-overview](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/secure-network-connectivity-azure/media/3-firewall-overview.png)

O Firewall do Azure é um firewall com estado. Um firewall com estado analisa o contexto completo de uma conexão de rede, não apenas um pacote individual de tráfego de rede. O Firewall do Azure apresenta alta disponibilidade e escalabilidade de nuvem irrestrita.

O Firewall do Azure fornece um local central para criar, impor e registrar políticas de conectividade de aplicativo e rede em assinaturas e redes virtuais. O Firewall do Azure usa um endereço IP público estático (inalterável) para seus recursos de rede virtual, o que permite que os firewalls externos identifiquem o tráfego proveniente de sua rede virtual. O serviço é integrado ao Azure Monitor para habilitar o registro em log e a análise.

O Firewall do Azure fornece muitos recursos, incluindo:

- Alta disponibilidade interna.
- Escalabilidade de nuvem irrestrita.
- Regras de filtragem de entrada e saída.
- Suporte a DNAT (conversão de endereços de rede de destino) de entrada.
- O registro em log do Azure Monitor.

Normalmente, você implanta o Firewall do Azure em uma rede virtual central para controlar o acesso geral à rede.

Com o Firewall do Azure, você pode configurar:

- Regras de aplicativo que definem FQDNs (nomes de domínio totalmente qualificados - fully qualified domain names) que podem ser acessados em uma sub-rede.
- Regras de rede que definem endereço de origem, protocolo, porta de destino e endereço de destino.
- Regras de NAT (conversão de endereços de rede - Network Address Translation) que definem endereços IP de destino e portas para converter solicitações de entrada.

O Gateway de Aplicativo do Azure também fornece um firewall, chamado de WAF (firewall do aplicativo Web). O WAF fornece proteção de entrada centralizada para seus aplicativos Web contra explorações e vulnerabilidades comuns. O Azure **Front Door** e a **Azure Content Delivery Network** também fornecem serviços de WAF.

## Proteger contra ataques de DDoS usando a Proteção contra DDoS do Azure

Qualquer empresa de grande porte pode ser alvo de um ataque de rede em grande escala. Nesta parte, você aprende como a Proteção contra DDoS do Azure (camada de serviço Standard) ajuda a proteger os recursos do Azure contra ataques de DDoS. 

### O que são ataques de DDoS?

Um ataque de negação de serviço distribuído tenta sobrecarregar e esgotar os recursos de um aplicativo, tornando-o lento ou sem resposta para usuários legítimos. Os ataques de DDoS podem ter como alvo qualquer recurso acessível publicamente pela Internet, incluindo sites.

Ao combinar a Proteção contra DDoS com práticas recomendadas de design de aplicativo, você ajuda a fornecer uma defesa contra ataques de DDoS. A Proteção contra DDoS usa a escala e a elasticidade da rede global da Microsoft para levar capacidade de mitigação de DDoS a todas as regiões do Azure. O serviço de Proteção contra DDoS ajuda a proteger seus aplicativos do Azure analisando e descartando o tráfego de DDoS na borda da rede do Azure, antes que ele possa afetar a disponibilidade do serviço.

A Proteção contra DDoS identifica a tentativa do invasor de sobrecarregar a rede e bloqueia o tráfego adicional, garantindo que o tráfego nunca atinja os recursos do Azure. O tráfego legítimo dos clientes ainda flui para o Azure sem nenhuma interrupção do serviço.

- A Proteção contra DDoS também pode ajudar você a gerenciar seu consumo de nuvem. 
- Ao executar localmente, você tem um número fixo de recursos de computação. Porém, na nuvem, a computação elástica lhe permite escalar horizontalmente a implantação de modo automático para atender à demanda. Um ataque de DDoS desenvolvido de modo inteligente pode fazer com que você aumente sua alocação de recurso, gerando despesas desnecessárias. 
- A Proteção contra DDoS Standard ajuda a garantir que a carga de rede que você processa reflita o uso do cliente. Você também pode receber crédito por qualquer custo acumulado para recursos escalados horizontalmente durante um ataque de DDoS.

A Proteção contra DDoS oferece estas camadas de serviço:

### Basic

A camada de serviço Básica é automaticamente habilitada de modo gratuito como parte da sua assinatura do Azure.

O monitoramento de tráfego sempre ativo e a mitigação em tempo real de ataques comuns no nível de rede fornecem os mesmos tipos de proteção usados pelos serviços online da Microsoft. A camada de serviço Básica garante que a própria infraestrutura do Azure não seja afetada durante um ataque de DDoS em grande escala.

A rede global do Azure é usada para distribuir e atenuar o tráfego de ataques entre regiões do Azure.

### Standard

A camada de serviço Standard fornece funcionalidades de mitigação adicionais ajustadas especificamente para os recursos de Rede Virtual do Azure. A Proteção contra DDoS Standard é relativamente fácil de habilitar e não requer alterações aos aplicativos.

A camada Standard fornece monitoramento de tráfego sempre ativo e mitigação em tempo real de ataques comuns no nível de rede. Ela oferece as mesmas defesas que os serviços online da Microsoft usam.

As políticas de proteção são ajustadas por meio do monitoramento de tráfego dedicado e de algoritmos de aprendizado de máquina. As políticas são aplicadas a endereços IP públicos associados aos recursos implantados em redes virtuais, como o Azure Load Balancer e o Gateway de Aplicativo.

A rede global do Azure é usada para distribuir e atenuar o tráfego de ataques entre regiões do Azure.

### Que tipos de ataques a Proteção contra DDoS pode ajudar a evitar?

A camada de serviço Standard pode ajudar a evitar:

- Ataques volumétricos - A meta desse ataque é inundar a camada de rede com uma quantidade significativa de tráfego aparentemente legítimo.
- Ataques de protocolo - Esses ataques renderizam um destino inacessível explorando uma vulnerabilidade na pilha de protocolos das camadas 3 e 4.
- Ataques de camada de recurso (camada de aplicativo) (somente com o firewall do aplicativo Web) - Esses ataques são direcionados a pacotes de aplicativo Web para interromper a transmissão de dados entre os hosts. Você precisa de um WAF (firewall do aplicativo Web) para proteger-se contra ataques L7. A Proteção contra DDoS Standard protege o WAF contra ataques volumétricos e de protocolo.

## Filtrar o tráfego de rede usando grupos de segurança de rede

### O que são os grupos de segurança de rede do Azure?

Um grupo de segurança de rede permite filtrar o tráfego de rede proveniente dos recursos do Azure e destinado a eles em uma rede virtual do Azure. Considere os NSGs como um firewall interno. Um NSG pode conter várias regras de segurança de entrada e saída que permitem a filtragem do tráfego para e de recursos por endereço IP de origem e de destino, porta e protocolo.

Quando você cria um grupo de segurança de rede, o Azure cria uma série de regras padrão para fornecer um nível de linha de base de segurança. Você não pode remover as regras padrão, mas pode substituí-las criando regras com prioridades mais altas.

## Combinar os serviços do Azure para criar uma solução de segurança de rede completa

Ao considerar uma solução de segurança do Azure, considere todos os elementos da defesa em profundidade.

Aqui estão algumas recomendações sobre como combinar os serviços do Azure para criar uma solução de segurança de rede completa.

### Proteger a camada do perímetro

A camada do perímetro refere-se a proteger os recursos da sua organização contra ataques baseados em rede. Identificar esses ataques, alertar as equipes de segurança apropriadas e eliminar seu impacto são aspectos importantes para manter sua rede segura. Para fazer isso:

- Use a Proteção contra DDoS do Azure para filtrar ataques em grande escala antes que eles possam causar uma negação de serviço para os usuários.
- Use firewalls de perímetro com o Firewall do Azure para identificar e alertar sobre ataques maliciosos contra a rede.

### Proteger a camada de rede

Essa camada concentra-se em limitar a conectividade de rede entre todos os recursos para permitir apenas o necessário. Segmente seus recursos e use os controles de nível de rede para restringir a comunicação apenas ao que é necessário.

Ao restringir a conectividade, você reduz o risco de movimento lateral em toda a rede contra um ataque. Use grupos de segurança de rede para criar regras que definem a comunicação de entrada e saída permitida nessa camada. Aqui estão algumas práticas recomendadas:

- Limitar a comunicação entre os recursos segmentando sua rede e configurando os controles de acesso.
- Negue por padrão.
- Restringir o acesso à Internet de entrada e limite a saída quando apropriado.
- Implemente a conectividade segura com as redes locais.

### Combinar serviços

Você pode combinar os serviços de segurança e de rede do Azure para gerenciar a segurança da rede e fornecer maior proteção em camadas.

#### Grupos de segurança de rede e Firewall do Azure

O Firewall do Azure complementa a funcionalidade dos grupos de segurança de rede. Juntos, eles fornecem uma melhor segurança de rede de defesa aprofundada.

Os grupos de segurança de rede fornecem filtragem de tráfego de camada de rede distribuída para limitar o tráfego aos recursos dentro das redes virtuais em cada assinatura.

O Firewall do Azure é um firewall de rede como serviço totalmente centralizado e com estado. Ele fornece proteção no nível da rede e do aplicativo em diferentes assinaturas e redes virtuais.

#### Firewall do aplicativo Web do Gateway de Aplicativo do Azure e Firewall do Azure

O WAF (firewall do aplicativo Web) é um recurso do Gateway de Aplicativo do Azure que fornece aos seus aplicativos Web proteção de entrada centralizada contra explorações e vulnerabilidades comuns.

O Firewall do Azure fornece:

- Proteção de entrada para protocolos não HTTP/S (por exemplo, RDP, SSH e FTP).
- Proteção em nível de rede de saída para todas as portas e protocolos.
- Proteção em nível de aplicativo para HTTP/S de saída.

Combiná-los fornece mais camadas de proteção.

### Resumo

Neste módulo, você aprendeu sobre algumas das maneiras de proteger o tráfego de rede no Azure e no seu datacenter local.

Proteção completa é o tema recorrente. Pense na segurança como um interesse de várias camadas e de vários vetores. As ameaças vêm de locais que não esperamos e podem vir com uma força surpreendente.

- O Firewall do Azure é um serviço de segurança de rede gerenciado e baseado em nuvem que ajuda a proteger recursos nas redes virtuais do Azure.
- Uma rede virtual do Azure é semelhante a uma rede tradicional que você operaria em seu datacenter. Ela permite que máquinas virtuais e outros recursos de computação se comuniquem com segurança entre si, pela Internet e por redes locais.
- Um NSG (grupo de segurança de rede) permite que você filtre o tráfego de rede de e para recursos do Azure em uma rede virtual.
- A Proteção contra DDoS do Azure ajuda a proteger os recursos do Azure contra ataques de DDoS.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte4)

---

# ☁️ <a name="parte5"></a> Parte 5: Princípios Básicos do Microsoft Azure: descrever recursos de identidade, governança, privacidade e conformidade

Com o aumento do trabalho remoto, de práticas de BYOD (bring your own device), do uso de aplicativos móveis e aplicativos de nuvem, o limite de segurança primário foi transferido dos firewalls e controles de acesso físico para a identidade.

Entender quem está usando seus sistemas e o que eles têm permissão para fazer são essenciais para manter seus dados protegidos contra invasores. Para se manter organizado, gerenciar custos e atender às suas metas de conformidade, você precisa de uma boa estratégia de governança de nuvem.

1. [Proteger o acesso aos seus aplicativos usando os serviços de identidade do Azure](#Proteger_o_acesso_aos_seus_aplicativos_usando_os_serviços_de_identidade_do_Azure)
2. [Criar uma estratégia de governança de nuvem no Azure](#Criar_uma_estratégia_de_governança_de_nuvem_no_Azure)
3. [Conheça os padrões de privacidade, conformidade e proteção de dados do Azure](#Conheça_os_padrões_de_privacidade_conformidade_e_proteção_de_dados_do_Azure)

## 🔸 <a name="Proteger_o_acesso_aos_seus_aplicativos_usando_os_serviços_de_identidade_do_Azure"></a> Proteger o acesso aos seus aplicativos usando os serviços de identidade do Azure

Saiba como o Azure Active Directory ajuda a gerenciar e proteger identidades. Além disso, veja como o logon único, a autenticação multifator e o Acesso Condicional permitem que os usuários acessem com segurança recursos e aplicativos na intranet e em redes públicas.

Depois de concluir este módulo, você poderá:

- Explicar a diferença entre autenticação e autorização.
- Descrever como o Azure Active Directory fornece gerenciamento de identidade e acesso.
- Explicar a função que o SSO (single sign-on), a autenticação multifator e o Acesso Condicional desempenham no gerenciamento da identidade do usuário.

A identidade tornou-se o novo limite de segurança primário. Provar com precisão que alguém é um usuário válido do sistema, com um nível apropriado de acesso, é crítico para manter o controle dos dados. Agora, é mais comum que essa camada de identidade seja o alvo dos ataques, e não a rede.

Dois conceitos fundamentais que você precisa entender ao falar sobre identidade e acesso são autenticação (AuthN) e autorização (AuthZ). A autenticação e a autorização dão suporte a todo o restante. Elas ocorrem em sequência no processo de identidade e acesso.

**Autenticação** é o processo de estabelecer a identidade de uma pessoa ou serviço que deseja acessar um recurso. Ela envolve o ato de solicitar credenciais legítimas de uma parte e fornece a base para criação de uma entidade de segurança para controle de acesso e identidade. Estabelece se o usuário é quem diz ser.

A **autenticação** estabelece a identidade do usuário, enquanto a autorização é o processo de estabelecer o nível de acesso que uma pessoa ou um serviço autenticado tem. Especifica quais dados podem ser acessados e que a pessoa ou serviço pode fazer com eles.

### O que é o Azure Active Directory?

O Active Directory está relacionado ao Azure AD, mas há algumas diferenças importantes.

O Azure AD é o serviço de gerenciamento de acesso e identidade baseado em nuvem da Microsoft. Com o Azure AD, você controla as contas de identidade, mas a Microsoft garante que o serviço esteja disponível globalmente.

Quando você conecta o Active Directory ao Azure AD, a Microsoft pode ajudar a protegê-lo detectando tentativas de conexão suspeitas sem custo adicional. Por exemplo, o Azure AD pode detectar tentativas de conexão de locais inesperados ou dispositivos desconhecidos.

O Azure AD é para:

**Administradores de TI** - Os administradores podem usar o Azure AD para controlar o acesso a aplicativos e recursos com base em seus requisitos de negócios.

**Desenvolvedores de aplicativos** - Os desenvolvedores podem usar o Azure AD para fornecer uma abordagem baseada em padrões para adicionar funcionalidade a aplicativos que eles criam, como adicionar a funcionalidade de SSO a um aplicativo ou habilitar um aplicativo para trabalhar com as credenciais existentes de um usuário.

**Usuários** - Os usuários podem gerenciar suas identidades. Por exemplo, a redefinição de senha por autoatendimento permite que os usuários alterem ou redefinam a senha sem envolvimento de um administrador de TI nem do suporte técnico.

**Assinantes do serviço online** - Os assinantes do Microsoft 365, do Microsoft Office 365, do Azure e do Microsoft Dynamics CRM Online já estão usando o Azure AD.
    - Um locatário é uma representação de uma organização. Normalmente, um locatário é separado de outros locatários e tem a própria identidade. Cada locatário do Microsoft 365, do Office 365, do Azure e do Dynamics CRM Online é automaticamente um locatário do Azure AD.

### Que serviços o Azure AD fornece?

O Azure AD fornece serviços como:

- **Autenticação** - Inclui verificar a identidade para acessar aplicativos e recursos. Também inclui fornecer funcionalidades como redefinição de senha por autoatendimento, autenticação multifator, uma lista personalizada de senhas banidas e serviços de bloqueio inteligente.

**Logon Único** - O SSO permite que você se lembre de apenas um nome de usuário e uma senha para acessar vários aplicativos. Uma única identidade é vinculada a um usuário, o que simplifica o modelo de segurança. À medida que os usuários trocam de funções ou saem de uma organização, as modificações de acesso são vinculadas àquela identidade, o que reduz consideravelmente o esforço necessário para alterar ou desabilitar contas.

**Gerenciamento de aplicativos** - Você pode gerenciar seus aplicativos de nuvem e locais usando o Azure AD. Recursos como Proxy de Aplicativo, aplicativos SaaS, o portal Meus Aplicativos (também conhecido como Painel de Acesso) e o logon único proporcionam uma experiência do usuário aprimorada.

**Gerenciamento de dispositivos** - Além das contas de pessoas individuais, o Azure AD dá suporte ao registro de dispositivos. O registro permite que os dispositivos sejam gerenciados por meio de ferramentas como o Microsoft Intune. Também permite que políticas de Acesso Condicional baseadas no dispositivo restrinjam tentativas de acesso somente às provenientes de dispositivos conhecidos, independentemente da conta de usuário solicitante.

O Azure AD ajuda os usuários a acessar recursos internos e externos.

Os recursos externos podem incluir Microsoft Office 365, o portal do Azure e milhares de outros aplicativos SaaS.

Os recursos internos podem incluir aplicativos em sua rede corporativa e intranet, juntamente com qualquer aplicativo de nuvem desenvolvido em sua organização.

### O que é o logon único?

O logon único permite que um usuário entre uma vez e use essa credencial para acessar vários recursos e aplicativos de provedores diferentes.

Um número maior de identidades significa mais senhas para se lembrar e alterar. As políticas de senha podem variar entre aplicativos. Quanto mais senhas um usuário precisa gerenciar, maior o risco de um incidente de segurança relacionado às credenciais.

Se um usuário sai de uma organização, o rastreamento de todas essas identidades e a garantia de que elas estão desabilitadas podem ser um desafio. 

Usar SSO para contas torna mais fácil para os usuários gerenciar suas identidades e aumenta as funcionalidades de segurança.

### Como posso conectar o Active Directory ao Azure AD?

Há algumas maneiras de conectar sua instalação existente do Active Directory ao Azure AD. Talvez o método mais popular seja usar o Azure AD Connect.

O Azure AD Connect sincroniza identidades de usuário entre o Active Directory local e o Azure AD. O Azure AD Connect sincroniza alterações entre os dois sistemas de identidade, o que permite que você use recursos como SSO, autenticação multifator e redefinição de senha por autoatendimento em ambos. A redefinição de senha por autoatendimento impede que os usuários usem senhas comprometidas conhecidas.

![azure-ad-connect](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/secure-access-azure-identity-services/media/3-azure-ad-connect.png)

### O que é a autenticação multifator?

Autenticação multifator é um processo em que o usuário deve fornecer uma forma adicional de identificação durante o processo de entrada. Exemplos incluem um código no telefone celular ou uma verificação de impressão digital.

A autenticação multifator fornece segurança adicional para as identidades, exigindo dois ou mais elementos para a autenticação completa.

Esses elementos se enquadram em três categorias:

- Algo que o usuário sabe - Pode ser um endereço de email e uma senha.
- Algo que o usuário tem - Pode ser um código enviado para o telefone celular do usuário.
- Algo que o usuário é - Normalmente é algum tipo de propriedade biométrica, como uma impressão digital ou verificação de detecção facial usada em muitos dispositivos móveis.

A autenticação multifator aumenta a segurança de identidade, limitando o impacto da exposição da credencial (por exemplo, nomes de acesso e senhas roubados). 

Esses serviços fornecem funcionalidades de Autenticação Multifator do Azure AD:

**Azure Active Directory** - A edição gratuita do Azure Active Directory habilita a Autenticação Multifator do Azure AD para administradores com o nível de acesso de administrador global por meio do aplicativo Microsoft Authenticator, de chamada telefônica ou de código SMS. Você também pode impor a Autenticação Multifator do Azure AD para todos os usuários por meio apenas do aplicativo Microsoft Authenticator habilitando padrões de segurança em seu locatário do Azure AD.

**O Azure Active Directory Premium (licenças P1 ou P2)** - permite uma configuração abrangente e granular da Autenticação Multifator do Azure AD por meio de políticas de Acesso Condicional

**Autenticação multifator para o Office 365** - Um subconjunto de funcionalidades da Autenticação Multifator do Azure AD faz parte da sua assinatura do Office 365.

### O que é Acesso Condicional?

O Acesso Condicional é uma ferramenta que o Azure Active Directory usa para permitir (ou negar) o acesso a recursos com base em sinais de identidade. Esses sinais incluem quem é o usuário, onde ele está e de qual dispositivo está solicitando acesso.

O acesso condicional ajuda os administradores de TI a:

- Capacitar os usuários a serem produtivos em qualquer lugar e sempre.
- Proteger os ativos da organização.

O Acesso Condicional também proporciona uma experiência de autenticação multifator mais granular para os usuários. Por exemplo, um segundo fator de autenticação poderá não ser solicitado se o usuário estiver em uma localização conhecida. No entanto, ele poderá ser solicitado se os sinais de conexão do usuário forem incomuns ou se o usuário estiver em uma localização inesperada.

Durante a conexão, o acesso condicional coleta sinais do usuário, toma decisões com base nesses sinais e impõe essa decisão, permitindo ou negando a solicitação de acesso ou solicitando uma resposta de autenticação multifator.

O acesso condicional é útil quando você precisa:

- Exigir autenticação multifator para acessar um aplicativo.
- Você pode configurar se todos os usuários precisam de autenticação multifator ou apenas determinados usuários, como administradores.
- Você também pode configurar se a autenticação multifator se aplica ao acesso de todas as redes ou apenas de redes não confiáveis.
- Exigir acesso a serviços somente por meio de aplicativos cliente aprovados.
    - Por exemplo, talvez você queira permitir que os usuários acessem os serviços do Office 365 usando um dispositivo móvel, desde que usem aplicativos cliente aprovados, como o aplicativo móvel do Outlook.
- Exigir que os usuários acessem seu aplicativo somente de dispositivos gerenciados.
    - Um dispositivo gerenciado é um dispositivo que atende aos seus padrões de segurança e conformidade.
- Bloquear o acesso de fontes não confiáveis, como o acesso de locais desconhecidos ou inesperados.

O acesso condicional vem com uma ferramenta What If, que ajuda a planejar e solucionar problemas de suas políticas de acesso condicional. Você pode usar essa ferramenta para modelar as políticas de Acesso Condicional propostas em tentativas de conexão recentes de seus usuários para ver qual teria sido o impacto se essas políticas tivessem sido habilitadas. 

A ferramenta What If permite que você teste as políticas de Acesso Condicional propostas antes de implementá-las.

Para usar o acesso condicional, você precisa de uma licença do Azure AD Premium P1 ou P2. Se você tiver uma licença do Microsoft 365 Business Premium, também terá acesso aos recursos de Acesso Condicional.

### Resumo

- A AuthN (autenticação) estabelece a identidade do usuário.
- A AuthZ (autorização) estabelece o nível de acesso que um usuário autenticado tem.
- O SSO (logon único) permite que um usuário entre uma vez e use essa credencial para acessar vários recursos e aplicativos.
- O Azure AD (Azure Active Directory) é um serviço de gerenciamento de identidade e acesso baseado em nuvem. O Azure AD permite que a organização controle o acesso a aplicativos e recursos com base em seus requisitos empresariais.
- A Autenticação Multifator do Azure AD fornece segurança adicional para as identidades, exigindo dois ou mais elementos para a autenticação completa. De modo geral, a autenticação multifator pode incluir algo que o usuário sabe, algo que o usuário tem e algo que o usuário é.
- O Acesso Condicional é uma ferramenta usada pelo Azure AD para permitir ou negar o acesso a recursos com base em sinais de identidade, como a localização do usuário.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte5)

---

## 🔸 <a name="Criar_uma_estratégia_de_governança_de_nuvem_no_Azure"></a> Proteger o acesso aos seus aplicativos usando os serviços de identidade do Azure

Saiba como acessar políticas, bloqueios de recursos e tags, além de descobrir como os serviços do Azure, como o Azure Policy e o Azure Blueprints, podem ajudar você a criar uma estratégia de governança de nuvem abrangente.

Depois de concluir este módulo, você poderá:

- Tomar decisões organizacionais sobre seu ambiente de nuvem usando o Cloud Adoption Framework para Azure.
- Definir quem pode acessar recursos de nuvem usando o controle de acesso baseado em função do Azure.
- Aplique um bloqueio de recurso para evitar a exclusão acidental dos recursos do Azure.
- Aplique marcas aos recursos do Azure para ajudar a descrever a finalidade deles.
- Controle e audite como os recursos são criados usando o Azure Policy.
- Habilite a governança em escala em várias assinaturas do Azure usando o Azure Blueprints.

O termo governança descreve o processo geral de estabelecer regras e políticas e garantir que elas sejam impostas.

Manter o controle sobre o seu ambiente garante que você permaneça em conformidade com:

- Padrões do setor, como o PCI DSS.
- Padrões corporativos ou organizacionais, como a garantia de que os dados da rede são criptografados.

A governança é mais benéfica quando você tem:

- Várias equipes de engenharia trabalhando no Azure.
- Várias assinaturas a serem gerenciadas.
- Requisitos regulatórios que precisam ser impostos.
- Padrões que precisam ser seguidos para todos os recursos de nuvem.

### Controlar o acesso a recursos de nuvem usando o controle de acesso baseado em função do Azure

É uma boa prática de segurança conceder aos usuários apenas os direitos de que precisam para executar o trabalho e somente aos recursos relevantes.

O Azure permite controlar o acesso por meio do RBAC do Azure (role-based control access).

O Azure fornece funções internas que descrevem regras de acesso comuns para os recursos de nuvem. Você também pode definir suas funções. Cada função tem um conjunto associado de permissões de acesso relacionadas a essa função. Quando você atribui indivíduos ou grupos a uma ou mais funções, eles recebem todas as permissões de acesso associadas.

O RBAC (controle de acesso baseado em função) é aplicado a um escopo, que é um recurso ou um conjunto de recursos ao qual esse acesso se aplica.

Os escopos incluem:

- Um grupo de gerenciamento (uma coleção de várias assinaturas).
- Uma assinatura única.
- Um grupo de recursos.
- Um recurso individual.

Quando você permite acesso a um escopo pai, essas permissões são herdadas por todos os escopos filho.

### Quando devo usar o RBAC do Azure?

Use o RBAC do Azure quando precisar:

- Permitir que um usuário gerencie VMs em uma assinatura e outro usuário gerencie redes virtuais.
- Permitir que um grupo de Administradores de Banco de Dados gerencie bancos de dados SQL em uma assinatura.
- Permitir que um usuário gerencie todos os recursos em um grupo de recursos, como máquinas virtuais, sites e sub-redes.
- Permitir que um aplicativo acesse todos os recursos em um grupo de recursos.

O RBAC do Azure é imposto em qualquer ação iniciada em um recurso do Azure que passa pelo Azure Resource Manager. 

**Resource Manager** é um serviço de gerenciamento que fornece um modo de organizar e proteger seus recursos de nuvem.

Normalmente, você acessa o Resource Manager no portal do Azure, no Azure Cloud Shell, no Azure PowerShell e na CLI do Azure. O RBAC do Azure não impõe permissões de acesso no nível do aplicativo nem dos dados. 

> A segurança do aplicativo precisa ser realizada pelo aplicativo.

O RBAC usa um modelo de permissão. Quando você recebe uma função, o RBAC permite que você execute determinadas ações, como leitura, gravação ou exclusão. 

Você pode aplicar o RBAC do Azure a uma pessoa ou a um grupo. Você também pode aplicar o RBAC do Azure a outros tipos de identidades especiais, como entidades de serviço e identidades gerenciadas. Esses tipos de identidade são usados por aplicativos e serviços para automatizar o acesso aos recursos do Azure.

Gerencie as permissões de acesso no painel Access control (IAM) no portal do Azure. Esse painel mostra quem tem acesso a qual escopo e quais funções se aplicam. Você também pode permitir ou remover o acesso nesse painel.

### Impedir alterações acidentais usando bloqueios de recursos

Um bloqueio de recurso (Resource Lock) impede que os recursos sejam excluídos ou alterados acidentalmente.

Mesmo com as políticas do controle de acesso baseado em função do Azure (RBAC do Azure) em vigor, ainda há um risco de que as pessoas com o nível correto de acesso possam excluir recursos de nuvem críticos. 

### Como fazer para gerenciar os bloqueios de recursos?

Gerencie os bloqueios de recursos no portal do Azure, no PowerShell, na CLI do Azure ou em um modelo do Azure Resource Manager.

Para ver, adicionar ou excluir bloqueios no portal do Azure, acesse a seção Configurações do painel Bloqueios de um recurso no portal do Azure.

Você pode aplicar bloqueios a uma assinatura, a um grupo de recursos ou a um recurso individual. É possível definir o nível de bloqueio como CanNotDelete ou ReadOnly.

- **CanNotDelete** significa que as pessoas autorizadas ainda podem ler e modificar um recurso, mas não podem excluir o recurso sem antes remover o bloqueio.
- **ReadOnly** significa que pessoas autorizadas podem ler um recurso, mas não podem excluir nem alterar o recurso. 

### Como fazer para excluir ou alterar um recurso bloqueado?

Embora o bloqueio ajude a evitar alterações acidentais, você ainda poderá fazer alterações seguindo um processo de duas etapas.

Para modificar um recurso bloqueado, primeiro, você precisará remover o bloqueio. Depois de remover o bloqueio, aplique qualquer ação que você tenha permissões para executar. 

### Combinar bloqueios de recursos com o Azure Blueprints

Para tornar o processo de proteção mais robusto, você pode combinar bloqueios de recursos com o Azure Blueprints. O Azure Blueprints permite que você defina o conjunto de recursos padrão de recursos do Azure necessário para a sua organização. Por exemplo, você pode definir um blueprint que especifica que determinado bloqueio de recurso precisa existir. O Azure Blueprints poderá substituir automaticamente o bloqueio de recurso se esse bloqueio for removido.

### Organizar seus recursos do Azure usando Tags

À medida que o seu uso de nuvem aumenta, passa a ser cada vez mais importante manter-se organizado. 

- Uma forma de organizar os recursos relacionados é colocá-los nas próprias assinaturas. 
- Use também grupos de recursos para gerenciar os recursos relacionados. 
- As marcas de recursos são outra maneira de organizar os recursos. 

As marcas fornecem informações extras ou metadados sobre os recursos. Esses metadados são úteis para:

- **Gerenciamento de recursos** - As tags permitem que você localize em recursos associados a cargas de trabalho, ambientes, unidades de negócios e proprietários específicos e realize ações nesses recursos.
- **Gerenciamento e otimização de recursos** - As tags permitem agrupar os recursos para que você possa relatar custos, alocar centros de custos internos, acompanhar orçamentos e prever o custo estimado.
- **Gerenciamento de operações** - As tags permitem que você agrupe os recursos de acordo com o grau de importância da disponibilidade deles para os seus negócios. Esse agrupamento ajuda você a formular SLAs (Contratos de Nível de Serviço). Um SLA é uma garantia de tempo de atividade ou desempenho acordada entre você e seus usuários.
- **Segurança** - As tags permitem que você classifique os dados pelo nível de segurança, como público ou confidencial.
- **Governança e conformidade regulatória** - As tags permitem que você identifique recursos que se alinham com os requisitos de conformidade regulatória ou de governança, como a ISO 27001. Elas também podem fazer parte dos seus esforços de imposição de padrões. Por exemplo, você pode exigir que todos os recursos sejam marcados com um proprietário ou um nome de departamento.
- **Automação e otimização de carga de trabalho** - As tags podem ajudar você a visualizar todos os recursos que participam de implantações complexas. Por exemplo, você pode marcar um recurso com o nome da carga de trabalho ou do aplicativo associado e usar um software como o Azure DevOps para executar tarefas automatizadas nesses recursos.

### Como fazer para gerenciar tags de recursos?

Você pode adicionar, modificar ou excluir tags de recursos por meio do PowerShell, da CLI do Azure, dos modelos do Azure Resource Manager, da API REST ou do portal do Azure.

Você também pode gerenciar tags usando o Azure Policy.

Por exemplo, você pode aplicar tags a um grupo de recursos, mas essas marcas não são aplicadas automaticamente aos recursos nesse grupo de recursos. Você pode usar o Azure Policy para fazer com que um recurso herde as mesmas tags do grupo de recursos pai. 

Use também o Azure Policy para impor regras e convenções de marcação. Por exemplo, exija que determinadas tags sejam adicionadas aos novos recursos à medida que eles forem provisionados. Defina também regras que reaplicam as tags removidas.

Tenha em mente que não é necessário impor a presença de uma tag específica em todos os recursos. Por exemplo, você pode decidir que apenas os recursos críticos tenham a tag Impact. Em seguida, todos os recursos não marcados não serão considerados críticos.

### Controlar e auditar seus recursos usando o Azure Policy

Como garantir que seus recursos permaneçam em conformidade? Você poderá receber um alerta se a configuração de um recurso for alterada?

O Azure Policy é um serviço do Azure que permite criar, atribuir e gerenciar políticas que controlam ou auditam os recursos. Essas políticas impõem regras diferentes sobre as configurações dos recursos, de modo que essas configurações permaneçam em conformidade com os padrões corporativos.

### Como o Azure Policy define as políticas?

O Azure Policy permite que você defina políticas individuais e grupos de políticas relacionadas, conhecidas como iniciativas.

O Azure Policy avalia seus recursos e realça os que não estão em conformidade com as políticas criadas por você. Ele também pode impedir a criação de recursos sem conformidade.

O Azure Policy vem com definições de iniciativa e política internas para Armazenamento, Rede, Computação, Central de Segurança e Monitoramento. Por exemplo, se você definir uma política que permita que apenas um determinado tamanho de SKU (stock-keeping unit - unidade de manutenção de estoque) para VMs (máquinas virtuais) seja usado em seu ambiente, essa política será invocada quando você criar VMs e sempre que você redimensionar as VMs existentes. O Azure Policy também avalia e monitora todas as VMs atuais do ambiente.

Em alguns casos, ele pode corrigir automaticamente os recursos e as configurações sem conformidade para garantir a integridade do estado dos recursos. Por exemplo, se todos os recursos de determinado grupo de recursos precisarem ser marcados com AppName e um valor igual a "SpecialOrders", o Azure Policy reaplicará automaticamente essa tag se ela estava ausente.

Além disso, o Azure Policy se integra ao Azure DevOps aplicando as políticas de pipeline de entrega e integração contínua que pertencem às fases pré e pós-implantação dos seus aplicativos.

A implementação de uma política no Azure Policy envolve três tarefas:

1. Criar uma definição da política.
2. Atribuir a definição aos recursos.
3. Examinar os resultados da avaliação.

### Tarefa 1. Criar uma definição da política

Uma definição de política expressa o que avaliar e qual ação será tomada. Por exemplo, você pode impedir que as VMs sejam implantadas em determinadas regiões do Azure. Você também pode auditar suas contas de armazenamento para confirmar se elas só aceitam conexões de redes permitidas.

Cada definição de política tem condições sob as quais ela é imposta. Uma definição de política também tem um efeito de acompanhamento que ocorre quando as condições são atendidas. 

Estes são alguns exemplos de definições de política:

- SKUs de máquina virtual permitidos Esta política permite que você especifique um conjunto de SKUs de VM que sua organização pode implantar.
- Locais permitidos Esta política permite que você restrinja os locais que sua organização pode especificar quando implanta recursos. Seu efeito é usado para impor seus requisitos de conformidade geográfica.
- A MFA deve ser habilitada nas contas com permissões de gravação na assinatura Essa política exige que a MFA (autenticação multifator) esteja habilitada em todas as contas de assinaturas com privilégios de gravação, a fim de impedir uma violação de contas ou de recursos.
- O CORS não deve permitir que todos os recursos tenham acesso aos seus aplicativos Web O CORS (compartilhamento de recurso entre origens) é um recurso HTTP que permite que um aplicativo Web em execução em um domínio acesse recursos em outro domínio. Por motivos de segurança, os navegadores da Web modernos restringem o cross-site scripting por padrão. Essa política permite que só os domínios necessários interajam com o aplicativo Web.
- As atualizações do sistema devem ser instaladas em seus computadores - Essa política permite que a Central de Segurança do Azure recomende atualizações ausentes do sistema de segurança nos seus servidores.

### Tarefa 2. Atribuir a definição aos recursos

Para implementar suas definições de política, atribua definições aos recursos. Uma atribuição de política é uma definição de política que ocorre em um escopo específico. Esse escopo pode ser um grupo de gerenciamento (uma coleção de várias assinaturas), uma assinatura única ou um grupo de recursos.

As atribuições de política são herdadas por todos os recursos filho no escopo. 

### Tarefa 3. Examinar os resultados da avaliação

Quando uma condição é avaliada em relação aos recursos existentes, cada recurso é marcado como em conformidade ou sem conformidade. Você pode examinar os resultados da política sem conformidade e executar qualquer ação necessária.

A avaliação de política ocorre uma vez por hora. Se você fizer alterações na definição de política e criar uma atribuição de política, essa política avaliará seus recursos dentro da próxima hora.

### O que são iniciativas do Azure Policy?

Uma iniciativa do Azure Policy é uma forma de agrupar políticas relacionadas. A definição de iniciativa contém todas as definições de política para ajudar a acompanhar seu estado de conformidade para atingir uma meta maior.

Por exemplo, o Azure Policy inclui uma iniciativa chamada Habilitar o Monitoramento na Central de Segurança do Azure. A meta dela é monitorar todas as recomendações de segurança disponíveis para todos os tipos de recursos do Azure na Central de Segurança do Azure.

Com essa iniciativa, as seguintes definições de política são incluídas:

- **Monitorar um banco de dados SQL não criptografado na Central de Segurança** - Essa política monitora servidores e bancos de dados SQL não criptografados.
- **Monitorar vulnerabilidades de SO na Central de Segurança** - Esta política monitora servidores que não atendem à linha de base de vulnerabilidade do sistema operacional configurado.
- **Monitorar o Endpoint Protection ausente na Central de Segurança** - Essa política monitora servidores que não têm um agente de proteção de ponto de extremidade instalado.

Na verdade, a iniciativa Habilitar o Monitoramento na Central de Segurança do Azure contém mais de 100 definições de política separadas.

O Azure Policy também inclui iniciativas que dão suporte a padrões de conformidade regulatória, como o HIPAA e a ISO 27001.

## Controlar várias assinaturas usando o Azure Blueprints

O que acontece quando seu ambiente de nuvem começa a crescer além de apenas uma assinatura? Como você pode escalar a configuração desses recursos, sabendo que eles precisam ser impostos para os recursos em novas assinaturas?

Em vez de ter que configurar recursos como o Azure Policy para cada nova assinatura, com o Azure Blueprints, você pode definir um conjunto repetível de ferramentas de governança e de recursos padrão do Azure necessário para a sua organização. Assim, as equipes de desenvolvimento podem criar e implementar rapidamente novos ambientes, sabendo que eles estão sendo criados de acordo com as especificações da organização, com um conjunto de componentes internos que aceleram as fases de desenvolvimento e implantação.

O Azure Blueprints orquestra a implantação de vários modelos de recursos e outros artefatos, como:

- Atribuições de função
- Atribuições de política
- Modelos do Azure Resource Manager
- Grupos de recursos

Ao formar uma equipe de centro de excelência em nuvem ou uma equipe de custodiantes da nuvem, essa equipe pode usar o Azure Blueprints para escalar as práticas de governança em toda a organização.

A implementação de um blueprint no Azure Blueprints envolve estas três etapas:

1. Criar um Azure Blueprint.
2. Atribuir o blueprint.
3. Acompanhar as atribuições de blueprint.

Com o Azure Blueprints, a relação entre a definição do blueprint (o que deve ser implantado) e a atribuição do blueprint (o que foi implantado) é preservada. Em outras palavras, o Azure cria um registro que associa um recurso ao blueprint que o define. Essa conexão ajuda você a acompanhar e auditar suas implantações.

Os blueprints também têm controle de versão. O controle de versão permite que você acompanhe e comente as alterações no blueprint.

### O que são artefatos de blueprint?

Cada componente na definição de blueprint é conhecido como um artefato.

É possível que os artefatos não tenham parâmetros adicionais (configurações). Um exemplo é a política Implantar detecção de ameaças nos servidores SQL, que não requer nenhuma configuração adicional.

Os artefatos também podem conter um ou mais parâmetros que você pode configurar. 

Você pode especificar o valor de um parâmetro ao criar a definição de blueprint ou atribuí-la a um escopo. Com isso, você pode manter um blueprint padrão, mas ter a flexibilidade de especificar os parâmetros de configuração relevantes em cada escopo no qual a definição é atribuída.

A ISO 27001 é um padrão que se aplica à segurança de sistemas de TI publicado pela Organização Internacional de Normalização

## Acelere sua jornada de adoção da nuvem usando o Cloud Adoption Framework para Azure

O Cloud Adoption Framework para Azure fornece diretrizes comprovadas para ajudar com a sua jornada de adoção da nuvem. O Cloud Adoption Framework ajuda você a criar e implementar as estratégias de negócios e de tecnologia necessárias para ter sucesso na nuvem.

o Cloud Adoption Framework consiste em ferramentas, documentação e práticas comprovadas. O Cloud Adoption Framework inclui estas fases:

- Definir sua estratégia.
- Criar um plano.
- Preparar sua organização.
- Adotar a nuvem.
- Controlar e gerenciar seus ambientes de nuvem.

![framework-stages](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/build-cloud-governance-strategy-azure/media/2-framework-stages-9b54ccbe.png)

### Definir sua estratégia

Aqui, você explicará por que está migrando para a nuvem e indicará o que deseja obter com a migração. Você precisa escalar seus negócios para atender à demanda ou alcançar novos mercados? Isso reduzirá os custos ou aumentará a agilidade dos negócios? Ao definir sua estratégia de negócios de nuvem, entenda a economia de nuvem, o impacto nos negócios, o tempo de retorno, o alcance global, o desempenho, entre outros.

1. **Definir e documentar suas motivações**: reunir-se com os stakeholders e a liderança pode ajudar você a explicar por que está migrando para a nuvem.
2. **Documentar os resultados dos negócios**: reúna-se com a liderança dos grupos de finanças, marketing, vendas e recursos humanos para ajudar você a documentar suas metas.
3. **Avalie as considerações financeiras**: avalie os objetivos e identifique o retorno esperado de um investimento específico.
4. **Entenda as considerações técnicas**: avalie as considerações técnicas por meio da seleção e da conclusão do seu primeiro projeto técnico.

### Criar um plano

Aqui, você criará um plano que mapeia suas metas ambiciosas para ações específicas. Um bom plano ajuda a garantir que os seus esforços sejam mapeados para os resultados de negócios desejados.

1. **Propriedade digital**: crie um inventário dos ativos digitais e das cargas de trabalho existentes que você pretende migrar para a nuvem.
2. **Alinhamento organizacional inicial**: verifique se as pessoas certas estão envolvidas nos seus esforços de migração, do ponto de vista técnico e da governança de nuvem.
3. **Plano de preparação de habilidades**: crie um plano que ajude os indivíduos a criar as habilidades de que precisam para operar na nuvem.
4. **Plano de adoção da nuvem**: crie um plano abrangente que reúne as equipes de desenvolvimento, operações e negócios em direção a uma meta de adoção da nuvem compartilhada.

### Preparar sua organização

1. **Guia de configuração do Azure**: Examine o Guia de Configuração do Azure para se familiarizar com as ferramentas e as abordagens necessárias para criar uma zona de destino.
2. **Zona de destino do Azure**: comece a criar as assinaturas do Azure que dão suporte a cada uma das principais áreas do seu negócio. Uma zona de destino inclui a infraestrutura de nuvem, bem como funcionalidades de governança, contabilidade e segurança.
3. **Expandir a zona de destino**: refine sua zona de destino para garantir que ela atende às suas necessidades de operações, governança e segurança.
4. **Melhores práticas**: comece com as práticas recomendadas e comprovadas para ajudar a garantir que seus esforços de migração para a nuvem sejam escalonáveis e possam ser mantidos.

### Adotar a nuvem

Aqui, você começará a migrar seus aplicativos para a nuvem. Ao longo do caminho, você poderá encontrar maneiras de modernizar seus aplicativos e criar soluções inovadoras que usam os serviços de nuvem.

O Cloud Adoption Framework divide essa fase em duas partes: migração e inovação.

### Migrar

1. **Migrar sua primeira carga de trabalho**: use o guia de migração do Azure para implantar seu primeiro projeto na nuvem.
2. **Cenários de migração**: use guias detalhados adicionais para explorar cenários de migração mais complexos.
3. **Melhores práticas**: dê uma olhada na lista de verificação de melhores práticas de migração para a nuvem do Azure para confirmar se você está seguindo as práticas recomendadas.
4. **Aprimoramentos de processo**: identifique maneiras de escalar o processo de migração, exigindo menos esforço.

### Inovar

1. **Consenso do valor comercial**: confirme se os investimentos em inovações agregam valor aos negócios e atendem às necessidades dos clientes.
2. **Guia de inovação do Azure**: use esse guia para acelerar o desenvolvimento e criar um MVP (produto mínimo viável) para a sua ideia.
3. **Melhores práticas**: confirme se o seu progresso é mapeado para as práticas recomendadas antes de prosseguir.
4. **Loops de comentários**: pergunte frequentemente aos seus clientes se você está criando algo de que eles precisam.

### Controlar e gerenciar seus ambientes de nuvem

Aqui, você começará a formar suas estratégias de governança e gerenciamento de nuvem. À medida que o estado da nuvem se altera ao longo do tempo, o mesmo ocorrerá com os processos e as políticas de governança da nuvem. Você precisará criar soluções resilientes que sejam constantemente otimizadas.

1. **Metodologia**: considere sua solução de estado final. Em seguida, defina uma metodologia que leve você incrementalmente das primeiras etapas à governança de nuvem completa.
2. **Parâmetro de comparação**: use a ferramenta **governance benchmark tool** de governança para avaliar o estado atual e o estado futuro e estabelecer uma visão para a aplicação da estrutura.
3. **Base de governança inicial**: crie um MVP que capture as primeiras etapas do plano de governança.
4. **Aprimorar a base de governança inicial**: adicione iterativamente controles de governança que resolvam os riscos tangíveis à medida que você progride rumo à solução de estado final.

### Gerenciar

1. **Estabelecer uma linha de base de gerenciamento**: defina seu compromisso mínimo com o gerenciamento de operações. Uma linha de base de gerenciamento é o conjunto mínimo de ferramentas e processos que devem ser aplicados a todos os ativos em um ambiente.
2. **Definir compromissos empresariais**: Documente as cargas de trabalho compatíveis para estabelecer compromissos operacionais com o negócio e entre em acordo sobre investimentos em gerenciamento de nuvem para cada carga de trabalho.
3. **Expandir a linha de base de gerenciamento**: aplique as práticas recomendadas para iterar pela linha de base de gerenciamento inicial.
4. **Operações avançadas e princípios de design**: para cargas de trabalho que exigem um nível mais alto de compromisso de negócios, execute uma análise mais profunda da arquitetura para cumprir seus compromissos de resiliência e confiabilidade.

## Criar uma estratégia de governança de assinatura

No início de qualquer implementação de governança de nuvem, você identifica uma estrutura de organização em nuvem que atende às suas necessidades de negócios. Esta etapa geralmente envolve a formação de uma equipe do centro de excelência na nuvem (também chamada de equipe de habilitação de nuvem ou uma equipe custodiante de nuvem). Essa equipe está capacitada para implementar práticas de governança de um local centralizado para toda a organização.

As equipes costumam iniciar a estratégia de governança do Azure no nível da assinatura. Há três aspectos principais a serem considerados ao criar e gerenciar assinaturas: cobrança, controle de acesso e limites de assinatura.

### Cobrança

Você pode criar um relatório de cobrança por assinatura. Caso você tenha vários departamentos e precise fazer um "estorno" dos custos da nuvem, uma solução possível é organizar as assinaturas por departamento ou por projeto.

As tags de recurso também podem ajudar. Quando você define quantas assinaturas são necessárias e como nomeá-las, leve em consideração seus requisitos internos de cobrança.

### Controle de acesso

Uma assinatura é um limite de implantação para os recursos do Azure. Cada assinatura é associada a um locatário do Azure Active Directory. Cada locatário fornece aos administradores a capacidade de configurar o acesso granular por meio de funções definidas usando o controle de acesso baseado em função do Azure.

Quando projetar a arquitetura da assinatura, leve em conta o fator de limite de implantação. Por exemplo, você precisa ter assinaturas separadas para ambientes de desenvolvimento e produção? Com assinaturas separadas, você pode controlar o acesso a cada um separadamente e isolar os recursos uns dos outros.

### Limites de assinatura

As assinaturas também têm algumas limitações de recursos. Por exemplo, o número máximo de circuitos do Azure ExpressRoute na rede por assinatura é 10. Esses limites devem ser considerados durante a fase de design. Se você precisar exceder esses limites, talvez seja necessário adicionar mais assinaturas. Se você atingir um limite rígido máximo, não haverá flexibilidade para aumentá-lo.

Os grupos de gerenciamento também estão disponíveis para auxiliar no gerenciamento de assinaturas. Um grupo de gerenciamento gerencia o acesso, as políticas e a conformidade em várias assinaturas do Azure.

## Resumo

A governança de nuvem exige uma boa coleta de requisitos e análise. A boa notícia é que o Cloud Adoption Framework para Azure pode ajudar você a definir e implementar sua estratégia de governança. Há vários serviços e recursos no Azure que dão suporte a esses esforços:

- O RBAC do Azure (controle de acesso baseado em função do Azure) permite que você crie funções que definem permissões de acesso.
- Os bloqueios de recursos impedem que os recursos sejam excluídos ou alterados acidentalmente.
- As marcas de recursos fornecem informações extras ou metadados sobre os recursos.
- O Azure Policy é um serviço do Azure que permite criar, atribuir e gerenciar políticas que controlam ou auditam os recursos.
- O Azure Blueprints permite que você defina um conjunto repetível de ferramentas de governança e de recursos padrão do Azure necessário para a sua organização.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte5)

---

## 🔸 <a name="Conheça_os_padrões_de_privacidade_conformidade_e_proteção_de_dados_do_Azure"></a> Conheça os padrões de privacidade, conformidade e proteção de dados do Azure

Neste módulo, você aprenderá sobre o compromisso da Microsoft com a privacidade e sobre como o Azure segue os padrões comuns de regulamentação e de conformidade.

Se sua organização for um departamento ou uma agência governamental ou se você precisar realizar implantações em regiões da China, você também aprenderá sobre alguns aspectos que não se aplicam a outros usuários do Azure.

De modo geral, conformidade significa obedecer a uma lei, um padrão ou um conjunto de diretrizes. Conformidade regulatória refere-se à disciplina e ao processo de garantir que uma empresa siga as leis impostas pelos órgãos governamentais.

Depois de concluir este módulo, você poderá:

- Explicar os tipos de ofertas de conformidade disponíveis no Azure.
- Acessar a Política de Privacidade, os Termos dos Serviços Online e o Adendo de Proteção de Dados da Microsoft para saber quais dados pessoais a Microsoft coleta, como a Microsoft os utiliza e para quais finalidades.
- Conhecer os padrões regulatórios e a conformidade do Azure com base na Central de Confiabilidade e na documentação de conformidade do Azure.
- Explicar as funcionalidades do Azure específicas para agências governamentais.

## Explorar termos e requisitos de conformidade

- O quanto o Azure mantém a conformidade com relação à manipulação de dados pessoais?
- O quanto cada um dos serviços individuais do Azure se mantém em conformidade?

Os serviços online da Microsoft são baseados em um conjunto comum de controles regulatórios e de conformidade. Considere um controle como um bom padrão conhecido com o qual você pode comparar sua solução para garantir a segurança. Esses controles tratam das regulamentações atuais e se adaptam conforme as regulamentações evoluem.

### Quais categorias de conformidade estão disponíveis no Azure?

Embora haja muitas outras, a imagem a seguir mostra algumas das ofertas de conformidade mais populares disponíveis no Azure. Essas ofertas são agrupadas em quatro categorias: Global, Governo dos EUA, Setor e Regional.

![compliance-matrix](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/examine-privacy-compliance-data-protection-standards/media/2-compliance-matrix-383090ad.png)

Embora nem todas essas ofertas de conformidade sejam relevantes para você ou para sua equipe, elas mostram que o compromisso da Microsoft com a conformidade é amplo, contínuo e testado e comprovado de maneira independente.

### Serviço de Informações de Justiça Criminal

Qualquer agência estadual ou local dos EUA que deseja acessar o banco de dados dos CJIS (Serviços de Informações de Justiça Criminal) do FBI precisa aderir à Política de Segurança dos CJIS.

### Certificação STAR da Cloud Security Alliance

A Certificação STAR baseia-se na obtenção da certificação ISO/IEC (Organização Internacional de Normalização/Comissão Eletrotécnina Internacional) 27001 e na adesão aos critérios especificados na CCM (Matriz de Controles de Nuvem). Essa certificação demonstra que um provedor de serviços de nuvem:

- Está em conformidade com os requisitos aplicáveis do ISO/IEC 27001.
- Tratou de problemas críticos para a segurança da nuvem, conforme descrito na CCM.
- Foi avaliado em relação ao Modelo de Maturidade de Capacidade STAR para o gerenciamento de atividades em áreas de controle da CCM.

### Cláusulas Modelo da União Europeia

A Microsoft oferece aos clientes as Cláusulas Contratuais Padrão da UE (União Europeia), que fornecem garantias contratuais com relação às transferências de dados pessoais fora da UE.

### Lei Health Insurance Portability and Accountability dos EUA

A lei HIPAA (Health Insurance Portability e Accountability) é uma lei federal dos EUA que regula as PHI (informações de saúde protegidas) dos pacientes.

O Azure oferece aos clientes um BAA (contrato de associado corporativo)do HIPAA, que estipula a adesão a determinadas provisões de privacidade e segurança da HIPAA e da lei HITECH. Para ajudar os clientes em seus esforços de conformidade individuais, a Microsoft oferece um contrato de associado empresarial aos clientes do Azure como um adendo do contrato.

### Organização Internacional de Normalização/Comissão Eletrotécnina Internacional 27018

A Microsoft é o primeiro provedor de nuvem a adotar o código de conduta ISO/IEC 27018, que abrange o processamento de informações pessoais por provedores de serviço de nuvem.

### Multi-Tier Cloud Security – Singapura

Após rigorosas avaliações realizadas pelo órgão de certificação de MTCS (Multi-Tier Cloud Security), os serviços em nuvem da Microsoft receberam a certificação MTCS 584:2013 em todas as três classificações de serviço:

- IaaS (infraestrutura como serviço)
- PaaS (plataforma como serviço)
- SaaS (software como serviço)

### Controles de Organização de Serviço 1, 2 e 3

Os serviços de nuvem cobertos pela Microsoft são auditados pelo menos uma vez ao ano em relação à estrutura de relatório SOC (Controles de Organização de Serviço) por auditores terceirizados independentes.

A auditoria dos serviços em nuvem da Microsoft aborda os controles de segurança, disponibilidade, processamento, integridade e confidencialidade dos dados, conforme aplicável aos princípios de confiança em escopo de cada serviço.

### National Institute of Standards and Technology Cybersecurity Framework

O NIST (National Institute of Standards and Technology ) CSF (Cybersecurity Framework) é uma estrutura voluntária que consiste em padrões, diretrizes e melhores práticas para gerenciar riscos de segurança cibernética.

### Government G-Cloud do Reino Unido

O Government G-Cloud do UK (Reino Unido) é uma certificação de computação em nuvem para serviços usados por entidades governamentais no Reino Unido. O Azure recebeu credenciamento oficial do governo do Reino Unido.

## Acessar a Política de Privacidade, os Termos dos Serviços Online e o Adendo de Proteção de Dados da Microsoft

Nesta seção, você verá como a Política de Privacidade, os Termos dos Serviços Online e o Adendo de Proteção de Dados da Microsoft explicam os dados pessoais coletados pela Microsoft, como ela os utiliza e para quais finalidades.

A política de privacidade abrange todos os serviços, sites, aplicativos, softwares, servidores e dispositivos da Microsoft. Essa lista inclui desde produtos corporativos e de servidor até dispositivos que você usa em casa, passando pelos softwares que os alunos usam na escola.

A política de privacidade da Microsoft também fornece informações relevantes para produtos específicos, como o Windows e o Xbox.

O OST (Online Services Terms - Termos dos Serviços Online) é um contrato legal entre a Microsoft e o cliente. O OST detalha as obrigações das duas partes em relação ao processamento e à segurança de dados de clientes e dados pessoais. O OST se aplica especificamente ao serviços online da Microsoft que você licencia por meio de uma assinatura, incluindo o Azure, o Dynamics 365, o Office 365 e o Bing Mapas.

### O que é o Adendo de Proteção de Dados?

O DPA (Adendo de Proteção de Dados - Data Protection Addendum) define com mais profundidade os termos de segurança e processamento de dados dos serviços online. Esses termos incluem:

- Conformidade com as leis.
- Divulgação de dados processados.
- Segurança de Dados, que inclui políticas e práticas de segurança, criptografia de dados, acesso a dados, responsabilidades do cliente e conformidade com auditorias.
- Transferência, retenção e exclusão de dados.

Para acessar o DPA:

1. Acesse a Documentação e os Termos de Licenciamento.
2. Na barra de pesquisa, insira DPA.
3. Nos resultados da pesquisa, localize o link para o DPA no idioma de sua preferência. 

### Explorar a Central de Confiabilidade

A Central de Confiabilidade demonstra os princípios da Microsoft para manutenção da integridade dos dados na nuvem e como a Microsoft implementa e dá suporte à segurança, à privacidade, à conformidade e à transparência em todos os seus produtos e serviços em nuvem.

A Central de Confiabilidade fornece:

- Informações detalhadas sobre segurança, privacidade, ofertas de conformidade, políticas, recursos e práticas recomendadas em todos os produtos de nuvem da Microsoft.
- Recursos adicionais sobre cada tópico.
- Links para os blogs de segurança, privacidade e conformidade e eventos futuros.

A Central de Confiabilidade é um excelente recurso para outras pessoas de sua organização que podem desempenhar funções de segurança, privacidade e conformidade.

## Acessar a documentação de conformidade do Azure

Aqui, você aprende a acessar a documentação detalhada sobre a conformidade e os padrões legais e regulatórios no Azure.

A documentação de conformidade do Azure fornece uma documentação detalhada sobre a conformidade e os padrões legais e regulatórios no Azure.

Aqui, você encontra ofertas de conformidade nestas categorias:

- Global
- Governo dos EUA
- Serviços financeiros
- Saúde
- Mídia e manufatura
- Regional

Também há recursos de conformidade adicionais, como relatórios de auditoria, informações de privacidade, mapeamentos e implementações de conformidade e white papers e relatórios de analistas. Diretrizes de privacidade e de conformidade de países e regiões também estão incluídas.

## O que é o Azure Governamental?

O Azure Government é uma instância separada do serviço do Microsoft Azure. Ele atende às necessidades de segurança e de conformidade das agências federais dos EUA, de governos estaduais e locais e de seus provedores de soluções. O Azure Government oferece isolamento físico de implantações que não são do governo dos EUA e fornece uma equipe de TI selecionada.

Os serviços do Azure Government lidam com os dados que estão sujeitos a determinadas normas e requisitos governamentais:

- FedRAMP (Federal Risk and Authorization Management Program)
- NIST (National Institute of Standards and Technology) 800.171 DIB (Defense Industrial Base)
- ITAR (Regulamentos de Tráfego Internacional de Armas)
- IRS (Receita Federal dos Estados Unidos) 1075
- DoD (Departamento de Defesa dos Estados Unidos) L4
- CJIS (Serviço de Informações de Justiça Criminal)

Para fornecer o mais elevado nível de segurança e conformidade, o Azure Government usa redes e data centers isolados fisicamente, localizados apenas nos EUA. Os clientes do Azure Government, como os governos locais, estaduais e federal dos EUA ou seus parceiros, estão sujeitos a uma validação quanto à elegibilidade.

## O que é o Azure China 21Vianet?

A Azure China 21Vianet é operada pela 21Vianet. Trata-se de uma instância fisicamente separada dos serviços de nuvem localizados na China. O Azure China 21Vianet é operado e administrado de maneira independente pela Xangai Blue Cloud Technology Co., Ltd. ("21Vianet"), uma subsidiária de propriedade total Beijing 21Vianet Broadband Data Center Co., Ltd.

De acordo com a Regulamentação de Telecomunicação da China, os provedores de serviços de nuvem, IaaS (infraestrutura como serviço) e PaaS (plataforma como serviço) precisam ter permissões de telecomunicação de valor agregado. Somente empresas registradas localmente com menos de 50% de investimento estrangeiro se qualificam para essas permissões. 

Os serviços do Azure são baseados nas mesmas tecnologias do Azure, do Office 365 e do Power BI que compõem o serviço de nuvem global da Microsoft, com níveis de serviço comparáveis. Os acordos e contratos do Azure na China, onde aplicável, são assinados entre os clientes e a 21Vianet.

## Resumo

Neste módulo, você aprendeu sobre a abordagem da Microsoft à privacidade, à segurança e à conformidade. Você explorou recursos específicos dos serviços online, incluindo o Azure, e como governos podem usar o Azure para atender às suas necessidades específicas de segurança e conformidade.

- A Política de Privacidade da Microsoft proporciona confiança na forma como a Microsoft coleta, protege e usa dados do cliente.
- A Central de Confiabilidade fornece documentação sobre padrões de conformidade e sobre como o Azure pode dar suporte à sua empresa.
- A documentação de conformidade do Azure inclui informações detalhadas sobre a conformidade e os padrões legais e regulatórios no Azure.

Tenha em mente que o status de conformidade dos produtos e serviços do Azure não implica automaticamente conformidade para o serviço ou aplicativo que você cria ou hospeda no Azure. Você é responsável por garantir a conformidade com os padrões legais e regulatórios que precisa seguir.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte5)

---

# ☁️ <a name="parte6"></a> Parte 6: Conceitos Básicos do Microsoft Azure: descrever os contratos de nível de serviço e o Gerenciamento de Custos da Microsoft

A migração para a nuvem apresenta novas maneiras de pensar em suas despesas de TI. A nuvem também elimina a carga de oferecer suporte à infraestrutura de TI.

Ao migrar para a nuvem, você pode perguntar:

- Quanto isso custará?
- Quais garantias o Azure oferece em relação ao tempo de atividade e à conectividade?
- Como os serviços em versão prévia afetam meus aplicativos de produção?

Saiba mais sobre os fatores que influenciam os custos, as ferramentas que você pode usar para ajudar a estimar e gerenciar seus gastos com a nuvem e como os SLAs (Contratos de Nível de Serviço) do Azure podem afetar suas decisões de design de aplicativo.

1. [Planeje e gerencie seus custos do Azure](#Planeje_e_gerencie_seus_custos_do_Azure)
2. [Escolha os serviços do Azure certos examinando SLAs e ciclo de vida do serviço](#Escolha_os_serviços_do_Azure_certos_examinando_SLAs_e_ciclo_de_vida_do_serviço)

Neste módulo, você aprenderá sobre os principais fatores que influenciam o custo da execução na nuvem. Ao longo do caminho, você terá experiência prática com algumas das ferramentas que pode usar para estimar os custos de execução de suas cargas de trabalho no Azure para ajudar a garantir que você permaneça dentro do orçamento e use apenas os serviços de que precisa.

Depois de concluir este módulo, você poderá:

- Usar a Calculadora de Custo Total de Propriedade para comparar os custos atuais do datacenter com a execução das mesmas cargas de trabalho no Azure
- Descrever as diferentes maneiras de comprar produtos e serviços do Azure
- Usar a calculadora de preços para estimar o custo mensal da execução de suas cargas de trabalho de nuvem
- Definir alguns dos principais fatores que afetam o custo total e aplicar práticas recomendadas para minimizar o custo

## 🔸 <a name="Planeje_e_gerencie_seus_custos_do_Azure"></a> Planeje e gerencie seus custos do Azure

## Comparar custos usando a Calculadora de custo total de propriedade

Compreender a situação atual da empresa dará uma noção melhor de o que a migração para a nuvem significa em termos de custo.

### O que é a Calculadora de TCO?

A Calculadora de TCO ajuda a estimar a economia de custos de operar sua solução no Azure ao longo do tempo em comparação com a operação no datacenter local.

O termo custo total de propriedade normalmente é usado em finanças. Pode ser difícil ver todos os custos ocultos relacionados à operação de um recurso tecnológico local. As licenças de software e o hardware são custos adicionais.

Com a Calculadora de TCO, você insere os detalhes de suas cargas de trabalho locais. Em seguida, você examina o custo médio sugerido do setor (que pode ser ajustado) relativo aos custos operacionais relacionados. Esses custos incluem luz, manutenção de rede e pessoal de TI. Você verá um relatório lado a lado. Usando o relatório, você pode comparar esses custos com as mesmas cargas de trabalho em execução no Azure.

![tco-report-bar-graphs](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/plan-manage-azure-costs/media/2-tco-report-bar-graphs.png)

> Você não precisa de uma assinatura do Azure para trabalhar com a Calculadora de TCO.

Trabalhar com a Calculadora de TCO envolve três etapas:

1. Definir suas cargas de trabalho
2. Ajustar as suposições
3. Exibir o relatório

### Etapa 1: Definir suas cargas de trabalho

Primeiro, você insere as especificações da sua infraestrutura local na Calculadora de TCO com base nestas quatro categorias:

- **Servidores** - Essa categoria inclui sistemas operacionais, métodos de virtualização, núcleos de CPU e memória (RAM).
- **Bancos de dados** - Essa categoria inclui tipos de banco de dados, hardware de servidor e o serviço do Azure que você deseja usar, que inclui o máximo de credenciais de usuário simultâneos esperadas.
- **Storage** - Essa categoria inclui o tipo de armazenamento e a capacidade, que inclui backups ou armazenamentos de arquivos.
- **Rede** - Essa categoria inclui a quantidade de largura de banda de rede que você consome atualmente no seu ambiente local.

### Etapa 2: Ajustar as suposições

Em seguida, especifique se suas licenças locais atuais estão inscritas para Software Assurance, o que pode economizar dinheiro reutilizando essas licenças no Azure. Você também especifica se precisa replicar o armazenamento para outra região do Azure para maior redundância.

Em seguida, você pode ver as principais suposições de custo operacional em várias áreas diferentes, que variam entre equipes e organizações. Esses custos foram certificados pela Nucleus Research, uma empresa de pesquisa independente. 

Por exemplo, esses custos incluem:

- Preço da eletricidade por quilowatts/hora (KWh)
- Taxa de pagamento por hora para a administração de TI
- Custo de manutenção de rede como um percentual de custos de hardware e software de rede

Para aumentar a precisão dos resultados da Calculadora de TCO, você pode ajustar os valores para que correspondam aos custos da sua infraestrutura local atual.

### Etapa 3: Exibir o relatório

Escolha um período entre um e cinco anos. A Calculadora de TCO gera um relatório com base nas informações inseridas.

![tco-report-piecharts](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/plan-manage-azure-costs/media/2-tco-report-piecharts.png)

Para cada categoria (computação, datacenter, rede, armazenamento e mão de obra de TI), você também pode exibir uma comparação lado a lado do detalhamento de custo de operar essas cargas de trabalho localmente, em vez de no Azure.

![tco-report-detailed-cost](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/plan-manage-azure-costs/media/2-tco-report-detailed-cost.png)

## Comprar serviços do Azure

- Que tipos de assinaturas do Azure estão disponíveis?
- Como podemos comprar os serviços do Azure?
- O local ou o tráfego de rede afeta o custo?
- Que outros fatores afetam o custo final?
- Como podemos obter uma estimativa mais detalhada do custo de executar no Azure?

É importante saber como os custos são gerados no Azure para que você possa entender como suas decisões de compra e design da solução podem afetar o custo final. 

### Que tipos de assinaturas do Azure posso usar?

O Azure oferece opções de assinatura gratuitas e pagas para atender às suas necessidades e requisitos. 

- **Avaliação gratuita** - Uma assinatura de avaliação gratuita fornece 12 meses de serviços gratuitos populares, um crédito para explorar qualquer serviço do Azure por 30 dias e mais de 25 serviços que são sempre gratuitos. Os serviços do Azure são desabilitados quando a avaliação termina ou quando seu crédito expira para produtos pagos, a menos que você atualize para uma assinatura paga.

- **Pago conforme o uso** - Uma assinatura com Pagamento Conforme o Uso permite que você pague pelo que usar vinculando um cartão de crédito ou débito à sua conta. As organizações podem se candidatar a descontos por volume e a faturamento pré-pago.

- **Ofertas de membro** - Sua associação existente a determinados produtos e serviços da Microsoft pode fornecer créditos para sua conta do Azure e taxas reduzidas nos serviços do Azure. Por exemplo, ofertas de membros estão disponíveis para assinantes do Visual Studio, membros da Microsoft Partner Network, membros da Microsoft para Startups e membros do Microsoft Imagine.

### Como comprar serviços do Azure?

- **Por meio de um Contrato Enterprise** - Clientes maiores, conhecidos como clientes corporativos, podem assinar um Contrato Enterprise com a Microsoft. Esse contrato os obriga a gastar um valor predeterminado nos serviços do Azure durante um período de três anos. O valor de serviço geralmente é pago anualmente. Como um cliente com Contrato Enterprise, você receberá o melhor preço personalizado conforme os tipos e as quantidades de serviços que planeja usar.
- **Diretamente da Web** - Aqui, você pode comprar os serviços do Azure diretamente do site do portal do Azure e pagar os preços padrão. Você é cobrado mensalmente, como um pagamento de cartão de crédito ou por uma fatura. Esse método de compra é conhecido como Web Direct.
- **Por meio de um Provedor de Soluções na Nuvem** - Um CSP (Provedor de Soluções na Nuvem) é um parceiro da Microsoft que ajuda você a criar soluções com base no Azure. Seu CSP cobra seu uso do Azure a um preço que ele determina. Ele também responde às suas perguntas de suporte e as encaminha à Microsoft conforme a necessidade.

Você pode abrir ou provisionar, recursos do Azure do portal do Azure ou da linha de comando. Sua conta é cobrada de acordo com o modelo "pagar pelo que usar" do Azure.

A qualquer momento, você pode verificar a página Gerenciamento de Custos e Cobrança no portal do Azure para obter um resumo do uso atual e examinar faturas de meses anteriores.

### Quais fatores afetam o custo?

#### Tipo de recurso 

Vários fatores influenciam o custo dos recursos do Azure. Eles dependem do tipo de recurso ou de como você o personaliza.

Por exemplo, com uma conta de armazenamento, você especifica um tipo (como armazenamento de blobs de blocos ou de tabelas), um nível de desempenho (Standard ou Premium) e uma camada de acesso (frequente, esporádico ou arquivos). Essas seleções apresentam custos diferentes.

#### Medidores de uso

Quando você provisiona um recurso, o Azure cria medidores para acompanhar o uso desse recurso. O Azure usa esses medidores para gerar um registro de uso que depois é usado para ajudar a calcular sua fatura.

Vamos examinar uma única VM como exemplo. Os seguintes tipos de medidores são relevantes para acompanhar seu uso:

- Tempo geral da CPU
- Tempo gasto com um endereço IP público
- Tráfego de rede de entrada (ingresso) e saída (egresso) da VM
- Tamanho do disco e quantidade de operações de leitura e gravação no disco

Cada medidor rastreia um tipo específico de uso. 

#### Uso de recursos

A desalocação de uma VM significa que a VM não está mais em execução, mas os discos rígidos e os dados associados ainda são mantidos no Azure. A VM não está atribuída a uma CPU ou rede no datacenter do Azure e, portanto, não gera os custos associados ao tempo de computação ou ao endereço IP da VM. Como os discos e os dados ainda estão armazenados e o recurso está presente em sua assinatura do Azure, você ainda será cobrado pelo armazenamento em disco.

Desalocar uma VM quando você não planeja usá-la por algum tempo é apenas uma forma de minimizar os custos. Por exemplo, você pode desalocar as VMs usadas para teste nos finais de semana quando sua equipe de teste não as usa.

#### Tipos de assinaturas do Azure

Alguns tipos de assinatura do Azure também incluem as concessões de uso, que afetam os custos.

Por exemplo, uma assinatura de avaliação gratuita do Azure fornece acesso a vários produtos do Azure gratuitos por 12 meses. Ele também inclui crédito a ser gasto em seus primeiros 30 dias de inscrição. Você também obtém acesso a mais de 25 produtos que sempre são gratuitos (com base na disponibilidade de recursos e regiões).

#### Azure Marketplace

Você também pode comprar soluções e serviços baseados no Azure de fornecedores terceirizados por meio do Azure Marketplace. As estruturas de cobrança são definidas pelo fornecedor.

### O local ou o tráfego de rede afeta o custo?

Ao provisionar um recurso no Azure, você precisa definir o local (conhecido como a região do Azure) de onde ele será implantado. Vamos ver por que essa decisão pode ter consequências de custo.

#### Location

A infraestrutura do Azure é distribuída globalmente, o que permite que você implante serviços centralmente ou os provisione mais perto de onde os clientes os usam.

Regiões diferentes podem ter preços associados diferentes. Como as regiões geográficas podem afetar o local em que o tráfego de rede flui, o tráfego de rede é uma influência de custo a ser considerada também. Se a empresa precisar transferir dados entre essas regiões ou se os usuários estiverem em diferentes partes do mundo, qualquer economia potencial poderá ser contrabalançada pelos custos de uso de rede adicionais da transferência de dados entre esses recursos.

#### Zonas para cobrança de tráfego de rede

A largura de banda refere-se aos dados que entram e saem dos datacenters do Azure. Algumas transferências de dados de entrada (dados que entram em datacenters do Azure) são gratuitas. Para transferências de dados de saída (dados que saem de data centers do Azure), o preço de transferência de dados é baseado em zonas.

Uma zona é um agrupamento geográfico de regiões do Azure para fins de cobrança. 

- Zona 1: Austrália Central, Oeste dos EUA, Leste dos EUA, Oeste do Canadá, Oeste da Europa, França Central e outros
- Zona 2: Leste da Austrália, Oeste do Japão, Índia Central, Sul da Coreia e outros
- Zona 3: Sul do Brasil, Norte da África do Sul, Oeste da África do Sul, EAU Central, Norte dos EAU
- Alemanha Zona 1: Alemanha Central e Nordeste da Alemanha

### Como posso estimar o custo total?

A calculadora de preços exibe produtos do Azure em categorias. Você pode adicionar essas categorias à sua estimativa e configurar de acordo com seus requisitos específicos. Em seguida, você receberá um preço estimado consolidado, com uma análise detalhada dos custos associados a cada recurso que adicionou à sua solução. 

Você também pode acessar os detalhes de preços, os detalhes do produto e a documentação de cada produto de dentro da calculadora de preços.

As opções que você pode configurar na calculadora de preços variam entre os produtos, mas podem incluir:

- **Região** - Uma região é a localização geográfica na qual você pode provisionar um serviço. Sudeste da Ásia, Canadá Central, Oeste dos Estados Unidos e Norte da Europa são alguns exemplos.
- **Camada** - Camadas, como a Camada gratuita, a Camada básica e assim por diante, têm níveis diferentes de disponibilidade ou desempenho e custos associados diferentes.
- **Opções de cobrança** - As opções de cobrança realçam as diferentes maneiras de pagar por um serviço. As opções podem variar com base no tipo de cliente e no tipo de assinatura e podem incluir alternativas para economizar custos.
- **Opções de suporte** - Essas opções permitem que você selecione alternativas de preços de suporte adicionais para determinados serviços.
- **Programas e ofertas** - Seu tipo de cliente ou assinatura pode permitir que você escolha programas de licenciamento específicos ou outras ofertas.
- **Preço de Desenvolvimento/Teste do Azure** - Essa opção lista os preços disponíveis para cargas de trabalho de desenvolvimento e teste. O preço de Desenvolvimento/Teste se aplica quando você executa recursos dentro de uma assinatura do Azure que se baseia em uma oferta de desenvolvimento/teste.

> Lembre-se de que a calculadora de preços fornece estimativas, não cotações de preços reais. 

## Gerenciar e minimizar o custo total no Azure

### Entenda os custos estimados antes de implantar

Para ajudá-lo a planejar sua solução no Azure, considere cuidadosamente os produtos, serviços e recursos de que você precisa. Leia a documentação pertinente para entender como cada uma das suas escolhas é medida e cobrada.

Calcule os custos projetados usando a calculadora de preços e a Calculadora de TCO (custo total de propriedade). Adicione somente os produtos, os serviços e os recursos necessários para sua solução.

### Use o Azure Advisor para monitorar seu uso

Idealmente, você deseja que os recursos provisionados correspondam ao uso real.

O Azure Advisor identifica recursos não utilizados ou subutilizados e recomenda recursos não utilizados que podem ser removidos. Essa informação ajuda a configurar seus recursos para que correspondam à carga de trabalho real.

As recomendações são classificadas por impacto: alto, médio ou baixo. Em alguns casos, o Assistente do Azure pode corrigir o problema subjacente de modo automático. 

### Use limites de gastos para restringir seus gastos

Se você tiver uma avaliação gratuita ou uma assinatura do Azure baseada em crédito, poderá usar limites de gastos para evitar excesso inadvertido.

Se você tiver uma assinatura baseada em crédito e alcançar seu limite de gastos configurado, o Azure suspenderá sua assinatura até que um novo período de cobrança comece.

Um conceito relacionado é de cotas, ou limites ao número de recursos semelhantes que você pode provisionar em sua assinatura. Por exemplo, você pode alocar até 25.000 VMs por região. Esses limites ajudam principalmente a Microsoft a planejar a capacidade do datacenter.

### Usar Reservas do Azure para pagar antecipadamente

As Reservas do Azure oferecem preços com desconto em determinados serviços do Azure. As Reservas do Azure podem economizar até 72% em comparação aos preços pagos conforme o uso. Para receber um desconto, você pode reservas serviços e recursos pagando com antecedência.

As Reservas do Azure estão disponíveis para clientes com um Contrato Enterprise, provedores de soluções na nuvem e assinaturas com Pagamento Conforme o Uso.

### Escolher regiões e locais de baixo custo

O custo de produtos, serviços e recursos do Azure pode variar em locais e regiões. Se possível, você deve usá-los nos locais e nas regiões onde custam menos.

Porém, lembre-se de que alguns recursos são medidos e cobrados de acordo com a quantidade de largura de banda de rede de saída (egresso) que consomem. Você deve provisionar recursos conectados que são medidos por largura de banda na mesma região do Azure para reduzir o tráfego de saída entre eles.

### Pesquisar ofertas econômicas disponíveis

Mantenha-se atualizado com as ofertas de cliente e assinatura do Azure mais recentes e mude para ofertas que ofereçam o maior benefício de economia de custo.

### Use o Gerenciamento de Custos e Cobranças da Microsoft para controlar os gastos

O Gerenciamento de Custos é um serviço gratuito que ajuda você a entender sua fatura do Azure, gerenciar sua conta e assinaturas, monitorar e controlar os gastos do Azure e otimizar o uso de recursos.

Os recursos de Gerenciamento de Custos incluem:

- **Relatórios** - Use dados históricos para gerar relatórios e prever o uso e as despesas futuras.
- **Enriquecimento de dados** - Melhore a responsabilidade classificando os recursos com tags que correspondam a unidades organizacionais e de negócios do mundo real.
- **Orçamentos** - Crie e gerencie orçamentos de custo e uso monitorando tendências de demanda de recursos, taxas de consumo e padrões de custo.
- **Alertas** - Obtenha alertas conforme seus orçamentos de custo e uso.
- **Recomendações** - Receba recomendações para eliminar recursos ociosos e otimizar os recursos do Azure que você provisiona.

### Aplique tags para identificar os proprietários de custo

As tags ajudam a gerenciar os custos associados aos diferentes grupos de produtos e recursos do Azure. Você pode aplicar tags a grupos de recursos do Azure para organizar dados de cobrança.

As tags facilitam a identificação dos grupos que geram os maiores custos do Azure, o que pode ajudar você a ajustar seus gastos de acordo.

### Redimensionar máquinas virtuais subutilizadas

Uma recomendação comum que você encontrará no Gerenciamento de Custos e no Azure Advisor é redimensionar ou desligar as VMs que estão subutilizadas ou ociosas.

Os custos de máquinas virtuais são lineares, custando o dobro para cada tamanho maior da mesma série. Nesse caso, se você reduzir o tamanho da VM de Standard_D4_v4 para Standard_D2_v4, que é o próximo menor tamanho, reduzirá o custo de computação em 50%.

> Lembre-se de que redimensionar uma VM exige que ela seja interrompida, redimensionada e então reiniciada. Esse processo pode levar alguns minutos, dependendo de quão significativa é a alteração de tamanho. Planeje-se adequadamente uma interrupção ou desloque o tráfego para outra instância enquanto executa operações de redimensionamento.

### Desalocar máquinas virtuais durante horas de inatividade

Lembre-se de que desalocar uma VM significa não executar mais a VM, mas preservar os discos rígidos e os dados associados no Azure.

Se você tem cargas de trabalho de VM usadas apenas durante determinados períodos, mas está executando-as durante todas as horas de todos os dias, está perdendo dinheiro. Essas VMs são excelentes candidatas a serem desligadas quando não estão em uso e reiniciadas conforme necessário, economizando custos de computação enquanto a VM fica desalocada.

Essa abordagem é uma excelente estratégia para ambientes de desenvolvimento e teste, em que as VMs são necessárias somente no horário comercial. O Azure oferece, inclusive, uma forma de iniciar e parar automaticamente suas VMs conforme um agendamento.

### Excluir recursos não utilizados

Essa recomendação pode parecer óbvia, mas se você não estiver usando um recurso, deverá desativá-lo. Não é incomum encontrar sistemas de não produção ou de prova de conceito que não sejam mais necessários após a conclusão de um projeto.

Analise regularmente seu ambiente e trabalho para identificar esses sistemas. Desligar esses sistemas pode ter um benefício duplo, economizando custos de infraestrutura e, possivelmente, custos de licenciamento e operações.

### Migrar de IaaS para serviços PaaS

À medida que você move as cargas de trabalho para a nuvem, uma evolução natural é começar com serviços de IaaS (infraestrutura como serviço) porque eles são mapeados mais diretamente para conceitos e operações com as quais você já está familiarizado.

Ao longo do tempo, uma forma de reduzir os custos é migrar gradualmente as cargas de trabalho de IaaS para serem executadas em serviços PaaS (plataforma como serviço). PaaS fornece ambientes de desenvolvimento e implantação prontos que são gerenciados para você.

Por exemplo, digamos que você execute o SQL Server em uma VM em execução no Azure. Essa configuração exige que você gerencie o sistema operacional subjacente, configure uma licença do SQL Server, gerencie atualizações de software e segurança e assim por diante. Você também paga pela VM esteja o banco de dados processando consultas ou não. Uma forma de potencialmente economizar custos é mover o banco de dados do SQL Server em uma VM para o Banco de Dados SQL do Azure. O Banco de Dados SQL do Azure é baseado em SQL Server.

A execução de serviços de PaaS, como o Banco de Dados SQL do Azure, muitas vezes tem um menor custo, porém, como eles são gerenciados para você, não é preciso se preocupar com atualizações de software, patches de segurança ou otimização do armazenamento físico para operações de leitura e gravação.

### Reduzir os custos de licenciamento

O licenciamento é outra área que pode afetar drasticamente seus gastos com a nuvem. 

#### Escolher sistemas operacionais econômicos

Muitos serviços do Azure fornecem uma opção de execução no Windows ou no Linux. Em alguns casos, o custo depende do que você escolhe. Quando você tem opção e seu aplicativo não depende do sistema operacional subjacente, é útil comparar preços para ver se é possível economizar dinheiro.

### Usar o Benefício Híbrido do Azure para realocar licenças de software no Azure

Se você comprou licenças para o Windows Server ou o SQL Server e elas são cobertas pelo Software Assurance, poderá realocá-las para VMs no Azure.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte6)

## 🔸 <a name="Escolha_os_serviços_do_Azure_certos_examinando_SLAs_e_ciclo_de_vida_do_serviço"></a> Escolha os serviços do Azure certos examinando SLAs e ciclo de vida do serviço

Migrar para a nuvem também elimina a carga de oferecer suporte à infraestrutura de TI. Quando a conectividade de rede é perdida ou um disco rígido falha, você depende do provedor de nuvem para restaurar o serviço.

Saiba mais sobre os SLAs (Contratos de Nível de Serviço - service-level agreement) no Azure e como eles podem afetar suas decisões de design de aplicativo. Veja como acessar a versão prévia dos serviços e saiba como eles afetam o planejamento.

Depois de concluir este módulo, você poderá:

- Descrever o que é um SLA (Contrato de Nível de Serviço - service-level agreement) e por que os SLAs são importantes.
- Identificar fatores, como a camada de serviço escolhida, que podem afetar um SLA.
- Combinar SLAs para computar um SLA composto.
- Descrever o ciclo de vida do serviço no Azure, incluindo como acessar novas funcionalidades que estão chegando ao Azure.

## O que são SLAs (Contratos de Nível de Serviço - service-level agreement)?

Conforme mencionado no vídeo, um SLA (Contrato de Nível de Serviço) é um contrato formal entre uma empresa de serviços e o cliente. No caso do Azure, esse contrato define os padrões de desempenho com os quais a Microsoft se compromete a fornecer para você, o cliente.

### Por que os SLAs são importantes?
Entender o SLA para cada serviço do Azure usado ajuda a entender que garantias você pode esperar.

Quando você cria aplicativos no Azure, a disponibilidade dos serviços usados afeta o desempenho do aplicativo. Entender os SLAs envolvidos pode ajudar a estabelecer o SLA definido com seus clientes.

### Em que local posso acessar os SLAs para os serviços do Azure?

Você pode acessar os SLAs em [Contratos de Nível de Serviço](https://azure.microsoft.com/pt-br/support/legal/sla/).

Cada serviço do Azure define o próprio SLA. Os serviços do Azure são organizados em categorias.

### O que há em um SLA típico?

- **Introdução** - Esta seção explica o que esperar desse SLA, incluindo o escopo e como as renovações de assinatura podem afetar os termos.
- **Termos gerais** - Esta seção contém termos que são usados em todo o SLA para que ambas as partes (você e a Microsoft) tenham um vocabulário consistente. Por exemplo, esta seção pode definir o que significa tempo de inatividade, incidentes e códigos de erro. Esta seção também define os termos gerais do contrato, incluindo como enviar um requerimento, receber crédito por problemas de desempenho ou disponibilidade e limitações do contrato.
- **Detalhes de SLA** - Esta seção define as garantias específicas para o serviço. Os compromissos de desempenho geralmente são medidos como um percentual. Essa porcentagem normalmente varia de 99,9% ("três noves") a 99,99% ("quatro noves").
    - O principal compromisso de desempenho geralmente se concentra em tempo de atividade ou no percentual de tempo em que um produto ou serviço está funcionando com êxito. Alguns SLAs se concentram também em outros fatores, incluindo latência ou quão rápido o serviço deve responder a uma solicitação.
    - Esta seção também define quaisquer termos adicionais específicos para esse serviço.

### Como os percentuais estão relacionados ao tempo de inatividade total?

O tempo de inatividade refere-se à duração da indisponibilidade do serviço.

A diferença entre 99,9% e 99,99% pode parecer pequena, mas é importante entender o que esses números significam em termos de tempo de inatividade total.

| Percentual de SLA	| Tempo de inatividade por semana | Tempo de inatividade por mês | Tempo de inatividade por ano |
|-|-|-|-|
| 99 | 1,68 hora | 7,2 horas | 3,65 dias |
| 99,9 | 10,1 minutos | 43,2 minutos | 8,76 horas |
| 99,95 | 5 minutos | 21,6 minutos | 4,38 horas |
| 99,99 | 1,01 minuto | 4,32 minutos | 52,56 minutos |
| 99,999 | 6 segundos | 25,9 segundos | 5,26 minutos |

> Esses valores são cumulativos, o que significa que a duração de várias interrupções de serviço diferentes é combinada ou somada.

### O que são créditos de serviço?

Um crédito do serviço é o percentual dos valores pagos que são creditados de volta para você de acordo com o processo de aprovação da declaração.

Um SLA descreve como a Microsoft responde quando o desempenho de um serviço do Azure não cumpre as especificações. Por exemplo, você pode receber um desconto em sua fatura do Azure como compensação quando um serviço não tem desempenho de acordo com o SLA.

Normalmente, os créditos aumentam conforme o tempo de atividade diminui.

### Qual é o SLA para serviços gratuitos?

Produtos gratuitos normalmente não têm um SLA.

### Como saber quando há uma interrupção?

O status do Azure fornece uma exibição global da integridade dos serviços e regiões do Azure. A suspeita de uma interrupção geralmente é um bom ponto de partida para a investigação.

O status do Azure fornece um RSS feed de alterações à integridade dos serviços do Azure que você pode assinar. 

Na página de status do Azure, você também pode acessar a Integridade do Serviço do Azure. Ela fornece uma exibição personalizada da integridade dos serviços e das regiões do Azure que você está usando diretamente no portal do Azure.

### Como posso solicitar um crédito de serviço da Microsoft?

Normalmente, você precisa registrar um requerimento com a Microsoft para receber um crédito de serviço. Se você comprar os serviços do Azure de um parceiro CSP (Provedor de Soluções na Nuvem), o CSP normalmente gerenciará o processo de reivindicações.

Cada SLA especifica o prazo até o qual você deve enviar seu requerimento e quando a Microsoft o processará. Para muitos serviços, você deve enviar seu requerimento até o final do mês do calendário após o mês em que o incidente ocorreu.

## Definir o SLA do aplicativo

Um SLA aplicativo define os requisitos de SLA para um aplicativo específico. Esse termo geralmente se refere a um aplicativo que você compilar no Azure.

Há muitas decisões de design que você pode tomar para melhorar a disponibilidade e a resiliência dos aplicativos e dos serviços que cria no Azure. Essas decisões se estendem além do SLA para um serviço específico.

Um bom ponto de partida é discutir com a equipe a importância da disponibilidade de cada aplicativo para o seu negócio. 

- **Impacto aos negócios** - Se o aplicativo falhar, qual será o impacto aos negócios? Nesse caso, os clientes não podem inserir novos pedidos por meio da loja e a equipe não pode verificar o status de pedidos existentes. Os clientes precisarão tentar novamente mais tarde ou, possivelmente, ir para um concorrente.

- **Efeito sobre outras operações de negócios** - Se o aplicativo falhar, afetará outros serviços?

- **Padrões de uso** - Os padrões de uso definem quando e como os usuários acessam seu aplicativo.
    - Uma questão a ser considerada é se o requisito de disponibilidade é diferente entre períodos críticos e não críticos. Por exemplo, um aplicativo de declaração de imposto não pode falhar durante um prazo de entrega da declaração.

### O que a equipe decide?

Digamos que a empresa decida que um SLA de 99,9% é aceitável para um aplicativo. Isso dá à empresa um tempo de inatividade estimado de 10,1 minutos por semana. Mas como ela fará com que suas opções de tecnologia deem suporte ao SLA de seu aplicativo?

## Projetar seu aplicativo para atender ao seu SLA

Agora, você precisa criar uma solução eficiente e confiável para esse aplicativo no Azure, mantendo o SLA do aplicativo em mente. 

Na realidade, ocorrerão falhas. O hardware pode falhar. A rede pode ter períodos de tempo limite intermitentes. Embora seja raro que um serviço ou região inteira sofra uma interrupção, você ainda precisa planejar esses eventos.

### Identificar suas cargas de trabalho

Uma carga de trabalho é uma funcionalidade ou tarefa distinta logicamente separada de outras tarefas em termos de requisitos de armazenamento de dados e lógica de negócios. Cada carga de trabalho define um conjunto de requisitos de disponibilidade, escalabilidade, consistência de dados e recuperação de desastres.

No Azure, o aplicativo exemplo exigirá:

- Duas máquinas virtuais.
- Uma instância do Banco de Dados SQL do Azure.
- Uma instância do Azure Load Balancer.

### Combinar SLAs para computar o SLA composto

Depois de identificar o SLA para as cargas de trabalho individuais no aplicativo, você pode observar que esses SLAs não são todos iguais. Como isso afeta nosso requisito geral de SLA de aplicativo de 99,9%? Para resolver isso, você precisará fazer alguns cálculos.

O processo de combinar SLAs ajuda a computar o SLA composto para um conjunto de serviços. A computação do SLA composto exige que você multiplique o SLA de cada serviço individual.

Em [Contratos de Nível de Serviço](https://azure.microsoft.com/pt-br/support/legal/sla/), você descobre o SLA para cada serviço do Azure de que precisa. Eles são:

| Serviço | Contrato de Nível de Serviço |
|-|-|
| 2 Máquinas Virtuais do Azure | 99,9% |
| 1 Banco de Dados SQL do Azure | 99,99% |
| 1 Azure Load Balancer | 99,99% |

Portanto, para o aplicativo, o SLA composto seria:

SLA Composto = 99,9% x 99,9% x 99,99% x 99,99% 

SLA Composto = 0,999 x 0,999 x 0,9999 x 0,9999 

SLA Composto = 0.9978 = 99.78%

> Lembre-se de que você precisa de duas máquinas virtuais. Portanto, você inclui o SLA de Máquinas Virtuais de 99,9% duas vezes na fórmula.

Observe que, embora todos os serviços individuais tenham SLAs iguais ou melhores que o SLA de aplicativo, a combinação deles resulta em um número geral menor do que o percentual de 99,9% necessário. 

Você vê aqui que o SLA composto de 99,78% não cumpre o SLA necessário de 99,9%. Você pode voltar à sua equipe e perguntar se isso é aceitável. Ou pode implementar outras estratégias no design para melhorar o SLA.

### O que acontece quando o SLA composto não atende às suas necessidades?

#### Escolher as opções de personalização que atendam ao SLA necessário

Cada uma das cargas de trabalho definidas anteriormente tem o próprio SLA, e as opções de personalização feitas ao provisionar cada carga de trabalho afetam o SLA. Por exemplo:

- **Discos** - Com as Máquinas Virtuais, você pode escolher entre um disco gerenciado HDD Standard, um disco gerenciado SSD Standard, um SSD Premium ou um Disco Ultra. O SLA para uma única VM seria de 95%, 99,5% ou 99,9%, dependendo da escolha do disco.

- **Camadas** - Alguns serviços do Azure são oferecidos como um produto de camada gratuita e como um serviço pago padrão. Por exemplo, a Automação do Azure fornece 500 minutos de runtime de trabalho em uma conta gratuita do Azure, mas não tem o suporte de um SLA. O SLA da camada Standard para a Automação do Azure é de 99,9%.

Suas decisões de compra devem levar em conta o impacto sobre o SLA para os serviços do Azure escolhidos. Isso garante que o SLA dê suporte ao SLA de aplicativo necessário.

#### Insira requisitos de disponibilidade no design

Há considerações de design de aplicativo que você pode usar com relação à infraestrutura de nuvem subjacente.

Por exemplo, para melhorar a disponibilidade do aplicativo, evite pontos únicos de falha. Assim, em vez de adicionar mais máquinas virtuais, você pode implantar uma ou mais instâncias adicionais da mesma máquina virtual em diferentes zonas de disponibilidade na mesma região do Azure.

Uma zona de disponibilidade é um local físico exclusivo dentro de uma região do Azure. Cada zona é composta por um ou mais datacenters equipados com energia, resfriamento e rede independentes. Essas zonas usam agendas diferentes para manutenção, ou seja, se uma zona for afetada, sua instância de máquina virtual na outra zona não será afetada.

A implantação de duas ou mais instâncias de uma máquina virtual do Azure em duas ou mais zonas de disponibilidade eleva o SLA da máquina virtual a 99,99%. O recálculo de seu SLA composto acima com esse SLA de Máquinas Virtuais dá a você um SLA de aplicativo de:

SLA Composto = 99,99% x 99,99% x 99,99% x 99,99% = 99,96%

Esse SLA revisado de 99,96% excede o seu alvo de 99,9%.

#### Incluir redundância para aumentar a disponibilidade

Para garantir alta disponibilidade, você pode planejar que seu aplicativo tenha componentes duplicados em várias regiões, o que é conhecido como redundância. Por outro lado, para minimizar os custos durante períodos não críticos, você pode executar o aplicativo somente em uma única região. 

Para alcançar a disponibilidade máxima em seu aplicativo, adicione redundância a cada parte do aplicativo. Essa redundância inclui o próprio aplicativo, bem como os serviços e a infraestrutura subjacentes. No entanto, esteja ciente de que isso pode ser difícil e caro e, muitas vezes, resulta em soluções desnecessariamente complexas.

Considere a importância da alta disponibilidade para seus requisitos antes de adicionar redundância. Pode haver maneiras mais simples de cumprir o SLA do aplicativo.

#### É difícil alcançar um desempenho muito alto

Metas de desempenho acima de 99,99% são muito difíceis de alcançar. Um SLA de 99,99% significa ter 1 minuto de tempo de inatividade por semana. É difícil seres humanos responderem a falhas com rapidez suficiente para cumprir metas de desempenho de SLA superiores a 99,99%. Em vez disso, seu aplicativo deve ser capaz de realizar os próprios diagnósticos e reparos durante uma interrupção.

## Acessar versões prévias dos recursos e dos serviços

### O que é o ciclo de vida do serviço?

O ciclo de vida do serviço define como cada serviço do Azure é liberado para uso público.

Cada serviço do Azure começa na fase de desenvolvimento. Nesta fase, a equipe do Azure coleta e define seus requisitos e começa a criar o serviço.

Em seguida, o serviço é liberado para a fase de versão prévia pública. Durante essa fase, o público pode acessá-lo, experimentá-lo e fornecer comentários reais. 

Depois que um novo serviço do Azure for validado e testado, ele será liberado a todos os clientes como um serviço pronto para produção. Isso é conhecido como GA (disponibilidade geral).

Cada versão prévia do Azure define os próprios termos e condições. 

Algumas versões prévias podem não estar cobertas pelo suporte ao cliente e podem estar sujeitas a compromissos de segurança, conformidade e privacidade reduzidos ou diferentes. Por esses motivos, as versões prévias não são recomendadas para cargas de trabalho comercialmente críticas.

Você pode acessar as versões prévias dos serviços pelo portal do Azure.

Quando você estiver usando a versão prévia do portal do Azure, o elemento Microsoft Azure (versão prévia) será exibido no cabeçalho da página para lembrar qual versão do portal do Azure você está usando. 

### Resumo

Um SLA (Contrato de Nível de Serviço) é o contrato formal entre uma empresa de serviços e o cliente. No caso do Azure, esse contrato define os padrões de desempenho com os quais a Microsoft se compromete a fornecer para seus clientes.

Conforme os requisitos evoluem, é importante que a equipe entenda como o SLA de cada serviço escolhido afeta as garantias gerais de desempenho dos aplicativos.

Ao definir seus requisitos de SLA, considere as suas necessidades comerciais e o tempo necessário para restaurar um componente após uma falha. Considere também como o uso de versões prévias dos recursos e serviços pode afetar seus sistemas em produção.

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte6)