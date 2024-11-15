
# Resumo do Laboratório Microsoft Azure

## Módulo 1 - Conceitos Iniciais de Cloud com Azure

### Benefícios da Computação em Nuvem
- Mudança de idioma e tema (cor) no portal do Azure.
- Visualização de recursos do Azure por categoria.
- **Rede:**
  - **Bastions:** Rede segura que funciona como Jump Server.
  - **Firewall.**

### Criação de Máquinas Virtuais no Azure
- **SLA:** Disponibilidade conforme redundância:
  - Maior SLA: menor indisponibilidade e maior custo.

### Tipos de Serviço na Azure
- **IaaS (Infraestrutura como Serviço):** Mais flexível, mais responsabilidades do contratante.
- **PaaS (Plataforma como Serviço):** Focado em desenvolvimento de apps, menos responsabilidades.
- **SaaS (Software como Serviço):** Pouca flexibilidade e responsabilidades.

### Modelo de Responsabilidade Compartilhada
- Usuário é responsável por **dados, dispositivos e configurações**.
- Provedor gerencia **infraestrutura, hardware e serviços básicos**.

---

## Módulo 2 - Arquitetura e Serviços Azure

### Infraestrutura Global
- **Regiões:** Conjunto de datacenters próximos.
- **Zonas de Disponibilidade:** Redundância entre datacenters.
- **Pares de Regiões:** Separados por no mínimo 480 km.

### Gerenciamento de Recursos
- **Grupos de Recursos:** Organização lógica, sem restrição de tipo ou região.
- **Assinaturas:** Separação recomendada (desenvolvimento, teste, produção).

### Armazenamento no Azure
- **Redundância:** 
  - LRS: Redundância local (3 cópias).
  - GRS: Redundância geográfica (cópias fora da região).
- **Tipos de Dados:** 
  - Blob (dados não estruturados), 
  - Arquivos, 
  - Tabelas, 
  - Filas.
- **Camadas de Acesso:** Frequente, Esporádico, Frio, Arquivo Morto.

---

## Módulo 3 - Gerenciamento e Governança

### Gerenciamento de Custos
- **Fatores que afetam custos:**
  - Tipo de recurso, consumo, área geográfica e tráfego de rede.
- **Ferramentas:**
  - Calculadora de preços.
  - Gerenciamento de Custos e Marcas (Tags).

### Governança e Conformidade
- **Políticas e Bloqueios de Recurso:**
  - Azure Policy para impor conformidade de recursos.
  - Bloqueios protegem recursos contra exclusão acidental.

### Microsoft Purview
- Governança de dados e conformidade: 
  - Classificação, ciclo de vida e insights de dados.

---

## Módulo 4 - Ferramentas de Gerenciamento e Monitoramento

### Implantação no Azure
- **Azure Cloud Shell:** CLI para gerenciamento de recursos.
- **Azure Resource Manager (ARM):** Modelos JSON para infraestrutura como código.

### Monitoramento
- **Azure Monitor:** Telemetria para maximizar desempenho e disponibilidade.
- **Advisor:** Recomendações de segurança, custo e confiabilidade.

---

**Laboratórios Práticos**: Aplicação de conceitos como criação de máquinas virtuais, configuração de armazenamento, simulações de custo e uso de ferramentas de monitoramento.
