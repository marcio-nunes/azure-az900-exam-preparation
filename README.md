# <a name="topo"></a>Preparação para o exame Azure AZ-900

## Considerações

1. Todo conteúdo foi retirado dos módulos e paths do site [Microsoft Learn](https://docs.microsoft.com/pt-br/learn/) para fins de estudo.
2. Criei o [Path de estudo para a certificação AZ-900](https://docs.microsoft.com/pt-br/users/marcio-nunes-silva/collections/ew7zi52118116y) e vou atualizando conforme necessidade. 
3. Esse resumo não substitui os módulos completos. Recomendo fortemente estudar através dos módulos do MS Learn.
4. Resumo baseado no [Study Guide](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3VwUY) oficial da Microsoft.
5. [Microsoft Azure training and certifications](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4J5ea)
6. Façam simulados. 
	- [Microsoft AZ-900 practice test](https://esi.microsoft.com/getcertification)
	- Na Udemy você também encontra alguns. [Udemy Practice Test](https://www.udemy.com/course/az-900-microsoft-azure-fundamentals-practice-tests-2022-k)
	- [itexams](https://www.itexams.com/exam/AZ-900)
7. [Agendamento do exame](https://esi.microsoft.com/getcertification) de certificação.
8. Fiquem a vontade para ajudar a melhorar o conteúdo.

Icons: ☁️🔸

# Study Guide - Skills measured

- [Describe cloud concepts (25-30%)](#Describe_cloud_concepts)
- [Describe Azure architecture and services (35-40%)](#Describe_Azure_architecture_and_services)
- [Describe Azure management and governance (30-35%)](#Describe_Azure_management_and_governance)

# <a name="Describe_cloud_concepts"></a> ☁️ Describe cloud concepts (25-30%)

## 🔸 Describe cloud computing

### Define cloud computing

É a entrega de serviços de computação pela Internet. Esses serviços incluem servidores, armazenamentos, bancos de dados, redes, software, análises e inteligência. A computação em nuvem oferece inovação mais rápida, recursos flexíveis e economias de escala.

### Describe the shared responsibility model

Num datacenter corporativo tradicional a empresa é responsável por manter o espaço físico, garantir a segurança e manter ou substituir os servidores se algo acontecer. TI é responsável por manter toda a infraestrutura e o software necessários para manter o datacenter em funcionamento. É provável que eles também sejam responsáveis por manter todos os sistemas corrigidos e na versão correta.

Na núvem, essas responsabilidades são compartilhadas entre o provedor de nuvem e o consumidor. 

- **Responsabilidade do provedor de nuvem**: Segurança física, energia, resfriamento e conectividade de rede. 
- **Responsabilidades do consumidor**: é responsável pelos dados e pelas informações armazenados na nuvem e pela segurança de acesso, o que significa que você só dá acesso àqueles que precisam.
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

**Nuvem pública**
- As implantações de nuvem pública são frequentemente usadas para fornecer e-mail baseado na Web, aplicativos de escritório online, armazenamento e ambientes de teste e desenvolvimento.
	- Custos mais baixos - não há necessidade de comprar hardware ou software e você paga apenas pelo serviço que usa. 
	- Sem manutenção - seu provedor de serviços fornece a manutenção. 
	- Escalabilidade quase ilimitada - recursos sob demanda estão disponíveis para atender às suas necessidades de negócios. 
	- Alta confiabilidade - uma vasta rede de servidores garante proteção contra falhas.

**Nuvem privada**
- Muitas organizações escolhem uma abordagem de nuvem pricada devido a imperativos de negócios, como atender aos requisitos regulatórios e de soberania de dados, aproveitar ao máximo o investimento em tecnologia local ou resolver problemas de baixa latência.
- Nuvens privadas são frequentemente usadas por agências governamentais, instituições financeiras e quaisquer outras organizações de médio a grande porte com operações críticas para os negócios que buscam maior controle sobre seu ambiente.
	- Mais flexibilidade - sua organização pode personalizar seu ambiente de nuvem para atender a necessidades comerciais específicas. 
	- Mais controle - os recursos não são compartilhados com outros, portanto, níveis mais altos de controle e privacidade são possíveis. 
	- Mais escalabilidade - as nuvens privadas geralmente oferecem mais escalabilidade em comparação com a infraestrutura local.

**Nuvem híbrida**
- A computação de borda traz o poder de computação da nuvem para dispositivos IoT – mais perto de onde os dados residem. Ao mover as cargas de trabalho para a borda, os dispositivos gastam menos tempo se comunicando com a nuvem, reduzindo a latência e podem até operar de forma confiável em longos períodos offline.
- Muitos clientes aproveitam a nuvem híbrida para alcançar escala global, maior confiabilidade, segurança habilitada por IA e economia de custos oferecida pela nuvem pública. Em setores altamente regulamentados, os requisitos de residência de dados podem exigir que determinados conjuntos de dados sejam mantidos no local, enquanto outras cargas de trabalho podem residir na nuvem pública.
- Se um aplicativo reside no local ou em uma nuvem privada, picos repentinos de demanda podem sobrecarregar a capacidade, como eventos sazonais, como compras on-line ou declaração de impostos. Quando a demanda aumenta, as organizações podem acessar recursos de computação adicionais na nuvem pública, às vezes chamados de “cloud bursting” – onde o ambiente de nuvem híbrida permite que a infraestrutura local “exploda” para a nuvem pública.

### Describe the consumption-based model

- Na computação em nuvem, você não paga pela infraestrutura física, pela eletricidade, pela segurança nem por nada que esteja associado à manutenção de um datacenter. Você paga pelos recursos de TI que usa. 
	- **Modelo baseado em consumo**. As organizações pagam apenas pelo que usam e operam em um modelo de OpEx (despesas operacionais).
	- **OpEx** - é o gasto de capital em serviços ou produtos ao longo do tempo. O aluguel de um centro de convenções, o leasing de um veículo da empresa ou a assinatura de serviços de nuvem são exemplos de OpEx.
	- **CapEx** - normalmente é uma despesa inicial única para comprar ou proteger recursos tangíveis. Um prédio novo, a repavimentação do estacionamento, a construção de um datacenter ou a compra de um veículo da empresa são exemplos de CapEx.
- Um modelo baseado em consumo oferece vários benefícios, como:
	- Sem custos prévios.
	- Não há necessidade de comprar nem gerenciar uma infraestrutura cara que os usuários talvez não usem na capacidade máxima.
	- A capacidade de pagar para obter mais recursos quando necessário.
	- A capacidade de parar de pagar por recursos que não são mais necessários.

### Compare cloud pricing models

- Avaliação gratuita - Uma assinatura de avaliação gratuita fornece 12 meses de serviços gratuitos populares, um crédito para explorar qualquer serviço do Azure por 30 dias e mais de 25 serviços que são sempre gratuitos. Os serviços do Azure são desabilitados quando a avaliação termina ou quando seu crédito expira para produtos pagos, a menos que você atualize para uma assinatura paga.
- Pago conforme o uso - Uma assinatura com Pagamento Conforme o Uso permite que você pague pelo que usar vinculando um cartão de crédito ou débito à sua conta. As organizações podem se candidatar a descontos por volume e a faturamento pré-pago.
- Ofertas de membro - Sua associação existente a determinados produtos e serviços da Microsoft pode fornecer créditos para sua conta do Azure e taxas reduzidas nos serviços do Azure. Por exemplo, ofertas de membros estão disponíveis para assinantes do Visual Studio, membros da Microsoft Partner Network, membros da Microsoft para Startups e membros do Microsoft Imagine.

## 🔸 Describe the benefits of using cloud services

Alta disponibilidade, escalabilidade, confiabilidade e previsibilidade

### Describe the benefits of high availability and scalability in the cloud

- **Alta disponibilidade**: dependendo do SLA que você escolher, seus aplicativos poderão oferecer uma experiência de usuário contínua, sem tempo de inatividade aparente, mesmo quando as coisas derem errado.

- **Escalabilidade**: os aplicativos na nuvem podem ser dimensionados verticalmente e horizontalmente:
	- **Dimensione verticalmente** - aumentar a capacidade de computação adicionando RAM ou CPUs a uma máquina virtual.
	- **Dimensionar horizontalmente** - aumentar a capacidade de computação adicionando instâncias de recursos.

### Describe the benefits of reliability and predictability in the cloud

- **Confiabilidade** garante que seu aplicativo possa cumprir os compromissos que você assume com seus clientes.
	- A confiabilidade é uma responsabilidade compartilhada
	- Garante que suas cargas de trabalho fiquem disponíveis e possam se recuperar de falhas em qualquer escala.
	- **Recuperação de desastre**: ao aproveitar os serviços de backup baseados em nuvem, a replicação de dados e a distribuição geográfica, você pode implantar os aplicativos com a confiança de saber que seus dados estarão seguros em caso de desastre.

- **Previsibilidade** - uma solução com custo e desempenho previsíveis. A previsibilidade na nuvem permite que você avance com confiança.
	- **Previsibilidade de Desempenho** - se concentra em prever os recursos necessários para oferecer uma experiência positiva aos clientes. O dimensionamento automático, o balanceamento de carga e a alta disponibilidade são apenas alguns dos conceitos de nuvem que dão suporte à previsibilidade de desempenho.
	- **Previsibilidade de custos** - se concentra em prever o custo dos gastos com a nuvem. Operando na nuvem e usando a análise e as informações da nuvem, você pode prever custos futuros e ajustar os recursos conforme o necessário. Você pode até mesmo usar ferramentas como TCO (custo total de propriedade) ou a Calculadora de Preços para obter uma estimativa de possíveis gastos com a nuvem.

### Describe the benefits of security and governance in the cloud

- Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

- **Governança** - Se você estiver implantando IaaS ou SaaS, os recursos de nuvem vão dar suporte à governança e à conformidade. 
	- Itens como modelos de conjunto ajudam a garantir que todos os seus recursos implantados atendam aos padrões corporativos e aos requisitos regulatórios governamentais. 
	- atualização dos recursos implantados com os novos padrões à medida que são alterados. 
	- Sinalização de qualquer recurso que esteja fora de conformidade e fornece estratégias de mitigação. 
	- Dependendo do modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente.

-  **Segurança** - Se você quiser o controle máximo da segurança, a IaaS fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção.  Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de PaaS ou SaaS podem ser as melhores estratégias de nuvem para você.

### Describe the benefits of manageability in the cloud

- Escalar automaticamente a implantação de recursos com base na necessidade.
- Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
- Monitorar a integridade dos recursos e substituir automaticamente os recursos com falha.
- Receber alertas automáticos com base em métricas configuradas, de modo a ficar ciente do desempenho em tempo real.

### Microsoft Cloud Adoption Framework (CAF)

O Microsoft Cloud Adoption Framework para Azure é uma estrutura completa de ciclo de vida que permite que arquitetos de nuvem, profissionais de TI e tomadores de decisão de negócios alcancem suas metas de adoção de nuvem. Ele fornece práticas recomendadas, documentação e ferramentas que ajudam você a criar e implementar estratégias de negócios e tecnologia para a nuvem.

- **Strategy** - você define a justificativa do negócio e os resultados esperados da adoção. Você deve definir e documentar suas motivações por trás da adoção da nuvem, acordar resultados de negócios específicos com as partes interessadas e executivos, desenvolver um caso de negócios para validar modelos financeiros relevantes e escolher o primeiro projeto certo que pode ajudar a alinhar as motivações com os esforços técnicos necessários.

- **Plan** - você alinha planos de adoção acionáveis ​​com resultados de negócios. Você cria um inventário de seu patrimônio digital, estabelece planos para o alinhamento organizacional inicial e as formas de abordar as lacunas de prontidão de habilidades. Eventualmente, você desenvolve um plano de adoção da nuvem para gerenciar as mudanças planejadas em todo o estado digital, organização e habilidades.

- **Ready** - você prepara o ambiente em nuvem para as mudanças planejadas. Como parte da preparação da preparação, você revisa os guias de configuração do Azure, escolhe a opção mais apropriada para hospedar sua carga de trabalho na nuvem, expande-a para atender aos requisitos de plataforma do seu plano de adoção da nuvem e valida suas modificações em relação às práticas recomendadas do Azure.

- **Inovate** - você desenvolve novas soluções nativas da nuvem ou híbridas. A inovação pode fornecer o maior valor comercial ao desbloquear novas habilidades técnicas e expandir os recursos de negócios. Você deve chegar a um consenso sobre o valor comercial hipotético, considerar várias ferramentas do guia de inovação do Azure, adotar as práticas recomendadas como parte da arquitetura de nuvem e habilitar um ciclo de feedback eficaz em todo o processo de desenvolvimento de sua solução de nuvem.

O Azure CAF reúne as melhores práticas de adoção da nuvem e fornece um conjunto de ferramentas, orientações e narrativas para gerar os resultados de negócios desejados durante o processo de adoção da nuvem. Além das metodologias Estratégia, Planejar, Preparar e Inovação descritas acima, o CAF também inclui Migrar, Governar, Gerenciar e Organizar.

## 🔸 Describe cloud service types

### Describe infrastructure as a service (IaaS)

O IaaS (infraestrutura como serviço) é a categoria mais flexível de serviços de nuvem, pois oferece:

- O máximo de controle sobre os recursos de nuvem. 
- O provedor de nuvem é responsável por manter o hardware, a conectividade de rede (com a Internet) e a segurança física. 
- Você é responsável por todo o resto: 
	- instalação, configuração e manutenção do sistema operacional
	- configuração de rede
	- configuração de banco de dados e armazenamento e assim por diante. 

Com o IaaS, basicamente o hardware é alugado em um datacenter de nuvem, mas cabe a você decidir o que fazer com ele.

### Describe platform as a service (PaaS)

O PaaS é adequado para fornecer um ambiente de desenvolvimento completo sem a preocupação de manter toda a infraestrutura de desenvolvimento. Em um cenário de PaaS, você não precisa se preocupar com o licenciamento nem com a aplicação de patch em sistemas operacionais e bancos de dados.

- O provedor de nuvem é responsável por:
	- manter a infraestrutura física e o acesso à Internet, como no IaaS. 
	- o provedor de nuvem também mantém:
		- os sistemas operacionais
		- os bancos de dados 
		- ferramentas de desenvolvimento. 

### Describe software as a service (SaaS)

O SaaS (software como serviço) é o modelo de serviço de nuvem mais completo do ponto de vista do produto. Com o SaaS, você está essencialmente alugando ou usando um aplicativo totalmente desenvolvido. Embora o modelo de SaaS possa ser o menos flexível, ele também é o mais fácil de colocar em funcionamento. Ele requer a menor quantidade de conhecimento técnico ou experiência para o emprego total.

- Em um ambiente de SaaS, você é responsável: 
	- pelos dados que coloca no sistema
	- pelos dispositivos que permite que se conectem ao sistema
	- pelos usuários que têm acesso. 

O provedor de nuvem é responsável pela segurança física dos datacenters, pela energia, pela conectividade de rede e pelo desenvolvimento e aplicação de patch dos aplicativos.

### Identify appropriate use cases for each cloud service (IaaS, PaaS, SaaS)

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

🔝 [Voltar ao topo](#topo)

# <a name="Describe_Azure_architecture_and_services"></a> ☁️ Describe Azure architecture and services (35-40%)

## 🔸 Describe the core architectural components of Azure

### Describe Azure regional, regional pairs and sovereign regions

Os recursos são criados em regiões, que são diferentes localizações geográficas no mundo inteiro que contêm datacenters do Azure.

- **Azure regional**
	- Uma região é uma área geográfica do planeta que contém pelo menos um, mas possivelmente vários data centers próximos e conectados a uma rede de baixa latência. 
	- Essas regiões dão flexibilidade para aproximar os aplicativos dos usuários, não importa onde estejam. 
	- As regiões globais proporcionam maior escalabilidade e redundância. Elas também preservam a residência a interrupções dos dados de seus serviços.

- **Regional pairs**
	- Cada região do Azure é sempre emparelhada com outra região na mesma área geográfica a pelo menos 300 milhas (cerca de 480 km) de distância. Essa abordagem permite a replicação de recursos, como o armazenamento de VM, em uma geografia, o que ajuda a reduzir a probabilidade de interrupções devido a eventos como desastres naturais, conflitos civis, quedas de energia ou interrupções de rede física afetarem as duas regiões ao mesmo tempo.
	- O Azure atribui e controla os recursos de modo inteligente dentro de cada região para garantir que as cargas de trabalho sejam balanceadas corretamente.

- **Sovereign regions** - Regiões soberanas são instâncias do Azure isoladas da instância principal do Azure. Talvez seja necessário usar uma região soberana para fins legais ou de conformidade.
	- essas regiões são instâncias lógicas e físicas do Azure isoladas da rede, destinadas a parceiros e órgãos do governo dos EUA. Esses datacenters são operados por cidadãos selecionados dos EUA e incluem certificações de conformidade adicionais.

### Describe availability zones

Você pode usar as zonas de disponibilidade para executar aplicativos críticos e incorporar alta disponibilidade à arquitetura do aplicativo, colocalizando seus recursos de computação, armazenamento, rede e dados em uma zona de disponibilidade e replicando em outras zonas de disponibilidade.

As zonas de disponibilidade são destinadas, principalmente, a VMs, discos gerenciados, balanceadores de carga e bancos de dados SQL.

- **Serviços em zonas (Zonal services)**: você fixa o recurso a uma zona específica.
- **Serviços com redundância de zona (Zone-redundant services)**: a plataforma replica automaticamente entre zonas (por exemplo, armazenamento com redundância de zona, Banco de Dados SQL).
- **Serviços não regionais (Non-regional services)**: os serviços estão sempre disponíveis em geografias do Azure e são resilientes a interrupções em toda a zona, bem como a interrupções em toda a região.

### Describe Azure datacenters

A infraestrutura física do Azure começa com datacenters. Conceitualmente, os datacenters são iguais aos grandes datacenters corporativos. São instalações com recursos organizados em racks com energia, refrigeração e infraestrutura de rede dedicadas.

Como um provedor de nuvem global, o Azure tem datacenters em todo o mundo. No entanto, esses datacenters individuais não estão diretamente acessíveis. Os datacenters são agrupados em Regiões do Azure ou em Zonas de Disponibilidade do Azure projetadas para ajudá-lo a obter resiliência e confiabilidade para suas cargas de trabalho críticas para os negócios.

### - Describe Azure resources and resource groups

- **Recurso**: um item gerenciável disponibilizado por meio do Azure. VMs (máquinas virtuais), contas de armazenamento, aplicativos Web, bancos de dados e redes virtuais são exemplos de recursos.

- **Grupo de recursos**: um contêiner que armazena os recursos relacionados de uma solução do Azure. O grupo de recursos inclui os recursos que você deseja gerenciar como um grupo. Você decide quais recursos pertencem a um grupo de recursos com base no que faz mais sentido para sua organização.
	- Os grupos de recursos existem para ajudar a gerenciar e organizar seus recursos do Azure. 
	- Um grupo de recursos é um contêiner lógico para recursos implantados no Azure. Esses recursos são tudo o que você cria em uma assinatura do Azure, como VMs, instâncias do Gateway de Aplicativo do Azure e instâncias do Azure Cosmos DB. 
	- Todos os recursos precisam estar em um grupo, e um recurso pode ser um membro de apenas um grupo de recursos. 
	- Muitos recursos podem ser movidos entre grupos de recursos com alguns serviços que têm limitações ou requisitos específicos de movimentação. 
	- Os grupos de recursos não podem ser aninhados. 
	- Para que qualquer recurso possa ser provisionado, é necessário colocá-lo em um grupo de recursos.
	- Grupos de recursos também são um escopo para a aplicação de permissões de RBAC (Role-based Access Control). Ao aplicar permissões de RBAC a um grupo de recursos, você pode facilitar a administração e limitar o acesso, a fim de permitir apenas o que é necessário.

O Azure Resource Manager é o serviço de implantação e gerenciamento do Azure. Ele fornece uma camada de gerenciamento que lhe permite criar, atualizar e excluir recursos em sua conta do Azure. Você usa recursos de gerenciamento como controle de acesso, bloqueios e tags para proteger e organizar seus recursos após a implantação.

Se você excluir um grupo de recursos, todos os recursos contidos nele também serão excluídos.

Com o Resource Manager, você pode:

- Gerenciar sua infraestrutura por meio de modelos declarativos em vez de scripts. Um modelo do Resource Manager é um arquivo JSON que define o que você deseja implantar no Azure.
- Implantar, gerenciar e monitorar todos os recursos da sua solução como um grupo em vez de tratá-los individualmente.
- Reimplantar a solução durante o ciclo de vida de desenvolvimento e ter confiança de que os recursos serão implantados em um estado consistente.
- Definir as dependências entre os recursos para que eles sejam implantados na ordem correta.
- Aplicar o controle de acesso a todos os serviços porque o RBAC é integrado nativamente à plataforma de gerenciamento.
- Aplicar tags aos recursos para organizar de modo lógico todos os recursos em sua assinatura.
- Esclarecer a cobrança da organização exibindo os custos de um grupo de recursos que compartilham a mesma tag.

### Describe subscriptions

- Uma assinatura fornece a você acesso autenticado e autorizado a serviços e produtos do Azure. 
- As assinaturas são uma unidade de gerenciamento, cobrança e escala. As assinaturas permitem organizar logicamente seus grupos de recursos e facilitar a cobrança.
- Ela também permite que você provisione recursos. 
- Uma assinatura do Azure é uma unidade lógica de serviços do Azure que se vincula a uma conta do Azure, que é uma identidade no Azure AD (Azure Active Directory) ou em um diretório no qual o Azure AD confia.
- Uma conta pode ter uma ou várias assinaturas com diferentes modelos de cobrança e às quais você aplica diferentes políticas de gerenciamento de acesso.
-  Você pode usar as assinaturas do Azure para definir limites em relação a produtos, serviços e recursos do Azure. 
	- **Limite de cobrança**: Esse tipo de assinatura determina como uma conta do Azure é cobrada pelo uso do Azure. Você pode criar várias assinaturas para atender a diferentes tipos de requisitos de cobrança. O Azure gera relatórios de cobrança e faturas separados para cada assinatura, para que você possa organizar e gerenciar os custos.
	- **Limite de controle de acesso**: O Azure aplica políticas de gerenciamento de acesso no nível da assinatura, e você pode criar assinaturas separadas para refletir diferentes estruturas organizacionais. Um exemplo disso é que, em um negócio, você tem diferentes departamentos aos quais aplica políticas de assinatura do Azure distintas. Esse modelo de cobrança permite gerenciar e controlar o acesso aos recursos que os usuários provisionam com assinaturas específicas.
- Se você tiver várias assinaturas, poderá organizá-las em seções de fatura. Cada seção de fatura é um item de linha na fatura que mostra os encargos incorridos nesse mês. Por exemplo, você pode precisar de uma única fatura para sua organização, mas deseja organizar os encargos por departamento, equipe ou projeto.

### Describe management groups

- Você organiza as assinaturas em contêineres chamados grupos de gerenciamento e aplica suas condições de governança a esses grupos. 
- Se a organização tiver muitas assinaturas, talvez você precise de uma forma de gerenciar o acesso, as políticas e a conformidade com eficiência para essas assinaturas. 
- Os grupos de gerenciamento do Azure fornecem um nível de escopo acima das assinaturas. 
- Todas as assinaturas dentro de um grupo de gerenciamento herdam automaticamente as condições aplicadas ao grupo de gerenciamento. 
- Os grupos de gerenciamento fornecem gerenciamento de nível empresarial em larga escala, independentemente do tipo de assinaturas que você possa ter.

### Describe the hierarchy of resource groups, subscriptions, and management groups

- O nível mais alto desses componentes de arquitetura do Azure é o Grupo de Gerenciamento. 
	- **Grupos de Gerenciamento** contêm uma ou mais assinaturas. 
		- **Assinatura** pode ter muitos grupos de recursos, mas um grupo de recursos pode pertencer a apenas uma assinatura. 
			- **Grupos de Recursos** - Dentro das Assinaturas estão os Grupos de Recursos. Os Grupos de Recursos pertencem a exatamente uma Assinatura. 
				- **Recursos** (os serviços de nuvem do Azure) - podem ser agrupados em grupos de recursos.

- **Management groups** - O nível mais alto desses componentes de arquitetura do Azure é o Grupo de Gerenciamento (management groups). 
	- Management groups -> Subscriptions -> Resource groups	-> Resources
	- Management groups existem acima do nível de assinatura. 
	- Cada diretório recebe um único grupo de gerenciamento de nível superior conhecido como Root. 
	- Este é um único limite para a gestão. Se você tiver várias assinaturas, todas elas pertencerão ao grupo de gerenciamento de nível superior. 
	- Os grupos de gerenciamento também podem ser criados para um subconjunto de assinaturas, tornando possível gerenciar esse subconjunto de assinaturas em conjunto.
	- Usado para aplicar padrões e políticas em várias assinaturas do Azure
	- Os Grupos de Gerenciamento contêm uma ou mais assinaturas. 

- **Subscriptions** - Uma assinatura no Azure é um contêiner lógico usado para provisionar serviços em nuvem. 
	- As empresas podem criar várias assinaturas se os limites de assinatura única forem atingidos. 
	- Cada serviço em uma assinatura tem certos limites e, se houver necessidade de escala extremamente alta, mais de uma assinatura pode ser necessária. 
	- A outra razão para ter mais de uma assinatura é ter várias opções de pagamento. 
	- Você pode isolar recursos entre vários projetos ou departamentos em diferentes assinaturas. Eles ajudam você a organizar o acesso aos recursos do Azure e determinar como o uso de recursos é relatado, cobrado e pago.
	- Dentro das Assinaturas estão os Grupos de Recursos. 
	- Uma assinatura pode ter muitos grupos de recursos, mas um grupo de recursos pode pertencer a apenas uma assinatura. 
	
- **Resource Groups** - Eles são um bloco de construção que possibilita agrupar serviços relacionados para fornecer uma solução completa. 
	- Grupos de recursos são frequentemente usados ​​para agrupar recursos que compartilham o mesmo ciclo de vida de recursos. 
	- Você pode implantar recursos em várias regiões do Azure em um único grupo de recursos.
	- Os Grupos de Recursos pertencem a exatamente uma Assinatura. 
	- Os próprios recursos (os serviços de nuvem do Azure) podem ser agrupados em grupos de recursos.

## 🔸 Describe Azure compute and networking services

### Compare compute types, including container instances, virtual machines (VMs), and functions

A computação do Azure é um serviço de computação sob demanda para execução de aplicativos baseados em nuvem. Ela fornece recursos de computação, como discos, processadores, memória, rede e sistemas operacionais. Os recursos estão disponíveis sob demanda e normalmente podem ser disponibilizados em minutos ou até mesmo segundos. Você só paga pelos recursos utilizados e apenas pelo tempo que utilizar.

- **Máquinas virtuais** são emulações de software de computadores físicos. Elas incluem um processador virtual, memória, armazenamento e recursos de rede. As VMs hospedam um sistema operacional, e você pode instalar e executar o software como se fosse um computador físico. 
- **Instâncias de Contêiner** e o Serviço de Kubernetes do Azure são recursos de Computação do Azure que você pode usar para implantar e gerenciar contêineres. Contêineres são ambientes de aplicativos leves e virtualizados. Eles foram projetados para serem criados rapidamente, escalados horizontalmente e interrompidos dinamicamente. Você pode executar várias instâncias de um aplicativo em contêineres em um computador host.
- **Funções (serverless)** são ideais quando você está preocupado apenas com o código que executa o serviço, e não com a plataforma ou a infraestrutura subjacente. Elas costumam ser usadas quando você precisa executar um trabalho em resposta a um evento, um temporizador ou uma mensagem de outro serviço do Azure. O Azure tem duas implementações de computação sem servidor:
	- **Azure Functions**: o Functions pode executar o código praticamente em qualquer linguagem de programação moderna.
	- **Azure Logic Apps**: os aplicativos lógicos foram desenvolvidos em um designer baseado na Web e podem executar a lógica disparada pelos serviços do Azure sem escrever nenhum código.
		- Cada vez que um gatilho é acionado, o mecanismo de Aplicativos Lógicos cria uma instância de aplicativo lógico que executa as ações no fluxo de trabalho. Essas ações também podem incluir 
    	- conversões de dados
    	- controles de fluxo, como instruções condicionais
    	- instruções de comutação
    	- loops e ramificações.

### Describe VM options, including Azure Virtual Machines, Azure Virtual Machine Scale Sets, availability sets, and Azure Virtual Desktop

- **Máquinas virtuais** são emulações de software de computadores físicos.
- **Máquinas Virtuais de Spot** - permite aproveitar a capacidade não usada com uma economia de custos significativa. 
	- A qualquer momento que o Azure precisar da capacidade de volta, a infraestrutura do Azure removerá as Máquinas Virtuais de Spot do Azure. 
	- As Máquinas Virtuais de Spot do Azure são ótimas para cargas de trabalho que podem lidar com interrupções, como trabalhos de processamento em lotes, ambientes de desenvolvimento/teste, grandes cargas de trabalho de computação, entre outros.
- **Virtual Machine Scale Sets**
	- Permitem criar e gerenciar um grupo de VMs idênticas e com balanceamento de carga. 
	- Permitem que você gerencie, configure e atualize centralmente um grande número de VMs em minutos para fornecer aplicativos de alta disponibilidade. O número de instâncias de VM pode aumentar ou diminuir automaticamente em resposta à demanda ou a um agendamento definido.
	- Facilidade de criar e gerenciar várias VMs
	- Fornece alta disponibilidade e resiliência de aplicativo, distribuindo as VMs por zonas de disponibilidade ou domínios de falha
	- Permite que seu aplicativo dimensione automaticamente de acordo com as alterações de demanda de recursos
	- Funciona em larga escala
- **Availability sets** - Um conjunto de disponibilidade é um agrupamento lógico de VMs que permite que o Azure entenda como o seu aplicativo foi criado para fornecer redundância e disponibilidade. 
	- Recomenda-se que duas ou mais VMs sejam criadas para fornecer um aplicativo altamente disponível e para atender o SLA de 99,95% do Azure. 
	- Não há nenhum custo para o conjunto de disponibilidade em si, você paga apenas por cada instância de VM que criar.
- **Virtual Desktop** - A Área de Trabalho Virtual do Azure é um serviço de virtualização de aplicativos executado na nuvem.
	- Configurar uma implantação de várias sessões do Windows 10 ou 11 que forneça uma experiência completa do Windows com escalabilidade
	- Apresentar os Aplicativos do Microsoft 365 para Empresas e otimizá-los para execução em cenários virtuais com vários usuários
	- Fornecer áreas de trabalho virtuais do Windows 7 com Atualizações de Segurança Estendida gratuitas
	- Trazer seu RDS (Remote Desktop Service) existente, além de aplicativos e áreas de trabalho do Windows Server para qualquer computador
	- Virtualizar aplicativos e áreas de trabalho
	- Gerenciar áreas de trabalho e aplicativos de diferentes sistemas operacionais Windows e Windows Server com uma experiência de gerenciamento unificada
- **Azure Batch** - trabalhos em lotes paralelos e de HPC (computação de alto desempenho) de grande escala com a capacidade de dimensionar dezenas, centenas ou milhares de VMs.
	- Quando você estiver pronto para executar um trabalho, o Batch fará o seguinte:
		- Iniciar um pool de VMs de computação para você.
		- Instalar aplicativos e dados de preparo.
		- Executar trabalhos com todas as tarefas que você tiver.
		- Identificar falhas.
		- Colocar o trabalho em filas.
		- Reduzir verticalmente o pool conforme o trabalho for concluído.
		- Pode haver situações em que você precise de potência de computação bruta ou de potência de computação no nível de supercomputador. O Azure fornece esses recursos.

### Describe resources required for virtual machines

Ao criar uma VM no Azure, você também cria recursos para hospedar a VM. Esses recursos trabalham juntos para virtualizar um computador e executar o sistema operacional.

- Uma máquina virtual que fornece recursos de CPU e memória
- Uma conta de Armazenamento do Azure para armazenar os discos rígidos virtuais
- Discos virtuais para armazenar o sistema operacional, os aplicativos e os dados
- Uma VNET (rede virtual) para conectar a VM a outros serviços do Azure ou ao hardware local próprio
- Um adaptador de rede (network interface) para se comunicar com a VNET
- Um endereço IP público opcional para que seja possível acessar a VM

### Describe application hosting options, including the Web Apps feature of Azure App Service, containers, and virtual machines

- **Azure App Service** - O Serviço de Aplicativo permite que você crie e hospede aplicativos Web, trabalhos em segundo plano, back-ends de dispositivos móveis e APIs RESTful na linguagem de programação de sua escolha sem gerenciar a infraestrutura. Ele oferece dimensionamento automático e alta disponibilidade. O Serviço de Aplicativo é compatível com Windows e Linux e permite implantações automatizadas do GitHub, Azure DevOps ou qualquer repositório Git para dar suporte a um modelo de deploy contínuo.
	- Esse ambiente de PaaS (plataforma como serviço) permite que você se concentre no site e na lógica da API, enquanto o Azure manipula a infraestrutura para executar e dimensionar seus aplicativos Web.

- **Containers** - As Instâncias de Contêiner do Azure oferecem a maneira mais rápida e simples de executar um contêiner no Azure, sem a necessidade de gerenciar máquinas virtuais nem adotar serviços adicionais. Trata-se de uma oferta de PaaS (plataforma como serviço) que permite que você carregue contêineres, que ela executará para você.
	- Azure Container Instances - Aplicativos em contêineres executados no Azure sem o provisionamento de servidores ou de VMs.

- **Virtual machines** - Se os requisitos de hospedagem na Web não forem diretamente compatíveis com a plataforma de aplicativo Web do Azure, aproveite as máquinas virtuais para personalizar e controlar todos os aspectos do servidor Web. 

### Describe virtual networking, including the purpose of Azure Virtual Networks, Azure virtual subnets, peering, Azure DNS, Azure VPN Gateway, and Azure ExpressRoute

**Azure Virtual Networks** - As VNets (Redes Virtuais) do Azure são o bloco de construção fundamental da sua rede privada no Azure. Com as VNets, você pode criar redes virtuais complexas semelhantes a uma rede local, com benefícios adicionais da infraestrutura do Azure, como escala, disponibilidade e isolamento. As VNets do Azure permitem que os recursos do Azure se comuniquem com segurança entre si, com a Internet e com as redes locais.

As redes virtuais do Azure oferecem as seguintes funcionalidades de rede essenciais:

- Isolamento e segmentação
- Comunicação pela Internet
- Comunicação entre recursos do Azure
- Comunicação com os recursos locais
- Rotear tráfego de rede
- Filtrar tráfego de rede
- Conectar redes virtuais

**Azure virtual subnets** - Uma sub-rede é um intervalo de endereços IP na VNet. Você pode segmentar VNets em sub-redes de tamanhos diferentes, criando quantas sub-redes você precisar para organização e segurança dentro do limite de assinatura.

**Peering** - O network peering permite que os recursos em cada rede virtual se comuniquem entre si. Essas redes virtuais podem estar em regiões separadas, o que permite criar uma rede global interconectada por meio do Azure.

**Azure DNS** - Embora a comunicação possa ser habilitada usando endereços IP, é muito mais simples usar nomes que possam ser facilmente lembrados e que não sejam alterados.
- Serviços DNS públicos - resolvem nomes e endereços IP para recursos e serviços acessíveis pela Internet, como servidores Web.
- Serviços DNS privados - É um serviço de hospedagem para domínios de DNS que fornece resolução de nomes usando a infraestrutura do Microsoft Azure. 

**Azure VPN Gateway** - Acessa as Redes Virtuais do Azure por meio de gateways de VPN de alto desempenho. Um gateway de VPN é um tipo de gateway de rede virtual. Gateways de VPN são implantados em redes virtuais do Azure e habilitam a conectividade:
- Conecte datacenters on-premises a redes virtuais por meio de uma conexão site-to-site.
- Conecte dispositivos individuais a redes virtuais por meio de uma conexão point-to-site.
- Conecte redes virtuais a outras redes virtuais por meio de uma conexão network-to-network.

**Azure ExpressRoute** - No caso de ambientes em que você precisa de maior largura de banda e níveis de segurança ainda mais altos, o ExpressRoute fornece uma conectividade privada dedicada para o Azure que não passa pela Internet. 

### Define public and private endpoints

Convém habilitar recursos do Azure para que se comuniquem entre si com segurança. 

Você pode usar Endpoint services para se conectar a outros tipos de recursos do Azure, como bancos de dados SQL do Azure e contas de armazenamento. Essa abordagem permite vincular vários recursos do Azure às redes virtuais para melhorar a segurança e fornecer o encaminhamento ideal entre recursos.

- Private endpoints - Um endpoint privado é uma adaptador de rede que usa um endereço IP privado de sua rede virtual. Essa interface de rede conecta você de forma privada e segura a um serviço da plataforma do Azure Private Link . Ao habilitar um endpoint privado, você está trazendo o serviço para sua rede virtual. O tráfego de um ponto de extremidade privado para o serviço passa pela rede de backbone da Microsoft, eliminando a exposição da Internet pública.

- Public endpoint - 

## 🔸 Describe Azure storage services

Uma conta de armazenamento fornece um namespace exclusivo para os dados do Armazenamento do Microsoft Azure, que podem ser acessados de qualquer lugar do mundo por HTTP ou HTTPS. Os dados nesta conta são seguros, altamente disponíveis, duráveis e maciçamente escalonáveis.

### Compare Azure storage services

- **Azure Blob storage** - Serviço de armazenamento para objetos muito grandes, como arquivos de vídeo ou bitmaps. O Armazenamento de Blobs é ideal para:
	- Fornecimento de imagens ou de documentos diretamente a um navegador.
	- Armazenamento de arquivos para acesso distribuído.
	- Transmissão por streaming de áudio e vídeo.
	- Armazenamento de dados de backup e restauração, recuperação de desastres e arquivamento.
	- Armazenamento de dados para análise por um serviço local ou hospedado no Azure.
	- Armazenamento de até 8 TB de dados para máquinas virtuais.
- **Azure Files storage** - Compartilhamentos de arquivos que podem ser acessados e gerenciados como um servidor de arquivos.
- **Azure Queue storage** - Um armazenamento de dados para o enfileiramento de mensagens e a entrega confiável delas entre aplicativos.
- **Azure Table storage** - O armazenamento de tabela é um serviço que armazena dados estruturados não relacionais (também conhecidos como dados NoSQL estruturados) na nuvem, fornecendo um repositório de chave/atributo com um design sem esquema. 

### Describe storage tiers

- **Hot access tier**: otimizada para armazenar dados que são acessados com frequência (por exemplo, imagens de seu site).
- **Cool access tier**: otimizada para dados acessados com menos frequência e armazenados por pelo menos 30 dias (por exemplo, faturas de seus clientes).
- **Archive access tier**: adequada para dados acessados raramente e armazenados por pelo menos 180 dias, com requisitos de latência flexíveis (por exemplo, backups de longo prazo).

### Describe redundancy options

O Armazenamento do Azure sempre armazena várias cópias dos seus dados para que eles fique protegidos contra eventos planejados e não planejados, como falhas de hardware transitórias, interrupções de energia ou rede e desastres naturais.

Os fatores que ajudam a determinar qual opção de redundância você deve escolher incluem:

- Como os dados são replicados na região primária.
- Se os dados são replicados em uma segunda região que está geograficamente distante da região primária, para protegê-los contra desastres regionais.
- Se o aplicativo requer acesso de leitura aos dados replicados na região secundária, caso a região primária não esteja disponível.

Os dados em uma conta de Armazenamento do Azure são sempre replicados três vezes na região primária.

**Redundância na região primária**

- **Armazenamento com redundância local** - O LRS replica seus dados três vezes em um único data center na região primária. O LRS oferece pelo menos 11 noves de durabilidade (99,999999999%) dos objetos em um determinado ano.
	- O LRS é a opção de redundância de menor custo e oferece a menor durabilidade em comparação com outras opções. 
	- Protege seus dados contra falhas de unidade e rack do servidor.
- **Armazenamento com redundância de zona** - o ZRS (armazenamento com redundância de zona) replica os dados do Armazenamento do Azure de maneira síncrona em três zonas de disponibilidade do Azure na região primária. O ZRS oferece durabilidade para objetos de dados do Armazenamento do Azure de, pelo menos, 12 noves (99,9999999999%) em um dado ano.
	- Seus dados ainda podem ser acessados por operações de leitura e de gravação, mesmo em caso de não disponibilidade de uma zona.
	- A Microsoft recomenda usar o ZRS na região primária para cenários que exigem alta disponibilidade. 
	- O ZRS também é recomendado para restringir a replicação de dados em um país ou uma região para atender aos requisitos de governança de dados.

**Redundância em uma região secundária** 

Para aplicativos que exigem alta durabilidade, você pode optar por também copiar os dados em sua conta de armazenamento para uma região secundária que esteja a centenas de quilômetros de distância da região primária. Seus dados serão duráveis mesmo que haja uma interrupção regional completa ou um desastre no qual a região primária não possa ser recuperada.

A região secundária emparelhada é baseada nos Pares de Região do Azure e não pode ser alterada.

Por padrão, os dados na região secundária não ficam disponíveis para acesso de leitura ou gravação. Se a região primária ficar indisponível, você poderá optar por fazer failover para a região secundária. Após a conclusão do failover, a região secundária se tornará a região primária e você poderá ler e gravar os dados novamente.

- **Armazenamento com redundância geográfica** - O GRS copia seus dados de maneira síncrona três vezes em um único local físico na região primária usando LRS. Em seguida, ele copia os dados de maneira assíncrona em um único local físico na região secundária (o par da região) usando LRS. O GRS oferece durabilidade para objetos de dados do Armazenamento do Azure de, pelo menos, 16 noves (99,99999999999999%) em um dado ano.
- **Armazenamento com redundância de zona geográfica** - O GZRS combina a alta disponibilidade fornecida pela redundância entre zonas de disponibilidade com a proteção contra interrupções regionais fornecidas pela replicação geográfica. Os dados em uma conta de armazenamento GZRS são copiados entre três zonas de disponibilidade do Azure na região primária (semelhante ao ZRS) e são replicados em uma região geográfica secundária usando LRS para proteção contra desastres regionais. A Microsoft recomenda o uso do GZRS para aplicativos que exigem consistência, durabilidade e disponibilidade máximas, excelente desempenho e resiliência para recuperação de desastres. O GZRS foi projetado para fornecer pelo menos 16 noves (99,99999999999999%) de durabilidade dos objetos durante um determinado ano.

Esses dados estarão disponíveis para serem lidos somente se o cliente ou a Microsoft iniciar um failover da região primária para a secundária. Você habilitar o acesso de leitura à região secundária, seus dados estarão sempre disponíveis, mesmo que a região primária esteja sendo executada de maneira ideal. 
- Habilite o armazenamento com redundância geográfica com acesso de leitura (RA-GRS)
- Ou o armazenamento com redundância de zona com acesso de leitura (RA-GZRS).

### Describe storage account options and storage types

Uma conta de armazenamento fornece um namespace exclusivo para os dados do Armazenamento do Azure que podem ser acessados de qualquer lugar do mundo por HTTP ou HTTPS. Os dados nesta conta são seguros, altamente disponíveis, duráveis e maciçamente escalonáveis.

- **Uso geral v2 Standard** - Tipo de conta de armazenamento básico para blobs, compartilhamento de arquivos, filas e tabelas. Recomendado para a maioria dos cenários que usam o Armazenamento do Azure.  Armazenamento de Blobs (incluindo Data Lake Storage), Queue Storage, Table Storage e Azure Files.
- **Premium block blobs** - Tipo de conta de armazenamento Premium para blobs de blocos e blobs de acréscimo. Recomendado para cenários com altas taxas de transação ou que usam objetos menores ou exigem uma latência de armazenamento sempre baixa. Armazenamento de Blobs (incluindo Data Lake Storage)
- **Premium file shares** - Tipo de conta de armazenamento Premium somente para compartilhamentos de arquivos. Recomendadas para aplicações de escala empresarial ou de alto desempenho. Use esse tipo de conta caso deseje ter uma conta de armazenamento que dê suporte a compartilhamentos de arquivos SMB e NFS. Azure Files.
- **Premium page blobs** - Tipo de conta de armazenamento Premium somente para blobs de páginas.

**Storage account endpoints** -  ter um namespace exclusivo no Azure para seus dados.

### Identify options for moving files, including AzCopy, Azure Storage Explorer, and Azure File Sync

- **AzCopy** - O AzCopy é um utilitário de linha de comando que você pode usar para copiar blobs ou arquivos de/para uma conta de armazenamento. Com o AzCopy, você pode carregar arquivos, baixar arquivos, copiar arquivos entre contas de armazenamento e até mesmo sincronizar arquivos. A sincronização de blobs ou arquivos com o AzCopy é uma sincronização de apenas uma direção. Ao sincronizar, você designa a origem e o destino e o AzCopy copiará arquivos ou blobs nessa direção. 
- **Azure Storage Explorer** - O Gerenciador de Armazenamento do Azure é um aplicativo autônomo que fornece uma interface gráfica para gerenciar arquivos e blobs em sua Conta do Armazenamento do Azure. Ele funciona em sistemas operacionais Windows, macOS e Linux e usa o AzCopy no back-end para executar todas as tarefas de gerenciamento de arquivos e blobs. 
- **Azure File Sync** - é uma ferramenta que permite centralizar seus compartilhamentos de arquivos no serviço Azure Files e manter a flexibilidade, o desempenho e a compatibilidade de um servidor de arquivos do Windows. É quase como transformar o servidor de arquivos do Windows em uma rede de distribuição de conteúdo em miniatura.

### Describe migration options, including Azure Migrate and Azure Data Box

O Azure dá suporte à migração em tempo real de infraestrutura, aplicativos e dados usando o serviço Migrações para Azure, bem como a migração assíncrona de dados usando o Azure Data Box.

- **Azure Migrate:: Descoberta e avaliação**. Descubra e avalie servidores locais em execução em VMware, Hyper-V servidores físicos para se preparar para a migração para o Azure.
- **Azure Migrate: Migração de Servidor**. Migre VMs do VMware, VMs do Hyper-V, servidores físicos, outros servidores virtualizados e VMs da nuvem pública para o Azure.
- **Assistente de Migração de Dados**. O Assistente de Migração de Dados é uma ferramenta autônoma criada para avaliar SQL Servers. Ele ajuda a identificar possíveis problemas que bloqueiam a migração.
- **Azure Database Migration Service**. Migre bancos de dados locais para VMs do Azure executando SQL Server, Banco de Dados SQL do Azure ou Instâncias Gerenciadas de SQL.
- **Web app migration assistant**. É uma ferramenta autônoma para avaliar sites locais para migração para o Serviço de Aplicativo do Azure. 
- **Azure Data Box**. Use os produtos Azure Data Box offline para mover grandes quantidades de dados offline para o Azure.
	- O Azure Data Box é um serviço de migração física que ajuda a transferir grandes quantidades de dados de maneira rápida, barata e confiável. Um dispositivo de armazenamento Data Box proprietário que tem uma capacidade máxima de armazenamento de 80 terabytes. 
	- O Data Box é transportado entre o datacenter por meio de uma empresa regional. Uma caixa robusta protege o Data Box contra danos durante o transporte.
	- É ideal para transferir os tamanhos de dados maiores do que 40 TB em cenários com conectividade de rede limitada a inexistente.

## 🔸 Describe Azure identity, access, and security

### Describe directory services in Azure, including Azure Active Directory (Azure AD) and Azure Active Directory Domain Services (Azure AD DS)

O Azure AD (Azure Active Directory) é o serviço de gerenciamento de acesso e identidade baseado em nuvem da Microsoft. As organizações usam o Azure AD para permitir que os funcionários, convidados e outras pessoas façam logon e acessem os recursos.

O Azure AD simplifica a maneira como as organizações gerenciam a autorização e o acesso, fornecendo um único sistema de identidade para os aplicativos no local e na nuvem. 

- Pode ser sincronizado com o Active Directory local existente, sincronizado com outros serviços de diretório ou usado como serviço autônomo.
- O Azure AD também permite que as organizações habilitem com segurança o uso de dispositivos pessoais, como celulares e tablets, e habilitem a colaboração com parceiros de negócios e clientes.
- Pode ser configurado para exigir a autenticação multifator ao acessar recursos organizacionais importantes.
- Pode ser usado para automatizar o provisionamento de usuários entre o Windows Server AD existente e os aplicativos na nuvem
- Os desenvolvedores usam o Azure AD como abordagem baseada em padrões para adicionar o SSO (logon único) aos aplicativos, para que os usuários possam entrar com as credenciais preexistentes. 
	- **Single Sign-on**: o SSO (logon único) permite que você se lembre apenas de um nome de usuário e uma senha para acessar vários aplicativos. Uma única identidade é vinculada a um usuário, o que simplifica o modelo de segurança.
	- **Gerenciamento de aplicativo**: você pode gerenciar seus aplicativos de nuvem e locais usando o Azure AD. Recursos como Proxy de Aplicativo, aplicativos SaaS, o portal Meus Aplicativos e o logon único proporcionam uma experiência do usuário aprimorada.

- O Azure AD também fornece APIs que permitem que os desenvolvedores criem experiências de aplicativo personalizadas usando os dados organizacionais existentes.
- A Microsoft garante que o serviço esteja disponível globalmente. 
- Ajudar a protegê-lo detectando tentativas de conexão suspeitas sem custo adicional. Por exemplo, o Azure AD pode detectar tentativas de conexão de locais inesperados ou dispositivos desconhecidos.
	- **Gerenciamento de dispositivo**: além das contas de pessoas individuais, o Azure AD dá suporte ao registro de dispositivos. Também permite que políticas de Acesso Condicional baseadas no dispositivo restrinjam tentativas de acesso somente às provenientes de dispositivos conhecidos, independentemente da conta de usuário solicitante.
- Também inclui fornecer funcionalidades como redefinição de senha por autoatendimento (SSPR - Self-service password reset), autenticação multifator, uma lista personalizada de senhas banidas e serviços de bloqueio inteligente.

O Azure AD está disponível em quatro edições: Gratuito, Aplicativos do Office 365, Premium P1 e Premium P2.

- **Azure Active Directory Gratuito**. Permite que você administre usuários e crie grupos, sincronize com o Active Directory local, crie relatórios básicos, configure a alteração de senha self-service para usuários na nuvem e habilite o logon único no Azure, no Microsoft 365 e em muitos aplicativos de SaaS populares. A edição gratuita está incluída nas assinaturas do Office 365, Azure, Dynamics 365, Intune e Power Platform.
- **Aplicativos do Office 365**. Permite que você faça tudo o que está incluído na versão gratuita, além da redefinição de senha self-service (SSPR - Self-service password reset) para usuários na nuvem e write-back de dispositivo, o que oferece sincronização bidirecional entre os diretórios locais e o Azure AD. Está incluída nas assinaturas do Office 365 E1, E3, E5, F1 e F3.
- **Azure Active Directory Premium P1**. Inclui todos os recursos da edição gratuita e de Aplicativos do Office 365. Ele também dá suporte à administração avançada, como grupos dinâmicos, gerenciamento de grupo de autoatendimento, Microsoft Identity Manager (um conjunto de gerenciamento de acesso e identidade local) e recursos de write-back de nuvem, que permitem a redefinição de senha por autoatendimento (SSPR - Self-service password reset) para os usuários locais.
- **Azure Active Directory Premium P2**. O P2 oferece todos os recursos do Premium P1 e o Azure Active Directory Identity Protection para fornecer acesso condicional baseado em risco aos aplicativos e dados críticos da empresa. O P2 também oferece o Azure Active Directory Privileged Identity Management para descobrir, restringir e monitorar os administradores e o acesso aos recursos, bem como fornecer acesso just-in-time, quando necessário.

> Também existe uma opção para licenças de recurso de “Pagamento conforme o uso”. Você pode obter licenças de outros recursos separadamente, como o Azure Active Directory B2C. O B2C pode ajudar você a fornecer soluções de gerenciamento de acesso e identidade para seus aplicativos voltados ao cliente.

**Azure AD DS (Azure Active Directory Domain Services)** é um serviço que fornece serviços de domínio gerenciado, como ingresso no domínio, política de grupo, protocolo LDAP e autenticação Kerberos/NTLM. Assim como o Azure AD permite que você use serviços de diretório sem precisar manter uma infraestrutura de suporte, com Azure AD DS você obtém o benefício dos serviços de domínio sem a necessidade de implantar, gerenciar e corrigir DCs (controladores de domínio) na nuvem.

- Um domínio gerenciado do Azure AD DS permite que você execute aplicativos herdados na nuvem que não podem usar métodos de autenticação modernos ou nos quais você não deseja que as pesquisas de diretório sempre voltem para um ambiente de AD DS local. 
- Todas as identidades de usuário são gerenciadas no diretório AD DS (Active Directory Domain Services) local e as alterações são sincronizadas no Azure AD.
	
### Describe authentication methods in Azure, including single sign-on (SSO), multifactor authentication, and passwordless

Autenticação é o processo de estabelecer a identidade de uma pessoa ou serviço que deseja acessar um recurso.

A autorização é o processo de estabelecer o nível de acesso que uma pessoa ou um serviço autenticado tem. Especifica quais dados podem ser acessados e que a pessoa ou serviço pode fazer com eles.

- **Single sign-on (SSO)** - O SSO permite que você se lembre de apenas um nome de usuário e uma senha para acessar vários aplicativos. Uma única identidade é vinculada a um usuário, o que simplifica o modelo de segurança. À medida que os usuários trocam de funções ou saem de uma organização, as modificações de acesso são vinculadas àquela identidade, o que reduz consideravelmente o esforço necessário para alterar ou desabilitar contas.
- **Multifactor authentication** - é um processo em que o usuário deve fornecer uma forma adicional de identificação durante o processo de entrada. Exemplos incluem um código no telefone celular ou uma verificação de impressão digital.
- **Passwordless** - A autenticação sem senha precisa ser configurada em um dispositivo para poder funcionar. Por exemplo, seu computador é algo que você tem. Depois de registrado ou inscrito, o Azure agora sabe que ele está associado a você. Agora que o computador é conhecido, uma vez que você forneça algo que você saiba ou seja (como um PIN ou uma impressão digital), você poderá ser autenticado sem usar uma senha. 3 Tipos são oferecidos:
	- Windows Hello para Empresas - Credenciais biométricas e de PIN estão diretamente ligadas ao computador do usuário, o que impede o acesso de quem não seja o proprietário. 
	- Aplicativo Microsoft Authenticator - permitir que o telefone do funcionário se torne um método de autenticação sem senha.
	- Chaves de segurança FIDO2 - A FIDO (Fast Identity online) Alliance ajuda a promover padrões de autenticação aberta e a reduzir o uso de senhas como forma de autenticação. A FIDO permite que usuários e organizações aproveitem o padrão para entrar nos recursos sem usar nome de usuário nem senha, usando uma chave de segurança externa ou uma chave de plataforma incorporada a um dispositivo.

O **PIM (Privileged Identity Management)** é um serviço no Azure AD (Azure Active Directory) que permite gerenciar, controlar e monitorar o acesso a importantes recursos na sua organização. Esses recursos incluem os recursos no Azure AD, no Azure e em outros Microsoft Online Services, como o Microsoft 365 ou o Microsoft Intune.

O Privileged Identity Management fornece ativação de função baseada em tempo e aprovação para atenuar os riscos de permissões de acesso excessivas, desnecessárias ou que foram indevidamente utilizadas em recursos importantes. 

- Fornecer acesso privilegiado just-in-time ao Azure AD e aos recursos do Azure
- Atribua acesso com limite de tempo aos recursos usando as datas de início e término
- Exigir aprovação para ativar funções com privilégios
- Impor autenticação multifator para ativar qualquer função
- Usar justificativa para entender por que os usuários ativam
- Obter notificações quando as funções privilegiadas forem ativadas
- Realizar revisões de acesso para garantir que os usuários ainda precisem de funções
- Baixar o histórico de auditoria para auditoria interna ou externa
- Impede a remoção do último Administrador Global ativo e das atribuições de função do Administrador de Função com Privilégios
- Para usar esse recurso, é necessária uma licença do Azure AD Premium P2.

### Describe external identities and guest access in Azure

O Azure AD gerencia diferentes tipos de identidades: usuários, entidades de serviço, identidades gerenciadas (managed identities) e dispositivos (devices).

**Identidade de usuário (users)** é uma representação de algo gerenciado pelo Azure AD. Os funcionários e convidados são representados como usuários no Azure AD. Se você tiver vários usuários com as mesmas necessidades de acesso, pode criar um grupo. Use os grupos para conceder permissões de acesso a todos os membros do grupo, em vez de atribuir direitos de acesso individualmente.
- A colaboração do Azure AD B2B, um recurso dentro de identidades externas, inclui a capacidade de adicionar usuários convidados. Com a colaboração B2B, uma organização pode compartilhar de maneira segura aplicativos e serviços com usuários convidados de outra organização.

**Entidade de serviço (service principals)** é, essencialmente, uma identidade para um aplicativo. O aplicativo deve primeiro ser registrado no Azure AD para habilitar sua integração. Depois de registrada, uma entidade de serviço é criada em cada locatário do Azure AD em que o aplicativo é usado. A entidade de serviço habilita recursos principais, como autenticação e autorização do aplicativo, para recursos protegidos pelo locatário do Azure AD. Os desenvolvedores de aplicativos devem gerenciar e proteger as credenciais.

**Identidades gerenciadas** são um tipo de entidade de serviço gerenciada automaticamente no Azure AD que eliminam a necessidade de os desenvolvedores gerenciarem credenciais. As identidades gerenciadas fornecem uma identidade para os aplicativos usarem ao se conectar a recursos do Azure que dão suporte à autenticação do Azure AD e podem ser usadas sem nenhum custo extra. Há dois tipos de identidades gerenciadas: atribuída pelo sistema e atribuída pelo usuário.

- **Atribuída pelo sistema (System-assigned)**. Alguns serviços do Azure permitem que você habilite uma identidade gerenciada diretamente em uma instância de serviço. Quando você habilita uma identidade gerenciada atribuída pelo sistema, uma identidade é criada no Azure AD que está vinculada ao ciclo de vida dessa instância de serviço. Quando o recurso é excluído, o Azure exclui automaticamente a identidade para você. Por design, somente o recurso do Azure pode usar essa identidade para solicitar tokens do Azure AD.
	- Criada como parte de um recurso do Azure, como uma máquina virtual do Azure ou o Serviço de Aplicativo do Azure.
	- Ciclo de vida compartilhado com o recurso do Azure. Quando o recurso pai é excluído, a identidade gerenciada também é excluída.
	- Não pode ser compartilhada. Associada a um único recurso do Azure.
	- Casos de uso: Cargas de trabalho que estão contidas em um único recurso do Azure. Cargas de trabalho para as quais você precisa de identidades independentes, como um aplicativo executado em uma única máquina virtual.

- **Atribuída pelo usuário (User-assigned)**. Você também pode criar uma identidade gerenciada como um recurso autônomo do Azure. Depois de criar uma identidade gerenciada atribuída pelo usuário, é possível atribuí-la a uma ou mais instâncias de um serviço do Azure. Com as identidades gerenciadas atribuídas pelo usuário, a identidade é gerenciada separadamente dos recursos que a usam.
	- Criada como recurso autônomo do Azure.
	- Ciclo de vida independente. Precisa ser explicitamente excluída.
	- Pode ser compartilhada. Uma identidade gerenciada atribuída pelo usuário pode ser associada a mais de um recurso do Azure.
	- Casos de uso: Cargas de trabalho que são executadas em vários recursos e que podem compartilhar uma única identidade. Cargas de trabalho que precisam de pré-autorização para um recurso seguro como parte de um fluxo de provisionamento. Cargas de trabalho em que os recursos são reciclados com frequência, mas as permissões devem permanecer consistentes. Por exemplo, uma carga de trabalho em que várias máquinas virtuais precisam acessar o mesmo recurso.

**Identidade do dispositivo**. Fornece aos administradores informações que eles podem usar ao tomar decisões de acesso ou configuração. As identidades de dispositivo podem ser configuradas de diferentes modos no Azure AD.
- **Dispositivos registrados no Azure AD** - fornecer aos usuários suporte para cenários BYOD (Traga seu próprio dispositivo) ou de dispositivo móvel. Nesses cenários, o usuário pode acessar os recursos da organização usando um dispositivo pessoal. 
- **Ingressado no Azure AD**. Um dispositivo é ingressado no Azure AD por meio de uma conta organizacional, que é usada para entrar no dispositivo.
- **Dispositivos ingressados no Azure AD híbrido**. As organizações com implementações do Active Directory local podem se beneficiar da funcionalidade oferecida pelo Azure AD implementando dispositivos ingressados no Azure AD híbrido.

Registrar e ingressar dispositivos no Azure AD oferece aos usuários o SSO (Logon Único) para recursos baseados em nuvem. Além disso, os dispositivos ingressados no Azure AD se beneficiam da experiência de SSO para recursos e aplicativos que dependem do Active Directory local.

Os administradores de TI podem usar ferramentas como Microsoft Intune, um serviço baseado em nuvem que se concentra no MDM (mobile device management) e no MAM (mobile application management), para controlar como os dispositivos de uma organização são usados.

**External identities** - As Identidades Externas do Azure AD consistem em um conjunto de recursos que possibilitam que as organizações permitam o acesso a usuários externos, como clientes ou parceiros. Essa capacidade para usuários externos é habilitada por meio do suporte do Azure AD de provedores de identidade externos, como outros locatários do Azure AD, Facebook, Google ou provedores de identidade empresariais. Pode ser configurado para que os usuários externos possam entrar com suas contas sociais ou corporativas existentes.

Há duas Identidades Externas do Azure AD diferentes: B2B e B2C.

- **Colaboração B2B** permite que você compartilhe os aplicativos e recursos com usuários externos.
	- A colaboração B2B permite que você compartilhe os aplicativos e serviços da sua organização com usuários convidados de outras organizações, mantendo o controle sobre seus próprios dados.
	- A colaboração B2B usa um processo de convite e resgate.
	- Você também pode habilitar fluxos dos usuários de inscrição por autoatendimento para permitir que os usuários externos se inscrevam em aplicativos ou recursos. 
	- Depois que o usuário externo resgatar o convite ou concluir a inscrição, ele será representado no mesmo diretório que os funcionários, mas com um usuário do tipo convidado. 
	- Com o B2B, há suporte para SSO (logon único) em todos os aplicativos conectados ao Azure AD.

- **Gerenciamento de acesso B2C** é uma solução de gerenciamento de identidade para aplicativos voltados para o consumidor e para o cliente.
	- O Azure AD B2C é uma solução de CIAM (customer identity access management). O Azure AD B2C permite que usuários externos entrem com suas identidades preferenciais de conta social, corporativa ou local para obter o logon único para os aplicativos.
	- Ele cuida do dimensionamento e da segurança da plataforma de autenticação, do monitoramento e do tratamento automático de ameaças, como denial-of-service (DDoS), password spray ou ataques de força bruta.
	- Os usuários externos são gerenciados no diretório Azure AD B2C, separadamente do diretório de funcionários e parceiros da organização.
	- Também há suporte para SSO para os aplicativos de clientes nos locatário do Azure AD B2C.

> As Identidades Externas do Azure AD são um recurso das edições Premium P1 e P2 do Azure AD e os preços se baseiam em usuários ativos mensais. 

**Identidade híbrida** - Muitas organizações são uma mistura de aplicativos locais e em nuvem. Independentemente de um aplicativo ser hospedado localmente ou na nuvem, os usuários esperam e exigem acesso fácil. Essas soluções criam uma identidade de usuário comum para autenticação e autorização para todos os recursos, independentemente da localização. A Microsoft oferece várias maneiras de autenticar. 

Todas as identidades de usuário são gerenciadas no diretório AD DS (Active Directory Domain Services) local e as alterações são sincronizadas no Azure AD.

- **Azure AD Password hash synchronization**. Os usuários podem entrar nos serviços do Azure AD usando o mesmo nome de usuário e senha usados para entrar na instância do Active Directory local. O Azure AD lida com o processo de conexão dos usuários. Um benefício dessa abordagem é que a sincronização de hash de senha fornece autenticação de nuvem altamente disponível. 

- **Azure AD Pass-through authentication**. A autenticação de passagem do Azure AD permite que os usuários entrem em aplicativos locais e baseados em nuvem usando as mesmas senhas, como sincronização de hash de senha. Uma diferença importante é que a validação de senha não ocorre na nuvem. Isso pode ser um fator importante para as organizações que desejam impor suas políticas de segurança e senha do Active Directory local. A autenticação de passagem do Azure AD também usa o Azure AD Connect, mas tem o requisito adicional de executar um ou mais agentes de autenticação. Esses agentes servem como intermediários entre o Azure AD e o Active Directory local no processo de autenticação de usuários.
	- Quando um usuário tenta acessar um aplicativo ao qual ainda não está conectado, ele é redirecionado para inserir seu nome de usuário e senha. O Azure AD criptografará a senha do usuário com a chave pública do Agente de Autenticação. O Agente de Autenticação local valida o nome de usuário e a senha no Active Directory que avalia a solicitação e fornece uma resposta (sucesso, falha, senha expirada ou usuário bloqueado) de volta ao agente, que notifica o Azure AD. 
	- Dependência de agentes de autenticação em execução em servidores, é preciso considerar software e hardware distribuídos e redundantes para fornecer alta disponibilidade de solicitações de conexão.

- **Federated authentication**.  A federação é recomendada como uma autenticação para organizações que têm recursos avançados atualmente incompatíveis com o Azure AD, incluindo logon usando cartões inteligentes ou certificados, logon usando o servidor de MFA (autenticação multifator) local e logon usando uma solução de autenticação de terceiros.
	- O Azure AD entrega o processo de autenticação para um sistema de autenticação confiável separado, como os Serviços de Federação do Active Directory (AD FS) locais, para validar a senha do usuário. Esse método de entrada garante que toda a autenticação do usuário ocorra localmente.
	- A autenticação federada usa o Azure AD Connect, mas também requer servidores adicionais para dar suporte à federação, resultando em um volume de infraestrutura maior.
	- Organizações podem configurar a sincronização de hash de senha como um backup em caso de falha na infraestrutura do AD FS.

> Essas opções de autenticação híbrida exigem um Active Directory local. Além disso, o Azure AD Connect, um aplicativo da Microsoft local executado em um servidor, é necessário e serve como uma ponte entre o Azure AD e o Active Directory local. 

### Describe Azure AD Conditional Access

O Acesso Condicional é uma ferramenta que o Azure Active Directory usa para permitir (ou negar) o acesso a recursos com base em sinais de identidade. Esses sinais incluem quem é o usuário, onde ele está e de qual dispositivo está solicitando acesso.

O Acesso Condicional também proporciona uma experiência de autenticação multifator mais granular para os usuários. Por exemplo, um segundo fator de autenticação poderá não ser solicitado se o usuário estiver em uma localização conhecida. No entanto, ele poderá ser solicitado se os sinais de conexão do usuário forem incomuns ou se o usuário estiver em uma localização inesperada.

- **Associação de usuário ou grupo**. As políticas podem ser direcionadas a todos os usuários, grupos específicos de usuários, funções de diretório ou usuários convidados externos
- **Informações de localização nomeada**. Podem ser criadas usando intervalos de endereços IP e usadas ao tomar decisões sobre a política.
- **Dispositivo**. Os usuários com dispositivos de plataformas específicas ou marcados com um estado específico podem ser usados.
- **Aplicativo**. Os usuários que tentam acessar aplicativos específicos podem disparar diferentes políticas de acesso condicional.
- **Detecção de risco de entrada em tempo real**. A integração dos sinais ao Azure AD Identity Protection permite que as políticas de acesso condicional identifiquem comportamentos de entrada suspeita
- **Aplicativos de nuvem ou ações**. Os aplicativos de nuvem ou as ações podem incluir ou excluir aplicativos de nuvem ou ações do usuário que estarão sujeitas à política.
- Risco do usuário. O risco do usuário representa a probabilidade de que determinada identidade ou conta seja comprometida. O risco do usuário pode ser configurado para uma probabilidade alta, média ou baixa.

**Atribuições da política** controla o quem, o quê, e o onde da política de Acesso Condicional. Todas as atribuições são avaliadas com AND lógicos. Se você tiver mais de uma atribuição configurada, todas as atribuições deverão ser atendidas para disparar uma política.

**Decisão** é conhecida como a parte de controles de acesso da política de Acesso Condicional e define como uma política é imposta.

Quando a política de acesso condicional tiver sido aplicada, uma decisão informada será atingida para conceder acesso, bloquear acesso ou exigir verificação adicional. 

As políticas de acesso condicional podem ser direcionadas a membros de grupos ou convidados específicos. Por exemplo, você pode criar uma política para excluir todas as contas de convidado do acesso a recursos confidenciais. O acesso condicional é um recurso das edições pagas do Azure AD.

O acesso condicional é útil quando você precisa:

- Exija a MFA (autenticação multifator) para acessar um aplicativo, dependendo da função, da localização ou da rede do solicitante. Por exemplo, você pode exigir a MFA para administradores, mas não para usuários regulares ou pessoas que se conectam de fora da rede corporativa.
- Exigir acesso a serviços somente por meio de aplicativos cliente aprovados. Por exemplo, você pode limitar quais aplicativos de email podem se conectar ao serviço de email.
- Exigir que os usuários acessem seu aplicativo somente de dispositivos gerenciados. Um dispositivo gerenciado é um dispositivo que atende os padrões de segurança e conformidade.
- Bloquear o acesso de fontes não confiáveis, como o acesso de locais desconhecidos ou inesperados.

### Describe Azure role-based access control (RBAC)

O princípio de privilégios mínimos diz que você só deve conceder acesso até o nível necessário para concluir uma tarefa.

O gerenciamento de permissões para uma equipe inteira se tornaria tedioso. Em vez de definir os requisitos de acesso detalhados para cada indivíduo e atualizar os requisitos de acesso quando outros recursos forem criados ou novas pessoas entrarem na equipe, o Azure permite controlar o acesso por meio do RBAC do Azure (controle de acesso baseado em função do Azure).

As funções do Azure AD controlam permissões para gerenciar recursos do Azure AD. Por exemplo, permitir que contas de usuário sejam criadas ou informações de cobrança sejam exibidas. 

O controle de acesso baseado em função é aplicado a um escopo, que é um recurso ou um conjunto de recursos ao qual esse acesso se aplica.

- Um grupo de gerenciamento (uma coleção de várias assinaturas).
- Uma assinatura única.
- Um grupo de recursos.
- Um recurso individual.

O RBAC do Azure é imposto em qualquer ação iniciada em um recurso do Azure que passa pelo Azure Resource Manager. O Resource Manager é um serviço de gerenciamento que fornece um modo de organizar e proteger seus recursos de nuvem.

O RBAC do Azure não impõe permissões de acesso no nível do aplicativo nem dos dados.

- **Funções internas (Built-in roles)** - Há muitas funções internas do Azure AD, que são funções com um conjunto fixo de permissões.
	- **Administrador global**: têm acesso a todos os recursos administrativos no Azure Active Directory. 
	- **Administrador do usuário**: podem criar e gerenciar todos os aspectos de usuários e grupos. Também inclui a capacidade de gerenciar tíquetes de suporte e monitorar a integridade do serviço.
	- **Administrador de cobrança**: podem fazer compras, gerenciar assinaturas e tíquetes de suporte e monitorar a integridade do serviço.
	- O conjunto fixo de permissões incluídas nas funções internas (Built-in roles) não pode ser modificado.

- **Funções personalizadas (Custom roles)** - é uma coleção de permissões que podem ser escolhidas de uma lista predefinida. A lista de permissões para escolher são as mesmas permissões usadas pelas funções internas (Built-in roles). A diferença é que você pode escolher quais permissões deseja incluir em uma função personalizada (Custom roles).
	- É um processo de duas etapas. A primeira etapa envolve a criação de uma definição de função personalizada (Custom roles), uma coleção de permissões que você adiciona de uma lista predefinida. A segunda etapa é atribuir (assign) essa função (role) a usuários ou grupos criando uma atribuição de função (role assignment).

Uma atribuição de função (role assignment) concede ao usuário as permissões em uma definição de função, em um escopo especificado. 

Um escopo define o conjunto de recursos do Azure AD ao qual o membro da função tem acesso.

Uma função personalizada pode ser atribuída no escopo de toda a organização ou em um escopo de objeto (um único aplicativo). 

> As funções personalizadas exigem uma licença Azure AD Premium P1 ou P2.

**Categorias do Azure AD roles** - alguns serviços de Microsoft 365, como Exchange e Intune, desenvolveram sistemas de controle de acesso baseados em função próprios. As funções internas (Built-in roles) do Azure AD podem ser usadas para fins diferentes. Há três categorias amplas.

- **Usuários em funções específicas do Azure AD (Azure AD-specific roles)**: Essas funções concedem permissões para gerenciar recursos somente no Azure AD. Por exemplo, Administrador de Usuários, Administrador de Aplicativos, Administrador de Grupos concedem permissões para gerenciar recursos que residem no Azure AD.
- **Funções específicas do serviço (Service-specific roles)**: para os principais serviços do Microsoft 365, o Azure AD inclui funções específicas de serviço integradas que concedem permissões para gerenciar os recursos no serviço. Por exemplo, as funções internas do Azure AD para Administradores do Exchange, do Intune, do SharePoint e do Teams podem gerenciar recursos em seus respectivos serviços.
- **Funções entre serviços (Cross-service roles)**: há algumas funções no Azure AD que abrangem vários serviços. Por exemplo, o Azure AD tem funções relacionadas à segurança, como o Administrador de Segurança, que concedem acesso em vários serviços de segurança em Microsoft 365. Da mesma forma, na função Administrador de Conformidade, você pode gerenciar configurações relacionadas à Conformidade no Centro de Conformidade do Microsoft 365, no Exchange e assim por diante.

**Diferença entre o RBAC do Azure AD e o RBAC do Azure**

- RBAC do Azure AD – as funções do Azure AD controlam o acesso a recursos do Azure AD como usuários, grupos e aplicativos.
- RBAC do Azure: as funções do Azure controlam o acesso a recursos do Azure como máquinas virtuais ou armazenamento usando o Gerenciamento de Recursos do Azure.

### Describe the concept of Zero Trust

A Confiança Zero é um modelo de segurança que pressupõe o pior cenário e protege os recursos com essa expectativa. A Confiança Zero pressupõe uma violação desde o início e verifica cada solicitação como se ela tivesse sido originada em uma rede não controlada.

- Verificar de modo explícito – sempre autentique e autorize com base em todos os pontos de dados disponíveis.
- Usar o acesso com o mínimo de privilégios – limite o acesso do usuário com JIT/JEA (Just-In-Time e Just-Enough-Access), políticas adaptáveis baseadas em risco e proteção de dados.
- Pressupor a violação – minimize o raio de alcance e segmente o acesso. Verifique a criptografia de ponta a ponta. Use a análise para obter visibilidade, promover a detecção de ameaças e aprimorar as defesas.

Em vez de supor que um dispositivo é seguro porque está dentro da rede corporativa, ele requer que todos se autentiquem. Em seguida, concede acesso com base na autenticação e não na localização.

### Describe the purpose of the defense in depth model

O objetivo da defesa em profundidade é proteger as informações e impedir que elas sejam roubadas por pessoas que não estejam autorizadas a acessá-las.

Uma estratégia de defesa em profundidade usa uma série de mecanismos para reduzir o avanço de um ataque que busca obter acesso não autorizado aos dados.

- **Camadas da defesa em profundidade** - Cada camada fornece proteção, de modo que se uma camada for violada, uma camada seguinte já estará em vigor para impedir a exposição adicional. Essa abordagem elimina a dependência de qualquer camada única de proteção. Ela desacelera um ataque e fornece informações de alerta sobre as quais as equipes de segurança podem agir, automática ou manualmente.

- A camada de segurança física é a primeira linha de defesa para proteger o hardware de computação no datacenter.
- A camada de identidade e acesso controla o acesso à infraestrutura e ao controle de alterações.
- A camada de perímetro usa a proteção contra DDoS (ataque de negação de serviço distribuído) para filtrar ataques em grande escala antes que eles possam causar uma negação de serviço para os usuários.
- A camada de rede limita a comunicação entre recursos por meio de controles de acesso e segmentação.
- A camada de computação protege o acesso a máquinas virtuais.
- A camada de aplicativo ajuda a garantir que os aplicativos estejam seguros e livres de vulnerabilidades de segurança.
- A camada de dados controla o acesso aos dados corporativos e do cliente que você precisa proteger.

O Azure fornece ferramentas e recursos de segurança em todos os níveis do conceito de defesa em profundidade. Vamos examinar cada camada em mais detalhes:

- **Segurança física** - Proteger fisicamente o acesso a edifícios e controlar o acesso ao hardware de computação no datacenter é a primeira linha de defesa.
- **Identidade e acesso** - A camada de identidade e acesso refere-se a garantir que as identidades estejam seguras, que o acesso seja concedido apenas ao que é necessário e que os eventos de entrada e as alterações sejam registradas.
	- Controle o acesso à infraestrutura e o controle de alterações.
	- Usar o SSO (logon único) e a autenticação multifator.
	- Faça a auditoria de eventos e alterações.
- **Perímetro** - O perímetro da rede protege seus recursos contra ataques baseados na rede. Identificar esses ataques, eliminar o impacto e alertar quando eles ocorrem são maneiras importantes de manter a rede segura.
	- Usar a Proteção contra DDoS para filtrar ataques em grande escala antes que eles possam afetar a disponibilidade de um sistema para os usuários.
	- Use firewalls de perímetro para identificar e alertar sobre ataques maliciosos contra a rede. 
- **Rede** - Essa camada concentra-se em limitar a conectividade de rede entre todos os recursos para permitir apenas o necessário. Ao limitar essa comunicação, você reduz o risco de uma disseminação de ataques para outros sistemas na rede.
	- Limite a comunicação entre os recursos.
	- Negue por padrão.
	- Restringir o acesso à Internet de entrada e limitar o acesso de saída quando apropriado.
	- Implemente a conectividade segura com as redes locais.
- **Computação** - Malware, sistemas sem patches e sistemas sem proteção adequada abrem o ambiente para ataques. 
	- Proteger o acesso às máquinas virtuais.
	- Implementar o Endpoint Protection em dispositivos e manter os sistemas atualizados e com patches.
- **Aplicativo** - A integração da segurança no ciclo de vida de desenvolvimento do aplicativo ajuda a reduzir o número de vulnerabilidades introduzidas no código. 
	- Verificar se os aplicativos estão seguros e livres de vulnerabilidades.
	- Armazene os segredos de aplicativos confidenciais em uma mídia de armazenamento seguro.
	- Faça com que a segurança seja um requisito de design em todo o desenvolvimento do aplicativo.
- **Dados** - Quem armazena dados e controla o acesso a eles é responsável por garantir que estejam protegidos adequadamente. É comum que requisitos regulatórios determinem os controles e os processos que precisam estar em vigor para garantir a confidencialidade, a integridade e a disponibilidade dos dados. Em quase todos os casos, os invasores estão em busca de dados:
	- Armazenados em um banco de dados.
	- Armazenados em disco em máquinas virtuais.
	- Armazenados em aplicativos SaaS (software como serviço), como o Office 365.
	- Gerenciados por meio do armazenamento em nuvem.

### Describe the purpose of Microsoft Defender for Cloud

O Defender para Nuvem é uma ferramenta de monitoramento para gerenciamento da postura de segurança e proteção contra ameaças. Ele monitora seus ambientes de nuvem, locais, híbridos e de várias nuvens para fornecer diretrizes e notificações com o objetivo de fortalecer sua postura de segurança.

O Defender para Nuvem fornece as ferramentas necessárias para proteger seus recursos, acompanhar sua postura de segurança, proteger contra ataques cibernéticos e simplificar o gerenciamento de segurança. A implantação do Defender para Nuvem é fácil e já está integrada nativamente ao Azure

Se você também tiver um datacenter local ou estiver operando em outro ambiente de nuvem, o monitoramento dos serviços do Azure poderá não fornecer uma visão completa da sua situação de segurança.

Quando necessário, o Defender para Nuvem pode implantar automaticamente um agente do Log Analytics para coletar dados relacionados à segurança. Para computadores do Azure, a implantação é tratada diretamente. Em ambientes híbridos e de várias nuvens, os planos do Microsoft Defender são estendidos para computadores que não são Azure com a ajuda do Azure Arc. Os recursos do GPSN (gerenciamento da postura de segurança na nuvem) são estendidos para computadores de várias nuvens sem a necessidade de agentes.

O Defender para Nuvem preenche três necessidades vitais à medida que você gerencia a segurança de seus recursos e cargas de trabalho locais e na nuvem:

- Avaliação contínua – Conheça sua postura de segurança. Identifique e rastreie vulnerabilidades.
- Proteger – Proteja recursos e serviços com o Azure Security Benchmark.
- Defender – Detecte e resolva ameaças a recursos, cargas de trabalho e serviços.

### Sentinel

O Azure Sentinel é o sistema de SIEM (security information and event management) baseado em nuvem da Microsoft. Ele usa análise de segurança e análise de ameaças inteligentes. O sistema de SIEM agrega dados de segurança de várias fontes diferentes (contanto que essas fontes sejam compatíveis com um formato padrão aberto de registro em log).

O Azure Sentinel permite que você:

- **Coletar dados de nuvem em escala** - Colete dados de todos os usuários, dispositivos, aplicativos e infraestrutura, tanto locais quanto de várias nuvens.
- **Detectar ameaças não detectadas anteriormente** - Minimize falsos positivos usando a análise abrangente e a inteligência contra ameaças da Microsoft.
- **Investigar ameaças com inteligência artificial** - Examine atividades suspeitas em escala, aproveitando a longa experiência em segurança cibernética da Microsoft.
- **Responder a incidentes rapidamente** - Use a orquestração e a automação internas para tarefas comuns.

### Azure Key Vault

O Azure Key Vault é um serviço de nuvem centralizado para armazenar secrets de aplicativo em um só local centralizado. Ele oferece acesso seguro a informações confidenciais fornecendo controle de acesso e funcionalidades de registro em log.

O Azure Key Vault pode ajudar você a:

- **Gerenciar secrets** - Você pode usar o Key Vault para armazenar tokens, senhas, certificados, chaves de API e outros segredos e controlar com segurança o acesso a eles.
- **Gerenciar chaves de criptografia** - Você pode usar o Key Vault como uma solução de gerenciamento de chaves. O Key Vault facilita a criação e o controle das chaves de criptografia usadas para criptografar os dados.
- **Gerenciar certificados SSL/TLS** - O Key Vault permite provisionar, gerenciar e implantar certificados SSL/TLS públicos e privados para recursos do Azure e recursos internos.
- **Armazenar segredos com o suporte de HSMs (hardware security modules)** - Esses segredos e chaves podem ser protegidos por software ou por HSMs validados pelo FIPS 140-2 Nível 2.

### Host Dedicado

O Host Dedicado do Azure fornece servidores físicos dedicados para hospedar as VMs do Azure para Windows e Linux.

O Host Dedicado do Azure:

- Fornece visibilidade e controle sobre a infraestrutura de servidor que está executando as VMs do Azure.
- Ajuda a endereçar os requisitos de conformidade implantando as cargas de trabalho em um servidor isolado.
- Permite que você escolha o número de processadores, as funcionalidades do servidor, a série de VMs e os tamanhos de VM dentro do mesmo host.

Você é cobrado pelo host dedicado, independentemente do número de VMs implantadas. O preço do host é baseado na família, no tipo (tamanho do hardware) e na região da VM.

O licenciamento de software, o armazenamento e o uso de rede são cobrados separadamente do host e das VMs. Para obter mais informações.

🔝 [Voltar ao topo](#topo)

# <a name="Describe_Azure_management_and_governance"></a> ☁️ Describe Azure management and governance (30-35%)

## Describe cost management in Azure

### Describe factors that can affect costs in Azure

É importante saber como os custos são gerados no Azure para que você possa entender como suas decisões de compra e design da solução podem afetar o custo final. 

- **Tipos de assinaturas**
	- Avaliação gratuita (Free trial)
	- Pago conforme o uso (Pay-as-you-go) - As organizações também podem se candidatar a descontos por volume e a faturamento pré-pago.
	- Ofertas de membro - Sua associação existente a determinados produtos e serviços da Microsoft pode fornecer créditos para sua conta do Azure e taxas reduzidas nos serviços do Azure.
- **A maneira como comprar os serviços do Azure**
	- Contrato Enterprise (Enterprise Agreement) - Esse contrato os obriga a gastar um valor predeterminado nos serviços do Azure durante um período de três anos. O valor de serviço geralmente é pago anualmente. 
	- Diretamente da Web - comprar os serviços do Azure diretamente do site do portal do Azure e pagar os preços padrão.
	- Por meio de um Provedor de Soluções na Nuvem - Um CSP (Cloud Solution Provider) é um parceiro da Microsoft que ajuda você a criar soluções com base no Azure. 
- **Tipo de recurso** - dependem do tipo de recurso ou de como você o personaliza.
- **Uso de recursos** - você sempre será cobrado conforme o que usa.
- **Azure Marketplace** - Você também pode comprar soluções e serviços baseados no Azure de fornecedores terceirizados por meio do Azure Marketplace. As estruturas de cobrança são definidas pelo fornecedor.
- **O local ou o tráfego de rede**
	- Location - Regiões diferentes podem ter preços associados diferentes. 
	- Zonas para cobrança de tráfego de rede - A largura de banda refere-se aos dados que entram e saem dos datacenters do Azure. Algumas transferências de dados de entrada (dados que entram em datacenters do Azure) são gratuitas. Para transferências de dados de saída (dados que saem de data centers do Azure), o preço de transferência de dados é baseado em zonas.

### Compare the Pricing calculator and the Total Cost of Ownership (TCO) calculator 

- **Pricing calculator** - calculadora de preços fornece estimativas, não cotações de preços reais. Os preços reais podem variar conforme a data de compra, a moeda de pagamento que você está usando e o tipo de cliente do Azure que é.
- **Total Cost of Ownership (TCO) calculator** - ajuda a estimar a economia de custos de operar sua solução no Azure ao longo do tempo em comparação com a operação no datacenter local.

### Describe the Azure Cost Management and Billing tool

O Gerenciamento de Custos é um serviço gratuito que ajuda você a entender sua fatura do Azure, gerenciar sua conta e assinaturas, monitorar e controlar os gastos do Azure e otimizar o uso de recursos.

Os recursos de Gerenciamento de Custos incluem:

- **Relatórios** - Use dados históricos para gerar relatórios e prever o uso e as despesas futuras.
- **Enriquecimento de dados** - Melhore a responsabilidade classificando os recursos com tags que correspondam a unidades organizacionais e de negócios do mundo real.
- **Orçamentos** - Crie e gerencie orçamentos de custo e uso monitorando tendências de demanda de recursos, taxas de consumo e padrões de custo.
- **Alertas** - Obtenha alertas conforme seus orçamentos de custo e uso.
- **Recomendações** - Receba recomendações para eliminar recursos ociosos e otimizar os recursos do Azure que você provisiona.

### Describe the purpose of tags

As tags ajudam a gerenciar os custos associados aos diferentes grupos de produtos e recursos do Azure. Você pode aplicar tags a grupos de recursos do Azure para organizar dados de cobrança.

## 🔸 Describe features and tools in Azure for governance and compliance

### Describe the purpose of Azure Blueprints

Azure Blueprints fornece uma maneira de definir um conjunto repetitivo de recursos do Azure. O Azure Blueprints permite que equipes de desenvolvimento provisionem e executem novos recursos rapidamente, com o conhecimento de que estão alinhados com os requisitos de conformidade da organização.

- ajuda a garantir que os recursos do Azure sejam implantados de uma maneira que esteja de acordo com os requisitos de conformidade. 
- é uma forma declarativa de orquestrar a implantação de vários modelos de recursos e outros artefatos, tais como:
	- Atribuições de Funções
	- Atribuições de Políticas
	- Modelos do ARM (modelos do Azure Resource Manager)
	- Grupos de recursos
- Objetos de blueprint são replicados para várias regiões do Azure. Essa replicação oferece baixa latência, alta disponibilidade e acesso consistente a seus objetos de blueprint.

### Describe the purpose of Azure Policy

**Azure Policy** - O Azure Policy foi projetado para ajudar a reforçar os padrões e avaliar a conformidade em toda a sua organização.
-  Casos de uso comuns do Azure Policy incluem implementar a governança para consistência de recursos, conformidade regulatória, segurança, custo e gerenciamento.
- O Azure Policy avalia se as propriedades de recursos correspondem às regras de negócio. Essas regras de negócio são descritas usando o formato JSON e são chamadas de definições de política. 
- Para um gerenciamento simplificado, você pode agrupar várias regras de negócio para formar uma única iniciativa de política.
- Usado para monitorar continuamente os recursos e garantir uma continuação com os requisitos de conformidade.
- O Azure Policy avalia recursos em momentos específicos durante o ciclo de vida do recurso, o ciclo de vida de atribuição de política e para avaliação regular de conformidade contínua.
- Diferença entre as funções do Azure Policy e o controle de acesso baseado em função do Azure (RBAC)?
	-  Você usa o Azure Policy para garantir que o estado do recurso seja compatível com as regras de negócio de sua organização, independentemente de quem fez a alteração ou quem tem permissão para fazer alterações. O Azure Policy avaliará o estado de um recurso e agirá para garantir que o recurso permaneça em conformidade.
	- O RBAC do Azure gerencia quem tem acesso aos recursos do Azure, o que eles podem fazer com esses recursos e quais áreas eles podem acessar. Se as ações precisarem ser controladas, você usará o RBAC do Azure. 
	- Se um indivíduo tiver acesso para concluir uma ação, mas o resultado for um recurso que não está em conformidade, o Azure Policy ainda bloqueará a ação. 

### Describe the purpose of resource locks

- Um bloqueio de recurso (resource locks) impede que os recursos sejam excluídos ou alterados acidentalmente.
- Mesmo com as políticas do controle de acesso baseado em função do Azure (RBAC do Azure) em vigor, ainda há um risco de que as pessoas com o nível correto de acesso possam excluir recursos de nuvem críticos.
- Gerencie os bloqueios de recursos no portal do Azure, no PowerShell, na CLI do Azure ou em um modelo do Azure Resource Manager.
- Você pode aplicar bloqueios a uma assinatura, a um grupo de recursos ou a um recurso individual. É possível definir o nível de bloqueio como CanNotDelete ou ReadOnly.
	- CanNotDelete significa que as pessoas autorizadas ainda podem ler e modificar um recurso, mas não podem excluir o recurso sem antes remover o bloqueio.
	- ReadOnly significa que pessoas autorizadas podem ler um recurso, mas não podem excluir nem alterar o recurso. 

### Describe the purpose of the Service Trust Portal

O Service Trust Portal da Microsoft é um local que oferece acesso a vários conteúdos, ferramentas e outros recursos sobre práticas de segurança, privacidade e conformidade da Microsoft.Contém detalhes sobre a implementação de controles e processos da Microsoft que protegem nossos serviços na nuvem e os dados do cliente encontrados neles. 

Fornecem uma grande quantidade de informações de design e implementação de segurança. 

Setores & Regiões fornecem informações de conformidade específicas do setor e da região sobre os serviços do Microsoft Cloud.

## 🔸 Describe features and tools for managing and deploying Azure resources

### Describe the Azure portal

O portal do Azure fornece uma interface gráfica do usuário amigável para exibir todos os serviços que você está usando, criar serviços, configurar seus serviços e exibir relatórios. A portal do Azure é como a maioria dos usuários experimenta o Azure primeiro. 

### Describe Azure Cloud Shell, including Azure CLI and Azure PowerShell

- **Azure Cloud Shell** - é um shell interativo, autenticado e acessível pelo navegador para o gerenciamento de recursos do Azure. Ele dá a você a flexibilidade de escolher a experiência de shell que melhor se adequa ao modo como você trabalha, seja com o Bash ou o PowerShell. É uma ferramenta baseada na Web que permite executar cmdlets do PowerShell ou comandos da CLI do Azure depois de fazer logon no portal do Azure.
- **Azure PowerShell** - é um módulo que você pode instalar em seu computador para Windows, Linux ou macOS. Ele permite que você use cmdlets do PowerShell localmente para administrar recursos do Azure.
- **Azure CLI** - A CLI do Azure (interface de linha de comando do Azure) é um conjunto de comandos usado para criar e gerenciar recursos do Azure em seu computador. Foi criada para ajudar você a trabalhar de maneira rápida com ênfase na automação.

**Conceitos**

- O Cloud Shell é executado em um host temporário fornecido por sessão e por usuário
- O Cloud Shell atinge o tempo limite após 20 minutos sem atividade interativa
- O Cloud Shell exige que um compartilhamento de arquivos do Azure seja montado
- O Cloud Shell usa o mesmo compartilhamento de arquivos para o Bash e o PowerShell
- É atribuído ao Cloud Shell um computador por conta de usuário
- O Cloud Shell persiste o $HOME usando uma imagem de 5 GB mantida no compartilhamento de arquivos
- As permissões são definidas da mesma forma que para um usuário normal do Linux em Bash

> O computador que hospeda o Cloud Shell é gratuito, com um pré-requisito de um compartilhamento de Arquivos do Azure montado. Custos de armazenamento regulares se aplicam.

### Describe the purpose of Azure Arc

O Azure Arc é uma ponte que estende a plataforma do Azure para ajudar na criação de aplicativos e serviços com a flexibilidade de executar em datacenters, na borda e em ambientes multinuvem. Desenvolva aplicativos nativos de nuvem com um modelo consistente de desenvolvimento, operações e segurança. O Azure Arc é executado em hardware, virtualização e plataformas de Kubernetes, dispositivos IoT e sistemas integrados novos e existentes.

### Describe Azure Resource Manager and Azure Resource Manager templates (ARM templates)

- **Azure Resource Manager** é o serviço de implantação e gerenciamento do Azure. Ele fornece uma camada de gerenciamento que lhe permite criar, atualizar e excluir recursos em sua conta do Azure. Você usa recursos de gerenciamento como controle de acesso, bloqueios e tags para proteger e organizar seus recursos após a implantação. Quando um usuário envia uma solicitação de ferramentas, APIs ou SDKs do Azure, o Resource Manager recebe a solicitação. Ele autentica e autoriza a solicitação. O Resource Manager envia a solicitação para o serviço do Azure, que executa a ação solicitada. Como todas as solicitações são manipuladas por meio da mesma API, você verá funcionalidades e resultados uniformes em todas as diferentes ferramentas. Com o Resource Manager, você pode:

	- Gerenciar sua infraestrutura por meio de modelos declarativos em vez de scripts. Um modelo do Resource Manager é um arquivo JSON que define o que você deseja implantar no Azure.
	- Implantar, gerenciar e monitorar todos os recursos da sua solução como um grupo em vez de tratá-los individualmente.
	- Reimplantar a solução durante o ciclo de vida de desenvolvimento e ter confiança de que os recursos serão implantados em um estado consistente.
	- Definir as dependências entre os recursos para que eles sejam implantados na ordem correta.
	- Aplicar o controle de acesso a todos os serviços porque o RBAC é integrado nativamente à plataforma de gerenciamento.
	- Aplicar tags aos recursos para organizar de modo lógico todos os recursos em sua assinatura.
	- Esclarecer a cobrança da organização exibindo os custos de um grupo de recursos que compartilham a mesma tag.

- **Azure Resource Manager templates** - Embora seja possível escrever um código imperativo no Azure PowerShell ou na CLI do Azure para configurar e remover um recurso do Azure ou orquestrar uma infraestrutura contendo centenas de recursos, há um modo mais adequado de implementar essa funcionalidade. Ao usar os templates do ARM (Azure Resource Manager), você pode descrever os recursos que deseja usar em um formato JSON declarativo. O benefício é que todo o modelo do ARM é verificado antes de algum código ser executado para fazer com que os recursos sejam criados e conectados corretamente. Em seguida, o modelo orquestra a criação desses recursos em paralelo.

Os modelos podem até mesmo executar scripts do PowerShell e Bash antes ou depois da configuração de um recurso.

## 🔸 Describe monitoring tools in Azure

### Describe the purpose of Azure Advisor

O Azure Advisor avalia seus recursos do Azure e faz recomendações para ajudar a melhorar a confiabilidade, a segurança e o desempenho, alcançar a excelência operacional e reduzir os custos. O Assistente foi projetado para ajudar você a poupar tempo na otimização da nuvem. O serviço de recomendação inclui ações sugeridas que você pode adotar imediatamente, adiar ou ignorar.

As recomendações são divididas em cinco categorias:

- **Confiabilidade**: usada para garantir e aprimorar a continuidade dos seus aplicativos comercialmente críticos.
- **Segurança**: usada para detectar ameaças e vulnerabilidades que podem levar a violações de segurança.
- **Desempenho**: usado para aprimorar a velocidade de seus aplicativos.
- **Custo**: usado para otimizar e reduzir seus gastos gerais com o Azure.
- **Excelência operacional**: usada para ajudar você a obter eficiência de processo e fluxo de trabalho, gerenciamento de recursos e melhores práticas de implantação.

Você pode exibir o desempenho histórico e em tempo real em cada camada da arquitetura ou informações agregadas e detalhadas. 
 - Os dados são exibidos em diferentes níveis para públicos-alvo diferentes. 
 - É possível exibir relatórios de alto nível no painel do Azure Monitor ou criar modos de exibição personalizados usando consultas do Power BI e do Kusto.

Além disso, os dados podem ser usados para ajudar você a reagir a eventos críticos em tempo real, por meio de alertas entregues às equipes por SMS, email etc.

Outra opção é usar limites a fim de disparar a funcionalidade de dimensionamento automático para aumentar ou reduzir conforme a demanda.

Alguns produtos populares, como o **Application Insights** do Azure, um serviço para envio de informações de telemetria do código-fonte do aplicativo para o Azure, usam o Azure Monitor nos bastidores. Com o Application Insights, os desenvolvedores de aplicativos podem aproveitar a poderosa plataforma de análise de dados no Azure Monitor para ter insights aprofundados sobre as operações de um aplicativo e diagnosticar erros sem ter que esperar que um usuário os relate.

### Describe Azure Service Health

A Azure Service Health fornece uma exibição personalizada da integridade dos serviços, regiões e recursos do Azure dos quais você depende.

Você pode configurar alertas que ajudam a fazer a triagem de interrupções e manutenção planejada. Após uma interrupção, fornece relatórios oficiais de incidentes, chamados de RCAs (root cause analyses), que podem ser compartilhados.

O Service Health ajuda você a ficar atento a vários tipos de evento:

- **Problemas de serviço** são problemas no Azure, como interrupções, que afetam você no momento. 
- **Eventos de manutenção planejada** podem afetar sua disponibilidade. O Service Health permite que você escolha quando realizar a manutenção para minimizar o tempo de inatividade.
- **Health advisories** são problemas que exigem que você aja para evitar a interrupção do serviço, incluindo descontinuações de serviço e alterações significativas. Os comunicados de integridade são anunciados com antecedência para permitir que você se planeje.

### Describe Azure Monitor, including Log Analytics, Azure Monitor alerts, and Application Insights

- **Azure Monitor** - é uma plataforma para coleta, análise, visualização e potencial execução de ações com base dos dados de registro em log e de métrica de todo o ambiente do Azure e local.
	- Pode usar o dimensionamento automático para adicionar ou remover recursos conforme apropriado para minimizar os custos e garantir o desempenho. 

- **Log Analytics** - O Azure Monitor armazena dados de log em um workspace do Log Analytics, que é um recurso e um contêiner do Azure no qual os dados são coletados, agregados e servem como um limite administrativo.

- **Azure Monitor alerts** - Cada alerta ou notificação disponível no Azure Monitor é o produto de uma regra. Algumas dessas regras são internas da plataforma Azure. Use regras de alerta para criar notificações e alertas personalizados. O Azure Advisor integra-se à Central de Segurança do Azure para fornecer uma visão consolidada das recomendações para todos os recursos do Azure para ajudar a melhorar a relação custo-benefício, desempenho, alta disponibilidade e segurança dos recursos do Azure. Ele não permite que você monitore e avalie a conformidade com os padrões da empresa.

	- **Alertas de métricas** permitem que você tenha um gatilho de alerta quando um limite especificado é excedido. 
	- **Alertas de log de atividades (Activity log)** notificam você quando os recursos do Azure mudam de estado. Por exemplo, um alerta de log de atividades pode notificar você quando um recurso é excluído.
	- **Alertas de log** são baseados nos itens gravados nos arquivos de log. Por exemplo, um alerta de log pode notificar você quando um servidor Web retorna um número de respostas 404 ou 500.

- **Application Insights** - O Application Insights, um recurso do Azure Monitor, é um serviço de APM (gerenciamento de desempenho de aplicativos) extensível para desenvolvedores e profissionais de DevOps. Use-o para monitorar seus aplicativos ativos. Ele detecta automaticamente anomalias de desempenho e inclui ferramentas de análise avançadas para ajudar a diagnosticar problemas e entender o que os usuários realmente fazem com seu aplicativo. 
	- Instale um pacote de instrumentação pequeno (SDK) no seu aplicativo ou habilite o Application Insights usando o Agente do Application Insights quando essa opção for compatível. A instrumentação monitora seu aplicativo e direciona os dados de telemetria para um recurso do Azure Application Insights usando um GUID exclusivo ao qual nos referimos como uma chave de instrumentação.
	- Você pode instrumentar não apenas o aplicativo de serviço web, mas também todos os componentes em segundo plano e o JavaScript nas próprias páginas da web.

Ele monitora:
- **Request rates, response times e failure rates** - descubra quais páginas estão mais populares, em que momentos do dia, e onde os usuários estão. Confira as páginas que têm melhor desempenho. Se as taxas de falha e os tempos de resposta ficam altos quando há mais solicitações, possivelmente você tem um problema de alocação de recursos.
- **Dependency rates,  response times e failure rates** - descubra se os serviços externos estão atrasando você.
- **Exceptions** – analise as estatísticas agregadas ou escolha instâncias específicas e faça uma busca detalhada no rastreamento de pilha e nas solicitações relacionadas. A maioria das exceções de navegador e servidor são relatadas.
- Page views e load performance - relatados por navegadores dos usuários.
- Chamadas AJAX de páginas da web - rates, response times e failure rates.
- Contagens de seção e usuários.
- Contadores de desempenho de suas máquinas de servidor Linux ou Windows server, como CPU, memória e uso da rede.
- Diagnósticos de host do Docker ou do Azure.
- Logs de rastreamento de diagnóstico do seu aplicativo - para que você possa correlacionar eventos de rastreamento com solicitações.
- Métricas e eventos personalizados que você escreve em código de cliente ou servidor, para acompanhar os eventos de negócios, como itens vendidos ou vitórias.

## Outros

- A Política de Privacidade da Microsoft fornece informações relevantes sobre serviços específicos, incluindo a Cortana.
- A Política de Privacidade da Microsoft proporciona confiança na forma como a Microsoft coleta, protege e usa dados do cliente.

- A Central de Confiabilidade fornece documentação sobre padrões de conformidade e sobre como o Azure pode dar suporte à sua empresa.
- A Central de Confiabilidade é um excelente recurso para as pessoas de sua organização que podem desempenhar funções de segurança, privacidade e conformidade- .

- Os Termos dos Serviços Online são um contrato legal entre a Microsoft e o cliente que detalha as obrigações das duas partes em relação ao processamento e à segurança de dados do cliente e dados pessoais.

- A documentação de conformidade do Azure inclui informações detalhadas sobre a conformidade e os padrões legais e regulatórios no Azure.
- A documentação de conformidade fornece blueprints de referência, ou definições de política, para padrões comuns que podem ser aplicados à sua assinatura do Azure.

🔝 [Voltar ao topo](#topo)