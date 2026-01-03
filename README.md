# Chatbot de Medicamentos — Automação com n8n e IA

Automação desenvolvida com n8n que utiliza um agente de IA integrado ao Google Gemini para fornecer informações objetivas sobre medicamentos, com base em dados oficiais, sem oferecer orientação médica.

## 💡 Problema
A busca por informações técnicas sobre medicamentos durante estudos ou atividades profissionais costuma ser lenta e pouco prática, exigindo consultas manuais em múltiplas fontes e gerando sobrecarga de informação.

## 🛠 Solução
Desenvolvimento de um chatbot automatizado que permite consultar rapidamente informações sobre medicamentos, retornando apenas os dados solicitados pelo usuário e oferecendo um relatório completo somente sob demanda.

O fluxo foi projetado para evitar excesso de informações e garantir respostas claras, objetivas e responsáveis.

## ⚙️ Como funciona
- Recebe o nome do medicamento via chatbot
- Processa a solicitação em um fluxo automatizado no n8n
- Realiza requisição HTTP à API oficial do FDA  
  (`https://api.fda.gov/drug/label.json`)
- Utiliza um agente de IA (Google Gemini) para organizar e resumir as informações
- Retorna respostas objetivas sobre:
  - Para que serve
  - Indicações
  - Contraindicações
  - Cuidados
- Oferece o relatório completo apenas quando solicitado pelo usuário

## 🧠 Boas práticas adotadas
- Não fornece diagnósticos ou orientações médicas
- Limita as respostas a informações técnicas e descritivas
- Reduz sobrecarga de informação para o usuário final

## 👩‍💻 Minha contribuição
- Modelagem completa do fluxo de automação no n8n
- Integração com API pública do FDA via HTTP Request
- Integração de agente de IA (Google Gemini) no fluxo
- Definição das regras de resposta e controle de escopo das informações
- Estruturação da lógica para entrega sob demanda do relatório completo

## 📂 Arquivos
- `/workflow`: export do fluxo n8n em JSON
- `/images`: imagem do fluxo de automação

## 🛠 Tecnologias
- n8n
- Google Gemini (IA)
- API pública do FDA
- Automação de processos

## 📷 Imagem do fluxo

<img width="803" height="402" alt="image" src="https://github.com/user-attachments/assets/c2197d33-85ce-4d16-a047-61e405a8849d" />
