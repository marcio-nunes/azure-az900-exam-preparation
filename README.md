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

## ☁️ <a name="parte1"></a>Princípios básicos do Microsoft Azure

1. [Descrever os principais conceitos do Azure](#parte1-1)
2. [Descrever os principais serviços do Azure](#parte1-2)
3. [Descrever as principais soluções e ferramentas de gerenciamento no Azure](#parte1-3)
4. [Descrever os recursos gerais de segurança de rede e segurança](#parte1-4)
5. [Descrever recursos de identidade, governança, privacidade e conformidade](#parte1-5)
6. [Parte 6: descrever contratos de nível de serviço e Gerenciamento de Custos da Microsoft](#parte1-6)

---
### 🔸<a name="parte1-1"></a> Princípios básicos do Microsoft Azure: descrever os principais conceitos do Azure 

[Link para o Microsoft Learn](https://docs.microsoft.com/pt-br/learn/paths/az-900-describe-cloud-concepts/)

Ao concluir este módulo, você poderá:

- Identificar os benefícios e as considerações do uso dos serviços de nuvem.
- Descrever as diferenças entre as categorias de serviços de nuvem.
- Descrever as diferenças entre os tipos de computação em nuvem.

## **Modelos de nuvem**

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

## Vantagens da computação em nuvem

- **Alta disponibilidade**: dependendo do SLA (Contrato de Nível de Serviço) que você escolher, seus aplicativos baseados em nuvem poderão oferecer uma experiência de usuário contínua, sem tempo de inatividade aparente, mesmo quando as coisas derem errado.

- **Escalabilidade**: os aplicativos na nuvem podem ser dimensionados verticalmente e horizontalmente:
    - **Dimensione verticalmente** para aumentar a capacidade de computação adicionando RAM ou CPUs a uma máquina virtual.
    - **Dimensionar horizontalmente** aumenta a capacidade de computação adicionando instâncias de recursos.

- **Elasticidade**: você pode configurar aplicativos baseados em nuvem para aproveitar o dimensionamento automático, de modo que os aplicativos sempre tenham os recursos de que precisam.

- **Agilidade**: implante e configure rapidamente os recursos baseados em nuvem à medida que os requisitos de aplicativo mudarem.

- **Distribuição geográfica**: você pode implantar aplicativos e dados em data centers regionais em todo o mundo, garantindo assim que os clientes sempre tenham o melhor desempenho em sua região.

- **Recuperação de desastre**: ao aproveitar os serviços de backup baseados em nuvem, a replicação de dados e a distribuição geográfica, você pode implantar os aplicativos com a confiança de saber que seus dados estarão seguros em caso de desastre.

## Despesas de capital vs. despesas operacionais

- **CapEx (despesas de capital)** são os gastos antecipados de dinheiro com a infraestrutura física e a posterior dedução dessas despesas antecipadas ao longo do tempo. 
O custo inicial de CapEx tem um valor que é reduzido ao longo do tempo. Como um investimento de capital foi feito, os contadores categorizam essa transação como uma CapEx. Ao longo do tempo, para considerar a vida útil limitada dos ativos, eles são depreciados ou amortizados.

- **OpEx (despesas operacionais)** são gastos atuais com serviços ou produtos, que são cobrados no ato. Você pode deduzir essas despesas no mesmo ano em que gasta. Não há nenhum custo antecipado, pois você paga por um serviço ou produto conforme o usa. Os serviços de nuvem são categorizados como uma OpEx devido ao seu modelo de consumo. Não há ativos a serem amortizados e o provedor de serviços de nuvem (Azure) gerencia os custos associados à compra e à vida útil do equipamento físico. Dessa forma, a OpEx tem impacto direto sobre o lucro líquido, a renda tributável e as despesas associadas no balanço.

Para resumir, a CapEx requer custos financeiros iniciais significativos, bem como despesas contínuas com suporte e manutenção. Por outro lado, a OpEx é um modelo baseado em consumo, portanto, você é responsável apenas pelo custo dos recursos de computação que usa.

Banefícios do modelo baseado em consumo:

- Sem custos prévios.
- Não há necessidade de comprar e gerenciar infraestrutura que seus usuários podem não usar ao máximo.
- A capacidade de pagar para obter recursos adicionais quando necessário.
- A capacidade de parar de pagar por recursos que não são mais necessários.

## Modelos de serviço de nuvem

### **IaaS - Infraestructure as a Seervice**

Esse modelo de serviço de nuvem é o mais próximo do gerenciamento de servidores físicos; um provedor de nuvem manterá o hardware atualizado, mas a manutenção do sistema operacional e a configuração da rede ficam a cargo do locatário da nuvem. 

Por exemplo, as máquinas virtuais do Azure são dispositivos de computação virtual totalmente operacionais em execução nos data centers da Microsoft. Uma vantagem desse modelo de serviço de nuvem é a implantação rápida de novos dispositivos de computação. A configuração de uma nova máquina virtual é consideravelmente mais rápida do que o processo de adquirir, instalar e configurar um servidor físico.

### **PaaS - Platform as a Service**

Esse modelo de serviço de nuvem é um ambiente de hospedagem gerenciado. O provedor de nuvem gerencia as máquinas virtuais e os recursos de rede e o locatário de nuvem implanta seus aplicativos no ambiente de hospedagem gerenciado. Por exemplo, os Serviços de Aplicativos do Azure fornecem um ambiente de hospedagem gerenciado em que os desenvolvedores podem carregar os aplicativos Web sem precisar se preocupar com os requisitos de software e hardware físico.

### **SaaS - Software as a Service**

Nesse modelo de serviço de nuvem, o provedor de nuvem gerencia todos os aspectos do ambiente de aplicativo, como as máquinas virtuais, os recursos de rede, o armazenamento de dados e os aplicativos. O locatário de nuvem só precisa fornecer seus dados para o aplicativo gerenciado pelo provedor de nuvem. Por exemplo, Microsoft Office 365 fornece uma versão totalmente funcional do Microsoft Office que é executada na nuvem. Você só precisa criar seu conteúdo e o Office 365 cuida de todo o resto.

![iaas-paas-saas](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/fundamental-azure-concepts/media/iaas-paas-saas-575a09e9.png)



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