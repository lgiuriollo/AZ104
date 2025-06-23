
# 📘 Resumo Completo para a Certificação AZ-104 – Administrador do Azure

Este documento reúne, de forma clara e detalhada, os principais conteúdos cobrados na certificação **Microsoft Azure Administrator Associate (AZ-104)**. A linguagem é acessível, direta ao ponto e pensada para revisões e aplicação prática no dia a dia.

---

## ☁️ 1. Gerenciamento de Identidade no Azure

### 🔐 Azure Active Directory (Azure AD)
- Serviço de identidade baseado em nuvem do Azure.
- Permite gerenciamento de usuários, grupos, dispositivos e autenticação.
- **Funções comuns**: Azure AD Admin, Global Admin, User Admin.
- **Conceitos chave**:
  - **RBAC (Role-Based Access Control)**: controle de permissões com base em funções atribuídas.
  - **IAM (Identity and Access Management)**: gestão de acesso aos recursos.
  - **Condições de acesso**: políticas de segurança baseadas em contexto (localização, dispositivo etc).

### 🔄 Sincronização com AD local
- Usando o **Azure AD Connect** para sincronizar identidades locais com o Azure AD.
- Autenticação híbrida.

---

## 🏗️ 2. Governança e Conformidade

### 📋 Grupos de Gerenciamento, Assinaturas e Grupos de Recursos
- Organização hierárquica dos recursos.
- Grupos de gerenciamento → Assinaturas → Grupos de recursos → Recursos.

### 📜 Azure Policies
- Aplicação de regras e padrões de compliance (ex: restringir tipos de VMs, localizações etc).

### 💰 Controle de Custos
- **Tags**: categorização de recursos para rastrear custos.
- **Orçamentos e alertas**: monitoramento financeiro com o Cost Management.

---

## 📦 3. Implementação e Gerenciamento de Recursos de Computação

### 🖥️ Máquinas Virtuais (VMs)
- Criação, configuração, inicialização, automação.
- **Discos**: OS Disk, Data Disk, Unmanaged vs Managed.
- **Snapshots e imagens personalizadas**.

### 📊 Escalonamento
- **Vertical**: mais recursos (CPU/RAM) para uma VM.
- **Horizontal**: mais instâncias (VMs).
- **VMSS (Virtual Machine Scale Sets)**: escalam automaticamente com base na demanda.

### ⚙️ Alta Disponibilidade
- **Availability Sets**: protegem contra falhas de hardware e atualizações simultâneas.
- **Availability Zones**: isolamento físico entre zonas da mesma região.

---

## 🌐 4. Implementação e Gerenciamento de Redes Virtuais

### 🔌 Redes Virtuais (VNets) e Sub-redes
- Comunicação entre recursos do Azure.
- Divisão lógica da rede.

### 🧱 NSG (Network Security Groups)
- Controle de tráfego de entrada/saída baseado em regras.

### 🔄 VPN Gateway e ExpressRoute
- VPN Gateway: conecta on-premise ao Azure via internet segura.
- ExpressRoute: conexão dedicada com alta velocidade e baixa latência.

### 🧭 Azure DNS, Peering e Endpoints de Serviço
- Resolução de nomes, conexão entre VNets, acesso seguro a serviços do Azure.

---

## 💾 5. Gerenciamento de Armazenamento

### 📁 Tipos de Conta de Armazenamento
- General-purpose v2, BlobStorage.
- Hot, Cool e Archive Tiers (acesso frequente, esporádico e raro).

### 🧩 Serviços
- Blob: objetos não estruturados.
- File: compartilhamentos de arquivos.
- Queue: mensagens entre componentes.
- Table: dados NoSQL.

### 🔐 Segurança e Acesso
- Chaves, SAS (Shared Access Signature), RBAC para Storage.
- Criptografia em repouso e em trânsito.

---

## 🛡️ 6. Monitoramento e Backup

### 📈 Azure Monitor e Log Analytics
- Métricas em tempo real e coleta de logs.
- Workbooks, alertas e dashboards.

### 💾 Backup e Site Recovery
- Azure Backup: proteção de dados de VMs, arquivos, SQL, etc.
- ASR (Azure Site Recovery): recuperação de desastres.

---

## 🧩 7. Gerenciamento de Recursos com ARM, CLI e PowerShell

### 📜 Modelos ARM
- Implantação declarativa com arquivos JSON.

### 💻 Ferramentas
- Azure CLI e Azure PowerShell: automatização e gestão por linha de comando.
- Cloud Shell: terminal integrado ao portal Azure.

---

> ✅ Este resumo foi elaborado como parte do meu preparo para a certificação AZ-104 e reflete minha forma de entender e revisar os conteúdos. Ideal para reforçar os principais pontos antes da prova ou aplicar na prática.
