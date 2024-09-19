# lab-azure-900

## Módulo 1 - Definição de Cloud Computing, Modelos e Benefícios

A computação em nuvem é o fornecimento de serviços de computação pela Internet, permitindo inovação rápida, recursos flexíveis e economia de escala.

### Benefícios da Computação em Nuvem

- **Alta Disponibilidade**: Garantia de tempo de atividade.
- **Escalabilidade**: Escalar verticalmente (mais poder) ou horizontalmente (mais instâncias).
- **Elasticidade**: A capacidade de adicionar ou remover recursos conforme necessário.
- **Agilidade**: Provisão rápida de novos recursos.
- **CapEx e OpEx**: Modelo de despesas de capital e operacionais.
- **Gerenciamento de Capacidade**: Ajuste dinâmico conforme o uso.
- **Ponto de Restauração Global**: Capacidade de replicar dados em várias regiões.
- **Segurança**: Provedores de nuvem oferecem ferramentas para monitoramento e proteção de dados.

### Modelos de Nuvem

#### Nuvem Privada
- Mantida por uma única organização, com controle total.
- **Vantagem**: Segurança e personalização.
- **Desvantagem**: Custo elevado de manutenção.

#### Nuvem Pública
- Serviços oferecidos via Internet por terceiros.
- **Vantagem**: Custo menor e elasticidade.
- **Desvantagem**: Menor controle sobre a infraestrutura.

#### Nuvem Híbrida
- Combina os dois tipos, conectando nuvens privadas e públicas.
- **Vantagem**: Flexibilidade e inovação com segurança.

### Tipos de Serviços de Nuvem

#### IaaS (Infrastructure as a Service)
- Provisão de máquinas virtuais, armazenamento e redes.
- Exemplos: **Azure Virtual Machines**, **Azure Storage**.

#### PaaS (Platform as a Service)
- Plataforma gerenciada para desenvolvimento e implantação de aplicativos.
- Exemplos: **Azure App Service**, **Azure SQL Database**.

#### SaaS (Software as a Service)
- Software disponível via internet, sem gerenciamento da infraestrutura.
- Exemplos: **Microsoft 365**, **Dynamics 365**.

## Comparação entre CapEx e OpEx

- **CapEx**: Gasto em infraestrutura física, com valor depreciando ao longo do tempo.
- **OpEx**: Gastos variáveis com serviços sob demanda, pagamento conforme uso.

---

## Módulo 2 - Arquitetura e Serviços Principais do Azure

### Regiões e Zonas de Disponibilidade

- **Regiões**: Locais físicos onde datacenters estão localizados.
- **Zonas de Disponibilidade**: Conjuntos de datacenters isolados em uma mesma região para alta disponibilidade.

#### Pares de Regiões
- Cada região tem um par em outra localização para redundância e recuperação de desastres.

### Recursos Principais de Computação

#### Máquinas Virtuais (VMs)
- Emulação de computadores físicos com controle total sobre o sistema operacional.

#### Contêineres
- Ambientes isolados para executar aplicativos sem gerenciar VMs completas.

#### Azure Kubernetes Service (AKS)
- Gerenciamento e orquestração de contêineres.

#### Azure App Services
- Serviço PaaS para hospedagem de aplicativos web.

#### Azure Functions
- Serviço de computação serverless para executar código sob demanda.

### Armazenamento no Azure

#### Tipos de Armazenamento
- **Blob Storage**: Armazenamento de objetos não estruturados, como imagens e vídeos.
- **Disk Storage**: Armazenamento gerenciado de discos para VMs.
- **File Storage**: Armazenamento de arquivos com suporte a SMB.
- **Queue Storage**: Armazenamento para enfileiramento de mensagens.
- **Table Storage**: Armazenamento de dados estruturados sem esquema.

#### Classes de Acesso
- **Camada Quente**: Dados acessados frequentemente.
- **Camada Fria**: Dados acessados ocasionalmente.
- **Camada de Arquivamento**: Dados raramente acessados.

### Rede no Azure

#### Virtual Networks (VNet)
- Rede privada no Azure que permite a comunicação entre diferentes recursos, como VMs.

#### Sub-redes
- Segmentação lógica de redes virtuais para isolar grupos de recursos.

#### VPN Gateway
- Conexão segura entre redes on-premise e o Azure.

#### Azure ExpressRoute
- Conexão privada dedicada entre sua infraestrutura e o Azure, sem passar pela internet.

#### Azure Load Balancer
- Balanceamento de carga de tráfego entre várias instâncias de VMs.

#### Application Gateway
- Balanceamento de carga com funcionalidades adicionais, como firewall e roteamento baseado em URL.

---

## Módulo 3 - Segurança, Privacidade, Conformidade e Confiança no Azure

### Serviços de Segurança

#### Azure Firewall
- Firewall gerenciado para proteger os recursos da nuvem.

#### Network Security Groups (NSG)
- Controle de tráfego de rede nas VMs.

#### Azure DDoS Protection
- Proteção contra ataques de negação de serviço distribuída.

#### Azure Security Center
- Ferramenta de monitoramento para proteger e gerenciar a segurança dos recursos.

### Identidade e Acesso

#### Azure Active Directory (AAD)
- Serviço de gerenciamento de identidade e autenticação.

#### Multi-Factor Authentication (MFA)
- Autenticação de dois fatores para maior segurança.

#### Conditional Access
- Define condições para o acesso de usuários, como localização ou dispositivo.

### Governança e Conformidade

#### Azure Policy
- Ferramenta que ajuda a aplicar regras e padrões nos recursos do Azure.

#### Role-Based Access Control (RBAC)
- Controle de acesso baseado em funções para gerenciar permissões em diferentes níveis.

#### Azure Blueprints
- Modelos para padronizar a implantação de recursos de acordo com requisitos de conformidade.

#### Trust Center
- Centro de transparência e conformidade de segurança da Microsoft.

---

## Módulo 4 - Preços e SLAs

### Fatores que Impactam o Custo

- **Tipos de Recurso**: O custo varia com base no serviço utilizado (VM, armazenamento, rede).
- **Localização**: O preço pode variar entre diferentes regiões do Azure.
- **Largura de Banda**: Custos com a transferência de dados entre regiões.

### Calculadora de Preços do Azure

- Ferramenta para estimar os custos dos serviços antes de utilizá-los.

### Preço Baseado em Consumo (Pay-as-You-Go)

- O modelo padrão de pagamento no Azure, onde você paga apenas pelo que consome.

### Benefícios de Economia de Custos

- **Azure Reservations**: Desconto em serviços ao comprometer-se com um período de uso de longo prazo.
- **Azure Hybrid Benefit**: Economia ao usar licenças existentes do Windows Server e SQL Server no Azure.

### Acordo de Nível de Serviço (SLA)

- SLA define o tempo de atividade garantido para cada serviço.
- **Exemplo**: Um SLA de 99,9% garante menos de 9 horas de inatividade por ano.

### Monitoramento e Otimização de Custos

- **Azure Cost Management**: Ferramenta para analisar e otimizar os gastos com o Azure.

---

## Módulo 5 - Suporte e Lifecycle de Recursos no Azure

### Planos de Suporte do Azure

- **Basic**: Gratuito, com acesso a documentação e suporte para faturamento.
- **Developer**: Suporte técnico durante horário comercial.
- **Standard**: Suporte técnico 24x7.
- **Professional Direct**: Acesso a engenheiros de suporte com tempos de resposta mais rápidos.

### Ciclo de Vida dos Recursos

- Serviços podem estar em **Versão Prévia**, **Geralmente Disponíveis (GA)**, ou podem ser **Descontinuados**.
- Serviços em versão prévia não têm SLA.

 

