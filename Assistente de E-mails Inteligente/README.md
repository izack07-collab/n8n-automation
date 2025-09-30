# Assistente de E-mails Inteligente 📧🤖

Fluxo de automação desenvolvido com **n8n** e **IA** para **classificar, priorizar e gerar alertas sobre e-mails recebidos**.  
Ele ajuda profissionais e equipes a manterem o foco no que é mais importante, economizando tempo e reduzindo erros.

---

## 📋 Funcionalidades

- **Leitura automática de e-mails:** usa o conector do Gmail no n8n
- **Classificação por categorias:**  
  - Alta Prioridade (urgente ou prazo curto)  
  - Suporte ao Cliente  
  - Financeiro/Faturamento  
  - Promoções/Marketing  
  - Pessoal
- **Geração de alertas no Telegram:** envia resumo com urgência e sugestão de ação
- **Resumo inteligente do e-mail:** baseado em LLM para leitura rápida
- **Recomendação de ação:** ex. responder, encaminhar, ignorar etc.

---

## ⚙️ Tecnologias Utilizadas

- [n8n](https://n8n.io/) – ferramenta de automação low-code
- Conector **Gmail Trigger**
- Integração com **Telegram Bot** para envio de alertas
- Modelos de **IA/LLM (Groq)** para análise e resumo
- Prompts customizados para triagem e priorização

---

## 🚀 Como Usar

1. **Importar o fluxo**  
   - Baixe o arquivo `assistente-emails.json`  
   - No n8n, clique em **Import Workflow** e selecione o arquivo

2. **Configurar credenciais**  
   - Configure o Gmail OAuth2  
   - Configure o token do bot do Telegram

3. **Ativar o fluxo**  
   - Teste enviando e-mails de diferentes categorias  
   - Confira as notificações automáticas no Telegram

---

## 📈 Resultados Obtidos

- Redução drástica do tempo de triagem de e-mails
- Maior foco em mensagens urgentes
- Diminuição de riscos por e-mails críticos passarem despercebidos

---

## 📂 Estrutura do Repositório

assistente-emails/
│
├── README.md ← explicação do projeto
└── assistente-emails.json ← fluxo exportado do n8n

yaml
Copiar código

---

## 👤 Autor

Criado por **Isaac Silveira**  
Especialista em Automação com n8n & IA | Integrações Inteligentes | Soluções Low-Code para Empresas