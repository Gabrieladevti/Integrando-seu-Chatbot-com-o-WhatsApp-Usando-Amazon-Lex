# Integrando seu Chatbot com o WhatsApp Usando Amazon Lex

## 🛠 Serviços Utilizados
- Amazon Lex
- WhatsApp
- Twilio

## 📌 Etapas

### 1️⃣ Criando uma Conta no Twilio
1. Acesse [Twilio](https://www.twilio.com/).
2. Valide seu e-mail e número de celular.

### 2️⃣ Criando um Chatbot de Exemplo no Amazon Lex
1. Acesse o **Console AWS** → **Lex** → **Bots** → **Criar bot**.
2. Escolha **Começar com um exemplo** e selecione **Reservar viagem**.
3. Defina um nome para o bot.
4. Crie uma função com permissões básicas do Amazon Lex.
5. Para a **Lei de Proteção à Privacidade Online de Crianças (COPPA)**, selecione **Não**.
6. Clique em **Avançar**.
7. Selecione o idioma **en-US** e clique em **Concluído**.
8. Construa o bot e faça testes.

### 3️⃣ Integrando o Amazon Lex com o WhatsApp via Twilio
1. No **Console Twilio**, acesse **Minha conta** e copie o **SID** e **Token**.
2. No **Amazon Lex Console**, vá até **Versões de bot** → **Implantação** → **Integrações de canal**.
3. Clique em **Adicionar canal** → **Plataforma - Twilio SMS**.
4. Insira o **Account SID** e **Authentication Token** do Twilio.
5. Clique em **Criar** e copie a **URL do endpoint gerado**.
6. No **Console Twilio**, acesse **Mensagens** → **Configurações** → **Configurações do sandbox do WhatsApp**.
7. Cole a **URL do endpoint copiada** no campo **QUANDO UMA MENSAGEM CHEGA**.

### 4️⃣ Testando a Integração
- Envie mensagens pelo WhatsApp e verifique as respostas do chatbot.

---
🚀 **Agora seu chatbot está integrado ao WhatsApp!**
