# -resumo-do-lab
Este repositório é dedicado ao resumo de lições aprendidas durante o desenvolvimento do LAB da DIO.

# Introdução a computação em Nuvem:

## O que é computação em nuvem? 

Computação em nuvem ou Cloud Computing, pode ser definida como um modelo de de fornecimento de serviços de tecnologia da informação (TI) pela internet. Onde empresas,usuários acessem recursos como servidores,aramazenamentos,banco de dados,rede,software sem a necessidade de possuir uma estrutura física propria. 

## Modelos de implantação Nuvem?

### On-Premise (Local):

O modelo On-Premise faz referência a um modelo de infraestrutura física com uma abordagem "tradicional" onde uma organização  mantém e gerência toda a infraestrtura de TI,incluindo todo seus recursos de TI sendo; Servidores,redes,sistemas. Em vez de alugar ou terceirizar recursos para provedores de Nuvem.

### Modelo Cloud (Nuvem):

O modelo Cloud (computação em Nuvem) é um modelo de fornecimento de serviços de TI que permite acessar e usar recursos computacionais pela internet, sem a necessidade de manter uma infraestrutura fÍsica própria. Isso unclui armazenamento, servidores,bancos de dados,redes e softwares.

### Modelo Hybrid: 

 O modelo hÍbrido é o melhor dos dois mundos. É a união On-Premise + Modelo cloud. Pois neste modelo se beneficia da Nuvem Pública E da Nuvem privada(Local).

Logo, é possível usufluir dos serviços de nuvem para outras operações, criando uma combinação de recursos internos e externos. Como por exemplo; Armazenar e processar dados Sensíveis em uma nuvem privada,garantindo maior segurança e controle.

### CAPEX vs OPEX – Diferenças e Impacto na Computação em Nuvem:

- **CAPEX:**
  
  CAPEX são despesas de capital, ou seja, investimentos em bens físicos ou infraestrutura de longo prazo.

 **Exemplos** de CAPEX em TI:
 
 Compra de servidores, roteadores e equipamentos de data center
 Construção ou expansão de um prédio para TI
 Compra de licenças de software vitalícias
 Aquisição de storage físico (HDDs, SSDs, NAS)
 
- **OPEX:**
  
  OPEX são despesas operacionais, ou seja, custos recorrentes para manter operações funcionando.

 **Exemplos** de OPEX em TI:
 
 Pagamento de serviços de nuvem (AWS, Azure, Google Cloud)
 Assinaturas de software (SaaS) – como Microsoft 365, Salesforce
 Custos de energia e manutenção de data centers
 Salários da equipe de TI Serviços de terceiros (Suporte, Consultoria, Segurança)

## O que é "As a Service"?

Podemos definir como um modelo de entrega de tecnologia onde serviços são oferecidos sob demanda via Internet, em vez de serem adquiridos e mantidos localmente. As tecnologias oferecidas podem sem ser como; recursos,plataformas ou softwares sendo fornecidos sob demanda pela internet.
 Neste modelo permite que emrpesas e indivíduos *paguem apenas pelo que utilizam* aumentando a flexibilidade,escalabilidade e reduzindo custos operacionais. Ele abrange desde infraestrutura **(IaaS)** e plataformas de desenvolvimento **(PaaS)** até softwares prontos para uso **(SaaS)** e outros serviços especializados.

### O que é "plataform"?

Pode ser definida como um ambiente oline que fornece recursos para o desenvolvimento,teste,implantação e gerenciamento de aplicativos,sem que o usuário precise gerenciar servidores,armazenamento ou infraestrutura de rede.

Exemplos: Microsoft Azure App Service,Aws.

### O que são Cloud Regions (Regiões de Nuvem)?

Uma Região de Nuvem (Cloud Region) é um conjunto geográfico onde os provedores de nuvem (AWS, Azure, Google Cloud) oferecem seus serviços. Cada região contém várias zonas de disponibilidade e está fisicamente separada de outras regiões.

- Exemplos de Regiões:

 **AWS:** us-east-1 (Norte da Virgínia), sa-east-1 (São Paulo)

**Azure:** Brazil South (São Paulo), East US

**Google Cloud:** southamerica-east1 (São Paulo), us-west1 (Oregon)

Diante disso a importância das regiões onde se escolhe armazenar seus Dados,respeitando leis e regulamentaçõees locais. Pode melhorar a **latência** garantindo que usuários acessem serviços e servidores mais próximos. Somando-se a isso, oferecem redundância,caso uma região tenha problemas, loutra pdoe ser usada como Backup.

### O que são Availability Zones (Zonas de Disponibilidade)?

Uma Zona de Disponibilidade (AZ - Availability Zone) é uma área isolada dentro de uma região, com data centers independentes, mas conectados por redes de alta velocidade.

 - Cada região tem pelo menos duas ou mais zonas de disponibilidade.
 -  Cada AZ tem energia, refrigeração e rede independentes, garantindo que uma falha em uma zona não afete as outras.


### Modelos de serviço Nuvem:

Os serviços em nuvem são divididos em três categorias principais:

- IaaS (Infrastructure as a Service):

A IaaS (Infrastructure as a Service) é um modelo específico dentro da computação em nuvem. 
 Onde fornece recursos de infraestrutura sob demanda,como servidores,aramazenamento,rede e máquinas virtuais,sem que a empresa precise de comprar ou manter hardware físico.

- PaaS (Platform as a Service):

Ambiente de desenvolvimento completo, com ferramentas para criar, testar e implantar aplicações sem gerenciar servidores.

Exemplo: Azure App Services, Google App Engine, AWS Elastic Beanstalk.

- SaaS (Software as a Service):

Softwares prontos para uso, acessíveis via navegador.

Exemplo: Microsoft 365, Google Workspace, Dropbox.
 


## Beneficios de se trabalhar com Nuvem:

### Alta disponibilidade (High Availability - HA):

A alta disponibilidade é a capacidade de um sistema continuar funcionando sem interrupções significativa, assim garantindo o minímimo de tempo de inatividade (downtime).

Ela é um conceito essencial na computação em Nuvem que garante que sistemas,aplicações e serviços permaneçam operacionais mesmo diante de falhas ou picos de demanda.
( A nuvem permite distribuir cargas de trabalho entre diferentes servidores  e data centers, reduzindo o risco de indiponibilidaee e aumentando a resiliência dos sistemas.)
  
### 1. SLA, ou Acordo de Nível de Serviço (service Level Agreement):

É um contrato que define os níveis de qualidade, disponibilidade e suporte que um provedor de serviços em nuvem deve garantir aos seus clientes.

 O **SLA** estabelece métricas e compromissos que a emprssa fornecedora de serviços precisa cumprir garantindo um padrão de **desempenho e confiabilidade.**
 Diante disso, o principal objetivo é garantir que os serviços contratados possuam alta disponilidade esperada para serviços como maquinas virtuais,banco de dados e redes.

 - Calculo da disponibilidade:

  Os provedores de nuvem expressam a disponibilidade em **percentuais de uptime**. Veja alguns exemplos:

| **SLA (%)**      | **Tempo Máximo de Indisponibilidade / Ano** |
|-----------------|------------------------------------------|
| **99,9%**       | 8,76 horas                              |
| **99,95%**      | 4,38 horas                              |
| **99,99%**      | 52,56 minutos                           |
| **99,999%**     | 5,26 minutos                            | 

**Quanto maior o SLA, menor é o tempo permitido de indisponibilidade.**

 **Exemplo:**
 Se um SLA garante 99,9% de disponibilidade, o serviço pode ficar indisponível no máximo 8,76 horas por ano sem penalizações.

 - Garantias e Penalidades no SLA:
   se o provedor de nuvem não cumprir o SLA, ele pode oferecer créditos financeiros ou descontos.

   Se por exemplo o **Azure Storage** garante **99,99%** de disponibilidade, mas entrega apenas **99,8%** em um mês, o cliente pode receber um crédito proporcional ao tempo de indisponibilidade.

   Mas também o **SLA** pode excluir falhas causadas por erro do cliente (exemplo: erro de configuração incorreta de rede). Pois algumas garantias atribuídas ao serviço exigem a configuração correta do serviço. E isso sendo de plena resposabilidade do usuário.
   
### 1.1. SLA  no Microsoft Azure:


O Azure oferece SLAs diferentes para cada serviço. Diante disso, é importante escolher um SLA adequado ao grau de disponibilidade exigido pelo usuário. Isso garante a confiabilidade dos serviços e assegura compensações caso o provedor não cumpra o acordo.

- **Máquinas Virtuais:**

**99,9%** para uma única VM.

**99,95%** para VMs em Availability Zones.

-  **Banco de Dados (Azure SQL):**

**99,99%** de disponibilidade para serviços gerenciados.

- **Armazenamento (Azure Storage):**

**99,99%** para redundância Local (LRS).

**99,999%** para redundância Geográfica (GRS).

-  **Redes:**

**99,99%** para Azure Load Balancer e Azure VPN Gateway.

 **Exemplo:** Uma empresa que hospeda um site no Azure App Service pode escolher um plano com SLA de 99,95%, garantindo que o site fique no ar quase o tempo todo.

### 1.2. Confiabilidade na Nuvem:

A confiabilidade na computação em nuvem refere-se à capacidade dos serviços de funcionarem de forma consistente, segura e previsível, garantindo disponibilidade e desempenho conforme os acordos de nível de serviço (SLA – Service Level Agreement).

 Diante disso a confiabilidade é um fator essencial para garantir que aplicações e sistemas baseados na nuvem operem sem problemas. Ela depende de três pilares principais:

- Alta Disponibilidade (High Availability – HA) → Sistemas projetados para operar continuamente, minimizando tempo de inatividade.
- Resiliência → Capacidade de se recuperar rapidamente de falhas, garantindo a continuidade dos serviços.
- Tolerância a Falhas (Fault Tolerance) → Capacidade de um sistema continuar funcionando mesmo quando ocorrem falhas em componentes individuais.
  
> [!IMPORTANT]
 No serviço oferecido pela **Azure Storage** e **AWS S3** replicam dados automaticamente entre diferentes regiões, garantindo que informações permaneçam acessíveis mesmo em caso de falha em um data center.

### 1.3. A confiabilidade é garantida?

Os provedores de nuvem utilizam diversas estratégias para aumentar a confiabilidade dos serviços. Dentre elas;

-  **Replicação de Dados:**
  
Os dados são copiados para vários servidores e data centers. Logo Evitasse a perda de informações em caso de falha de hardware.

**Exemplo:** O Azure Storage oferece replicação Local, Zonada e Geográfica.

- **Balanceamento de Carga (Load Balancing):**
 
Distribui o tráfego entre diferentes servidores para evitar sobrecarga. Logo Mantendo a estabilidade mesmo em picos de acesso.

**Exemplo:** O Azure Load Balancer distribui requisições entre várias máquinas virtuais.

- **Monitoramento e Auto Healing:**
  
Sistemas monitoram continuamente a performance dos serviços. Se uma falha for detectada, um novo servidor é iniciado automaticamente.

Exemplo: O Azure Kubernetes Service (AKS) reinicia pods automaticamente quando há falhas.

- **Redundância Multi-Regional:**
  
Serviços são distribuídos em múltiplas regiões para evitar indisponibilidade permitindo recuperação rápida em caso de falhas catastróficas.

**Exemplo:** O Azure Traffic Manager direciona usuários para a região mais saudável e próxima.

- **SLAs e Garantias de Disponibilidade:**

Os provedores definem percentuais de uptime garantidos nos contratos de SLA.

**Exemplo de SLA no Azure:**


**99,9%** → Permite até 8,76 horas de indisponibilidade por ano.

**99,99%** → Permite até 52,56 minutos de indisponibilidade por ano.

**99,999%** → Permite até 5,26 minutos de indisponibilidade por ano.

### 1.4. O que é previsibilidade na Nuvem?

A previsibilidade na computação em nuvem refere-se à capacidade de antecipar e **controlar o desempenho**, os **custos** e a **disponibilidade dos serviços**, garantindo uma experiência estável para usuários e empresas.

Para que a previsibilidade seja exercida, é necessário que haja uma garantia de que os recursos computacionais funcionem de maneira consistente, sem variações inesperadas. Além disso, deve ser possível estimar os gastos para evitar surpresas na fatura da nuvem. Todos os serviços contratados devem ser projetados para atender aos SLAs e evitar quedas inesperadas.

Um exemplo: 
Um e-commerce que usa Azure App Service precisa garantir que seu site tenha tempo de resposta previsível, independentemente do número de acessos. Através da escalabilidade automática e do monitoramento, é possível garantir essa estabilidade.


### 2. Escalabilidade:

A escalabilidade da nuvem é uma das principais vantagens da computação em nuvem, permitindo que recursos computacionais sejam ajustados conforme a demanda, de forma automática ou manual. Esse conceito garante eficiência operacional, otimização de custos e melhor desempenho para aplicações e serviços.
 Logo seu principal objetivo é garantir que sistemas e aplicações funcionem de maneira eficiente e otimizada, independente do volume de acessos ou carga de trabalho.

**Escalabilidade Vertical (Scale Up / Down):**

 Consiste em aumentar ou reduzir a capacidade de um único servidor (exemplo: adicionar mais memória RAM, CPU ou armazenamento).

**Exemplo:** Em um banco de dados que começa a ter muitas requisições, pode-se aumentar a capacidade da máquina virtual onde ele está hospedado.

**Escalabilidade Horizontal (Scale Out / In):**

Refere-se à adição ou remoção de servidores para distribuir a carga de trabalho.

**Exemplo:** Um site de e-commerce que recebe muitos acessos durante a Black Friday pode adicionar novos servidores automaticamente para lidar com o aumento do tráfego.

**Escalabilidade Automática (Auto Scaling):**

Usa algoritmos e monitoramento para ajustar recursos automaticamente conforme a demanda, sem necessidade de intervenção humana.

**Exemplo:** O Azure AutoScale pode adicionar servidores automaticamente quando um site recebe mais tráfego e removê-los quando o tráfego diminui.

### 2.1. Escalabilidade Aplicada no Microsoft Azure:

O Microsoft Azure oferece diversas ferramentas para escalabilidade, incluindo:

- Azure Virtual Machine Scale Sets (VMSS): Cria e gerencia múltiplas VMs para escalabilidade horizontal.

- Azure Kubernetes Service (AKS): Gerencia containers e permite escalabilidade automática.

- Azure App Service Auto Scaling: Ajusta dinamicamente o número de instâncias de um aplicativo baseado na demanda.

**Exemplo:**
 Uma aplicação pode ser configurada para criar novas instâncias automaticamente quando a CPU atinge 80% de uso e removê-las quando a carga cai para menos de 40%.

### 3. Elasticidade na Computação em Nuvem:

A elasticidade na computação em nuvem é a capacidade de ajustar automaticamente os recursos computacionais conforme a demanda aumenta ou diminui, garantindo eficiência operacional e controle de custos.

Ela complementa a **escalabilidade**, mas enquanto a escalabilidade foca no crescimento do sistema de forma planejada, a elasticidade permite **ajustes automáticos e dinâmicos de recursos**, garantindo que o sistema utilize apenas o necessário em cada momento.

 Logo, o seu objetivo é evitar o desperdício de recursos e garantir um desempenho "ideal".

 **Exemplo**:
 
Durante a Black Friday, um site de e-commerce pode receber milhões de acessos simultâneos. Com a elasticidade da nuvem, o sistema aumenta automaticamente os servidores para lidar com o tráfego. Após o evento, ele reduz os servidores para evitar custos desnecessários.

- Diferença entre Elasticidade Escalabilidade:

### Diferença Entre Elasticidade e Escalabilidade: 

| **Característica**  | **Elasticidade** | **Escalabilidade** |
|---------------------|-----------------|-------------------|
| **Definição**       | Ajuste **automático** da infraestrutura conforme a demanda. | Capacidade de expandir ou reduzir recursos, mas nem sempre de forma automática. |
| **Tempo de Resposta** | Ocorre **dinamicamente** e em tempo real. | Pode ser **planejada** e implementada conforme necessidade. |
| **Exemplo**         | Um site de streaming aumenta servidores automaticamente quando mais usuários entram. | Uma empresa adiciona servidores antes de um evento esperado. |

**Exemplo Prático:**  

Se um aplicativo hospedado no **Azure App Service** receber um alto volume de acessos, o **Auto Scaling** cria novas instâncias automaticamente para evitar lentidão. Quando o tráfego reduz, ele desativa as instâncias extras para economizar custos.

### 3.1. Elasticidade no Microsoft Azure:

O Microsoft Azure oferece vários serviços que permitem elasticidade automática:

- Azure Virtual Machine Scale Sets (VMSS) → Ajusta automaticamente o número de máquinas virtuais conforme a carga de trabalho.
- Azure App Service Auto Scaling → Garante que aplicações web recebam mais ou menos recursos conforme o tráfego.
- Azure Kubernetes Service (AKS) → Gerencia automaticamente a alocação de contêineres conforme a necessidade.

**Exemplo:** Se um aplicativo hospedado no Azure App Service receber um alto volume de acessos, o Auto Scaling cria novas instâncias automaticamente para evitar lentidão. Quando o tráfego reduz, ele desativa as instâncias extras para economizar custos.

### 4. Segurança na Computação em Nuvem (Introdução):

 A segurança na computação em nuvem pode ser definida como um conjunto de práticas, tecnologias e políticas que garantem a proteção de dados, aplicações e infraestruturas contra acessos não autorizados, ameaças cibernéticas e falhas operacionais. Como a nuvem é amplamente utilizada por empresas de todos os setores, garantir um ambiente seguro é essencial para evitar vazamentos de dados, ataques cibernéticos e prejuízos financeiros.

### 4.1 Princípios Fundamentais da Segurança na Nuvem:


- **Confidencialidade:

Garante que apenas usuários e sistemas autorizados tenham acesso às informações sensíveis. Técnicas como criptografia, autenticação multifator (MFA) e controle de acesso baseado em identidade (IAM) são utilizadas para restringir o acesso.

- **Integridade:**
  
Assegura que os dados não sejam alterados indevidamente, seja por erro humano, ataques maliciosos ou falhas no sistema. Para isso, são aplicadas assinaturas digitais, hashing e mecanismos de verificação de integridade.

- **Disponibilidade:**
  
Mantém os serviços e dados acessíveis sempre que necessário. Isso envolve a implementação de redundância, recuperação de desastres e mitigação de ataques DDoS (Distributed Denial of Service).

**Exemplo:** O Azure Storage pode aplicar criptografia automática nos dados, garantindo que apenas usuários autorizados possam acessá-los.


### 4.2. Principais Ameaças à Segurança na Nuvem:


 Os ambientes em nuvem estão sujeitos a diversas ameaças que podem comprometer a segurança dos dados e serviços. Algumas das principais incluem:

- **Ataques Cibernéticos:**

Os ataques mais comuns incluem:

DDoS (Distributed Denial of Service) → Tentativa de sobrecarregar um serviço para torná-lo indisponível.

Malware e Ransomware → Software malicioso que pode roubar ou bloquear dados até o pagamento de um resgate.

Phishing → Engenharia social para enganar usuários e obter credenciais de acesso.


-  Vazamento e Roubo de Dados
Ocorre quando dados sensíveis são acessados ou divulgados sem autorização. Isso pode acontecer devido a falhas de configuração, senhas fracas ou acessos não monitorados.

- Erros de Configuração e Exposição Acidental
Um erro comum na nuvem é a configuração inadequada de permissões e segurança. Por exemplo, um bucket de armazenamento aberto sem autenticação pode expor informações sigilosas para qualquer pessoa na internet.

- Ameaças Internas
Colaboradores mal-intencionados ou usuários com credenciais comprometidas podem causar danos, seja de forma intencional ou acidental.

- Vulnerabilidades em APIs e Aplicações
Muitas aplicações em nuvem dependem de APIs que, se não forem protegidas corretamente, podem ser exploradas por atacantes para invadir sistemas.

**Exemplo:** O Azure API Management permite configurar autenticação e monitoramento para evitar acessos não autorizados.

### 4.3. Principais Ameaças à Segurança na Nuvem:

Os provedores de nuvem, como a Microsoft Azure, oferecem diversas soluções para mitigar riscos e proteger dados. Algumas das principais práticas e tecnologias incluem:

- Criptografia de Dados:

A criptografia protege os dados contra acessos não autorizados, tanto em repouso (armazenamento) quanto em trânsito (transferência de dados).

> [!IMPORTANT]
 > No Azure:

>Azure Disk Encryption → Criptografa discos de máquinas virtuais.

>Azure Key Vault → Armazena chaves de criptografia com segurança.

>TLS e SSL → Protegem a comunicação entre sistemas e usuários.

-  Controle de Acesso e Autenticação:

O gerenciamento de identidade e controle de acesso evita que usuários não autorizados acessem sistemas críticos.

> [!IMPORTANT]
 > No Azure:

>Azure Active Directory (Azure AD) → Gerencia identidades e autenticação.

>Multi-Factor Authentication (MFA) → Adiciona uma camada extra de segurança no login.

>Role-Based Access Control (RBAC) → Restringe acessos conforme as funções do usuário.

- Segurança de Rede: 
Proteger a comunicação entre servidores e usuários é essencial para evitar ataques cibernéticos.

> [!IMPORTANT]
 > No Azure:

> Azure Firewall → Filtra tráfego malicioso e impede acessos indevidos.

> Azure DDoS Protection → Protege contra ataques de negação de serviço.

> Network Security Groups (NSG) → Define regras para bloquear ou permitir tráfego.

- Monitoramento e Resposta a Incidentes:
  
O monitoramento contínuo ajuda a identificar e responder a ameaças antes que causem danos.

> [!IMPORTANT]
 > No Azure:

>Azure Security Center → Detecta vulnerabilidades e recomenda ações corretivas.

>Microsoft Defender for Cloud → Protege cargas de trabalho contra ameaças avançadas.

>Azure Sentinel → SIEM para análise de logs e resposta automatizada a incidentes.

- Backup e Recuperação de Desastres:
Ter um plano de backup e recuperação de desastres evita a perda definitiva de dados.

> [!IMPORTANT]
 > No Azure:

>Azure Backup → Garante cópias automáticas dos dados.

>Azure Site Recovery → Replica serviços e bancos de dados para recuperação rápida.

### 4.4. Segurança no Modelo de Responsabilidade Compartilhada:

A segurança na nuvem é uma responsabilidade dividida entre o provedor e o cliente. A Microsoft adota o modelo de segurança compartilhada, onde o Azure protege a infraestrutura, enquanto o cliente é responsável por configurar a segurança dos serviços utilizados.


| **Responsablidade**  | **Microsoft Azure** | **Cliente** |
|---------------------|-----------------|-------------------|
| Segurança física dos data centers	      | ✅ | ❌ |
| Proteção contra ataques DDoS	 | ✅ | ❌ |
| Atualizações de hardware e software  | ✅ | ❌|
| Configuração de redes e firewalls	      | ❌| ✅ |
| Gerenciamento de identidades e acessos      | ❌| ✅ |
| Proteção de dados sensíveis      | ❌| ✅ |

### 5. Governança e Gerenciabilidade na Computação em Nuvem:

A computação em nuvem exige um gerenciamento eficiente e um conjunto de políticas bem estruturadas para garantir segurança, conformidade, otimização de custos e controle sobre os recursos.

- governança na computação em nuvem refere-se ao conjunto de políticas, processos e controles estabelecidos para garantir que o uso dos recursos na nuvem esteja alinhado com os objetivos estratégicos da organização, garantindo segurança, conformidade, eficiência operacional e otimização de custos.
  
- gerenciabilidade na computação em nuvem refere-se à capacidade de monitorar, controlar e otimizar recursos, serviços e aplicações na nuvem de maneira eficiente. Isso envolve ferramentas e práticas que garantem visibilidade, automação, governança e resposta rápida a incidentes, permitindo que empresas mantenham alta performance, segurança e custo-benefício.

  Juntas, governança e gerenciabilidade formam a base para uma infraestrutura de TI segura, eficiente e escalável.

A governança na nuvem pode ser dividida em quatro pilares principais:

| **Pilar**  | **Descrição** | **Ferramentas no Azure** |
|---------------------|-----------------|-------------------|
| Segurança e Conformidade      | Proteção de dados e aderência a regulamentações | Azure Security Center, Azure Policy |
| Gestão de Identidade e Acesso | Controle de usuários e permissões | Azure AD, Role-Based Access Control (RBAC) |
| Gestão Financeira e Custos | Monitoramento e otimização de despesas | Azure Cost Management, Azure Budgets|
| Monitoramento e Auditoria | Visibilidade e controle de atividades | Azure Monitor, Azure Log Analytics|

Logo, a  governança na computação em nuvem é essencial para garantir segurança, conformidade, eficiência e controle de custos. O Microsoft Azure oferece um conjunto robusto de ferramentas para ajudar empresas a implementar políticas de segurança, monitoramento e gestão financeira, garantindo um ambiente confiável e bem estruturado.

5.1. Diferença Entre Governança e Gerenciabilidade:

|Aspecto |	Governança	| Gerenciabilidade |
|---------------------|-----------------|-------------------|
Objetivo |	Garantir que o uso da nuvem esteja alinhado com os objetivos do negócio e conformidade. |	Monitorar, otimizar e administrar os recursos na nuvem.|
Foco |	Estratégico|	Operacional|
Atuação	|Define políticas e diretrizes para uso da nuvem.|	Utiliza ferramentas para aplicar e garantir que as políticas sejam seguidas.
Ferramentas no Azure	|Azure Policy, Azure Blueprints, Azure Cost Management.|	Azure Monitor, Azure Automation, Azure Security Center.
Exemplo|	Criar uma política para que apenas máquinas virtuais em regiões específicas possam ser implantadas.|	Monitorar o desempenho dessas máquinas e escalá-las automaticamente, se necessário.|





