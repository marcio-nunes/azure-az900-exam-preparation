# <a name="topo"></a>Preparação para o exame Azure AZ-900

☁️🔸

Depois de concluir este roteiro de aprendizagem, você poderá:

- Entenderá os benefícios da computação em nuvem e como ela pode poupar tempo e dinheiro
- Explicar conceitos de nuvem (alta disponibilidade, escalabilidade, elasticidade, agilidade e recuperação de desastre)
- Descrever os principais componentes da arquitetura (subscription, managment groups, resource e resource group)
- Resumir conceitos de distribuição geográfica (regiões do Azure, pares de regiões e zonas de disponibilidade)

1. [Princípios básicos do Microsoft Azure](#parte1)
2. [](#parte2)
3. [](#parte3)
4. [](#parte4)
5. [](#parte5)
6. [](#parte6)

# ☁️ <a name="parte1"></a>Princípios básicos do Microsoft Azure

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

**Nuvem pública** - Os serviços são oferecidos pela Internet pública e ficam disponíveis para qualquer pessoa que deseje comprá-los. Os recursos de nuvem são de propriedade e operados por um provedor de serviços de nuvem de terceiros e entregues pela Internet.

- Nenhuma despesa de capital para escalar verticalmente.
- Os aplicativos podem ser provisionados e desprovisionados rapidamente.
- As organizações pagam apenas pelo que utilizam.

**Nuvem privada** - Uma nuvem privada consiste em recursos de computação usados exclusivamente por usuários de uma empresa ou organização. Uma nuvem privada pode estar localizada fisicamente no datacenter (local) da organização ou ser hospedada por um provedor de serviços de terceiros.

- O hardware deve ser comprado para inicialização e manutenção.
- As organizações têm controle total sobre os recursos e a segurança.
- As organizações são responsáveis pela manutenção e pelas atualizações de hardware.

**Nuvem híbrida** - Uma nuvem híbrida é um ambiente de computação que combina uma nuvem pública e uma nuvem privada, permitindo que dados e aplicativos sejam compartilhados entre elas.

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

### IaaS - Infraestructure as a Seervice

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

### PaaS - Platform as a Service

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

### SaaS - Software as a Service

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

🔝 [Voltar ao topo](#topo)
🔼 [Voltar ao índice](#parte1)

---

### 🔸 <a name="parte1-3"></a> Princípios básicos do Microsoft Azure: Descrever as principais soluções e ferramentas de gerenciamento no Azure

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