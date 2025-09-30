# Atendente Virtual para Festas 🪩🤖

Assistente virtual desenvolvido com **n8n** e **IA** para automatizar o atendimento a clientes de festas e eventos.  
O objetivo é oferecer **respostas rápidas, vendas simplificadas e informações centralizadas via WhatsApp**.

---

## 📋 Funcionalidades

- **Vendas de ingressos via Pix:** o cliente recebe os dados de pagamento e instruções automaticamente.
- **Atendimento automatizado via WhatsApp:** responde dúvidas comuns sobre local, horário, atrações e regras do evento.
- **Suporte inteligente:** integra banco de dados e documentos do evento para consultas rápidas.
- **Agente de IA:** entende perguntas abertas dos usuários e responde de forma natural.
- **Gestão centralizada:** permite aos organizadores atualizar informações sem depender de suporte técnico.

---

## ⚙️ Tecnologias Utilizadas

- [n8n](https://n8n.io/) – ferramenta de automação low-code
- Modelos de **IA/LLM** para compreensão e respostas automáticas
- **Banco de dados** para armazenar informações do evento
- Integração com **WhatsApp Business API** para conversas em tempo real
- Fluxos customizados para gerenciamento de pagamentos via Pix

---

## 🚀 Como Usar

1. **Importar o fluxo**  
   - Baixe o arquivo `atendente-festa.json` deste repositório  
   - No painel do n8n, clique em **Import Workflow** e selecione o arquivo

2. **Configurar credenciais**  
   - Configure a integração com WhatsApp Business (ou outro canal de mensagens)  
   - Insira os dados do Pix e do banco de dados do evento

3. **Ativar o fluxo**  
   - Teste com perguntas reais (por exemplo: *“Quanto custa o ingresso?”*, *“Qual é o horário do evento?”*)  
   - O agente responderá automaticamente com base nas informações cadastradas

---

## 📈 Resultados Obtidos

- Redução do tempo médio de resposta de **horas para segundos**  
- Melhoria na experiência dos participantes do evento  
- Maior taxa de conversão nas vendas de ingressos pelo atendimento rápido e confiável

---

## 📂 Estrutura do Repositório

atendente-festa/
│
├── README.md ← explicação do projeto
└── atendente-festa.json ← fluxo exportado do n8n

yaml
Copiar código

---

## 👤 Autor

Criado por **Isaac Silveira**  
Especialista em Automação com n8n & IA | Integrações Inteligentes | Soluções Low-Code para Empresas