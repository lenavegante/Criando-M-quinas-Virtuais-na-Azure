# Criando Máquinas Virtuais na Azure

Este repositório documenta minha experiência prática e os principais aprendizados adquiridos no curso **“Criando Máquinas Virtuais na Azure”**, abordando desde conceitos fundamentais até a criação completa de VMs usando o Azure Portal e ferramentas de linha de comando.

---

## 📘 Objetivo do Repositório

- Registrar minha experiência prática no Azure  
- Compartilhar anotações e boas práticas  
- Facilitar estudos futuros e consultas rápidas  
- Mostrar habilidade em documentar ambientes de nuvem  

---

## 🧱 Conteúdo do Curso

### 1️⃣ Introdução ao Azure
- Estrutura global da plataforma  
- Regiões, Zonas de disponibilidade e Resource Groups  
- Modelos de serviço (IaaS / PaaS / SaaS)

---

### 2️⃣ Fundamentos de Máquinas Virtuais (VMs)
- Tipos e famílias de VMs  
- CPU, memória, discos e classificações (General, Compute, Memory Optimized)  
- Imagens do SO (Marketplace, customizadas)

---

### 3️⃣ Criação de uma Máquina Virtual – Azure Portal
Passo a passo realizado:

1. Criar Resource Group  
2. Definir nome da VM, região e imagem do SO  
3. Selecionar tamanho da VM  
4. Configurar autenticação (Senha / SSH Key)  
5. Escolher tipo de disco (Standard/Premium)  
6. Configurar rede (VNet, Subnet, IP público)  
7. Ajustar regras NSG (ex: RDP, SSH)  
8. Revisar e criar a VM  

📸 Capturas relacionadas:  
Veja a pasta **/images**.

---

### 4️⃣ Configurações de Rede
- Criação de Redes Virtuais  
- Subnets  
- Grupos de Segurança (NSG)  
- Controle de portas (RDP – 3389, SSH – 22)

---

### 5️⃣ Acesso à Máquina Virtual
**Windows:** Acesso via RDP  
**Linux:** Acesso via SSH  
