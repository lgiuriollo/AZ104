📘 Resumo Completo para a Certificação AZ-104 – Administrador do Azure
Este documento reúne, de forma clara e detalhada, os principais conteúdos cobrados na certificação Microsoft Azure Administrator Associate (AZ-104). A linguagem é objetiva, didática e ideal para revisões e aplicação prática no dia a dia profissional.

☁️ 1. Gerenciamento de Identidade no Azure
🔐 Azure Active Directory (Azure AD)
Serviço de gerenciamento de identidades baseado na nuvem.

Administra usuários, grupos, dispositivos e autenticação.

Funções comuns: Global Admin, User Admin, Azure AD Admin.

Recursos:

RBAC (Role-Based Access Control): atribuição de permissões com base em papéis.

IAM (Identity and Access Management): controle de acesso centralizado.

Condições de acesso: aplicam políticas baseadas em localização, dispositivo, risco etc.

🔄 Integração com Active Directory local
Uso do Azure AD Connect para sincronização.

Suporte a autenticação híbrida.

🛡️ 2. Governança, Compliance e Controle de Custos
🗂️ Hierarquia de gerenciamento
Grupos de gerenciamento → Assinaturas → Grupos de recursos → Recursos.

📜 Azure Policy
Regras de conformidade e restrições (ex: localização, tipos de recursos).

💸 Monitoramento de Custos
Tags: categorização para análise de gastos.

Budget e alertas no Azure Cost Management.

📦 3. Recursos de Computação
🖥️ Máquinas Virtuais (VMs)
Criação, inicialização e automação.

Tipos de disco: SO, dados, gerenciados e não gerenciados.

Snapshots, backups e imagens personalizadas.

⚖️ Escalabilidade e Alta Disponibilidade
Vertical (aumenta CPU/RAM).

Horizontal (escalonamento com VMSS).

Availability Sets e Zones: garantem tolerância a falhas e atualizações.

🌐 4. Rede Virtual e Segurança
🧭 Redes Virtuais (VNets)
Segmentação e comunicação entre recursos.

Sub-redes e endereçamento IP.

🔐 Network Security Groups (NSGs)
Controle do tráfego com regras de entrada e saída.

🔌 Conectividade Híbrida
VPN Gateway: conexão criptografada via internet.

ExpressRoute: conexão privada de alta performance.

🌐 Outros componentes
Azure DNS: gerenciamento de zonas DNS.

Peering de VNets: comunicação entre redes virtuais.

Service Endpoints: acesso seguro a serviços PaaS.

💾 5. Armazenamento
📂 Tipos de conta
General-purpose v2, BlobStorage.

Camadas: Hot, Cool e Archive.

🔧 Serviços
Blob: objetos não estruturados.

File: compartilhamento SMB.

Queue: mensagens assíncronas.

Table: dados NoSQL.

🔒 Segurança
Chaves, SAS (Shared Access Signatures), criptografia, RBAC.

📊 6. Monitoramento, Log Analytics e Backup
📈 Azure Monitor
Coleta de métricas e logs.

Workbooks, alertas e visualizações.

🔍 Log Analytics
Consulta de dados com KQL (Kusto Query Language).

Integração com Azure Monitor.

Permite análises com dados de auditoria, desempenho e segurança.

Tabelas comuns:

Syslog: mensagens de log do Linux.

Heartbeat: status de conectividade de agentes.

Acesso via: Monitor > Logs no portal Azure.

Workspace: armazena e organiza dados de log.

Vantagens:
Pronto para uso em auditoria e análise de segurança.

Diversas consultas predefinidas.

Alta integração com serviços do Azure.

📂 Backup e Recuperação
Azure Backup: proteção de dados de VMs, arquivos e bancos.

Azure Site Recovery (ASR): failover e continuidade de negócios.

🔍 Network Watcher
Para capturar tráfego em uma VM, é necessário:

Extensão do Agente Observador de Rede.

Permite análise de conexão, captura de pacotes e logs de fluxo.

⚙️ 7. Automatização e Gerenciamento via Código
🧱 ARM Templates
Implantação declarativa com arquivos JSON.

💻 CLI, PowerShell e Cloud Shell
Azure CLI e Azure PowerShell: automação e scripting.

Cloud Shell: terminal integrado no portal Azure.
