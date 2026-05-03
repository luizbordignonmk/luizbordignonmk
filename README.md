##Olá, eu sou o Luiz Bordignon.

Co-founder da BLENCO — Infraestrutura de Agentes de IA para operações comerciais.
# BLENCO

Infraestrutura de Agentes de IA para operações comerciais.

---

## 🧠 O que é a BlenCo?

A BlenCo constrói uma infraestrutura padronizada, escalável e replicável de Agentes de IA.

Não criamos chatbots.

Criamos sistemas que operam atendimento e vendas com consistência.

---

## 🏗️ Arquitetura

Canal (WhatsApp / Instagram / Web)
        ↓
ALIGN (CRM / Interface operacional)
        ↓
Webhook (n8n)
        ↓
Memória + Dados (Supabase)
        ↓
IA (OpenAI)
        ↓
Decisão
        ↓
Ações (CRM / APIs)
        ↓
Resposta

---

## 🧩 O papel do ALIGN

O ALIGN é o CRM da BlenCo.

Ele NÃO possui inteligência própria.

Sua função é:

- Centralizar conversas (Inbox)
- Permitir operação humana
- Configurar integrações
- Servir como interface da operação

Toda a inteligência vive fora dele.

---

## ⚙️ Stack

- Supabase (Database + Auth + Storage)
- n8n (orquestração)
- OpenAI (IA)
- React (frontend - ALIGN)
- Meta APIs (WhatsApp + Instagram)

---

## 🧬 Princípios

- IA fora do CRM
- Arquitetura única para todos clientes
- Multi-tenant (company_id)
- Escalabilidade sem refatoração
- Governança obrigatória

---

## 📈 Status

Em produção com evolução contínua.
