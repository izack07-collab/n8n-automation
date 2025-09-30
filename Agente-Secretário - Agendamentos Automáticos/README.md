# Agente-Secretário para Agendamentos 📆🤖

Agente inteligente construído com **n8n** e **IA**, atuando como um **secretário virtual**.  
Ele verifica disponibilidade de agenda, auxilia na marcação e cancelamento de compromissos e envia lembretes automáticos.

---

## 📋 Funcionalidades

- **Integração com Google Calendar:** verifica e cria eventos automaticamente
- **Agente de IA:** interpreta comandos em linguagem natural como  
  - “Marque reunião com a equipe amanhã às 10h”  
  - “Cancele o compromisso de sexta”
- **Resolução de conflitos:** avisa sobre sobreposições e sugere novos horários
- **Notificações automáticas:** envia confirmação de agendamento via chat
- **Escalável:** pode ser combinado com outros fluxos de automação

---

## ⚙️ Tecnologias Utilizadas

- [n8n](https://n8n.io/) – ferramenta de automação low-code
- Conector **Google Calendar**
- Integração com canais de chat (Telegram ou WhatsApp)
- Modelos de **IA/LLM** para compreensão de linguagem natural
- Lógica de fluxo para detecção de disponibilidade e conflitos

---

## 🚀 Como Usar

1. **Importar o fluxo**  
   - Baixe o arquivo `agente-secretario.json`  
   - No painel do n8n, clique em **Import Workflow**

2. **Configurar credenciais**  
   - Configure acesso ao Google Calendar  
   - Configure o canal de mensagens desejado

3. **Ativar o fluxo**  
   - Teste com frases em linguagem natural  
   - Verifique a criação de eventos no Google Calendar

---

## 📈 Resultados Obtidos

- Redução de tarefas manuais de agendamento
- Diminuição de erros humanos (conflitos e sobreposições)
- Economia de tempo na comunicação entre equipes e clientes

---

## 📂 Estrutura do Repositório

agente-secretario/
│
├── README.md ← explicação do projeto
└── agente-secretario.json ← fluxo exportado do n8n

yaml
Copiar código

---

## 👤 Autor

Criado por **Isaac Silveira**  
Especialista em Automação com n8n & IA | Integrações Inteligentes | Soluções Low-Code para Empresas