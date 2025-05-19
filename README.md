
# Resumo: Trabalhando com Ambientes Cloud na Azure


# Resumo introdução da computacao em nuvem

Esse é um resumo da aula sobre computação em cloud com Azure da DIO.

Nesse primeiro capítulo fui introduzido ao Microsoft Azure e seus conceitos, inicialmente sobre os Modelos de nuvem e as diferenças entre CapEx e OpEx.

# Comparação entre modelos de nuvem

| Modelo | Característica |
| ----- | ----- |
| Pública | Recursos compartilhados entre vários usuários; gerenciada por um provedor externo. |
| Privada | Infraestrutura dedicada a uma única organização; mais controle e segurança. |
| Híbrida | Combina nuvem pública e privada, permitindo flexibilidade e uso estratégico. |

# Comparação entre CapEx e OpEx

| Termo | Significado | Exemplo | Vantagens |
| ----- | ----- | ----- | ----- |
| CapEx (Capital Expenditure) | Despesa de capital com infraestrutura física, paga antecipadamente. | Compra de servidores | Controle total, patrimônio próprio |
| OpEx (Operational Expenditure) | Despesa operacional contínua, paga conforme o uso. | Pagamento mensal por serviços em nuvem | Flexibilidade, escalabilidade, menor investimento inicial |



## 🌐 Benefícios da Nuvem Azure

A Microsoft Azure é uma das principais plataformas de computação em nuvem do mercado, oferecendo uma ampla gama de serviços e soluções para empresas de todos os portes. Seus principais benefícios incluem:

- **Alta disponibilidade global** com data centers distribuídos em várias regiões.
- **Ampla gama de serviços**, como máquinas virtuais, bancos de dados, inteligência artificial, DevOps e muito mais.
- **Modelo de pagamento sob demanda**, reduzindo custos operacionais.
- **Integração com ferramentas Microsoft**, como Windows Server, Active Directory, Power Platform e Microsoft 365.

## ⚖️ Benefícios da Nuvem: Escalabilidade e Elasticidade

- **Escalabilidade**: Permite aumentar ou reduzir recursos computacionais com facilidade, de acordo com a demanda do negócio. Por exemplo, é possível aumentar a capacidade de uma aplicação durante períodos de pico sem interrupções.
- **Elasticidade**: Garante que os recursos sejam alocados e desalocados automaticamente, conforme necessário. Isso evita desperdício de recursos e otimiza o custo-benefício.

## 🔐 Benefícios da Nuvem: Confiabilidade, Previsibilidade e Segurança

- **Confiabilidade**: Alta disponibilidade dos serviços, com redundância de dados e recuperação de desastres. A Azure oferece SLAs (Acordos de Nível de Serviço) que asseguram continuidade e desempenho.
- **Previsibilidade**: Com modelos de custo bem definidos e métricas de desempenho, é possível planejar o crescimento da infraestrutura com segurança.
- **Segurança**: A Azure oferece proteção de dados com criptografia, controles de acesso, detecção de ameaças e conformidade com padrões internacionais como ISO, GDPR e LGPD.

## 🛠️ Benefícios da Nuvem: Governança e Gerenciabilidade

- **Governança**: Ferramentas como Azure Policy, Blueprints e Cost Management ajudam a definir, aplicar e monitorar políticas de uso e conformidade em todo o ambiente.
- **Gerenciabilidade**: O Azure fornece dashboards, alertas e automação para facilitar a administração dos recursos, permitindo uma gestão proativa e centralizada de toda a infraestrutura em nuvem.

---

# Tipos de Serviço de Nuvem na Azure

## ☁️ IaaS, PaaS e SaaS na Azure

A Azure disponibiliza diferentes modelos de serviços em nuvem, cada um com níveis distintos de controle, flexibilidade e gerenciamento:

### 🔧 IaaS (Infrastructure as a Service)

- **O que é**: Fornece infraestrutura básica como máquinas virtuais, redes e armazenamento.
- **Responsabilidade do cliente**: Gerenciar sistema operacional, middleware, aplicativos e dados.
- **Exemplos na Azure**: Azure Virtual Machines, Azure Load Balancer, Azure Virtual Network.

### 🛠️ PaaS (Platform as a Service)

- **O que é**: Fornece uma plataforma gerenciada para desenvolver, executar e escalar aplicações.
- **Responsabilidade do cliente**: Foco no desenvolvimento e gerenciamento de aplicações e dados.
- **Exemplos na Azure**: Azure App Service, Azure SQL Database, Azure Functions.

### 💼 SaaS (Software as a Service)

- **O que é**: Aplicações completas entregues como serviço, acessadas pela internet.
- **Responsabilidade do cliente**: Apenas o uso do software e gerenciamento de dados do usuário.
- **Exemplos na Azure**: Microsoft 365, Dynamics 365, Power BI.

## 🔄 Modelo de Responsabilidade Compartilhada

Na computação em nuvem, a segurança e o gerenciamento dos recursos são compartilhados entre a Microsoft (provedora da Azure) e o cliente. A divisão das responsabilidades varia de acordo com o modelo de serviço adotado:

| Elemento                         | IaaS         | PaaS         | SaaS         |
|----------------------------------|--------------|--------------|--------------|
| Segurança física do datacenter   | Azure        | Azure        | Azure        |
| Infraestrutura (rede, servidores)| Azure        | Azure        | Azure        |
| Sistema operacional               | Cliente      | Azure        | Azure        |
| Aplicações                       | Cliente      | Cliente      | Azure        |
| Dados                            | Cliente      | Cliente
