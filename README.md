# Projeto Chatbot IA — 

---

## Nome do Projeto

```text
Pragmata AI
```

---

## Contexto do Projeto

O projeto consiste em um chatbot simples com integração de inteligência artificial e estruturação de prompts técnicos, especialista no jogo Pragmata.

O sistema recebe mensagens do usuário, processa a entrada e retorna respostas automatizadas.

---

## Objetivos Técnicos

O projeto foi desenvolvido para:

1. praticar lógica de programação;
2. aprender integração com APIs;
3. entender arquitetura backend;


---

# Visão Geral da Solução

## Como o sistema funciona

O chatbot funciona em 4 etapas:

```text
Usuário → API → Processamento → Resposta
```

---

## Fluxo completo

### 1. Usuário envia mensagem

Exemplo:

```text
"O que é Pragmata?"
```

---

### 2. Backend recebe requisição

O servidor captura a mensagem usando uma API.

---

### 3. Processamento do prompt

O sistema:

1. organiza contexto;
2. interpreta entrada;
3. prepara requisição;
4. envia para o mecanismo de resposta.

---

### 4. Retorno da resposta

O chatbot devolve:

```text
"É um jogo desenvolvido..."
```

---

# Arquitetura da Solução

# Estrutura da arquitetura

```text
Frontend
   ↓
API REST
   ↓
Processamento de Prompt
   ↓
Motor de Resposta
   ↓
Banco de Dados 
```

---

# Explicação dos componentes

## Frontend

Interface utilizada pelo usuário.

Pode ser:

* terminal;

---

## API KEY

API = sistema de comunicação entre aplicações.

A API recebe mensagens e retorna respostas.

-Vá em console.groq, logue, vá no campo de criação de chaves API, gere uma chave API e coloque a chave no campo selecionado no código para usar o chatbot.

---

## Processamento de Prompt

Etapa responsável por:

1. interpretar entrada;
2. organizar contexto;
3. limpar dados;
4. preparar requisição.

---

## Motor de Resposta

Responsável pela lógica principal.

Pode utilizar:

* IA;
* regras;
* banco de conhecimento.

---

## Banco de Dados

Utilizado para:

* histórico;
* usuários;
* logs;

# README.md Profissional do Projeto


````md
# Chatbot AI Assistant 🤖

## Descrição

Chatbot desenvolvido para estudos de integração com IA, APIs REST e estruturação de prompts técnicos.

---

## Objetivos

- Aprender arquitetura backend
- Trabalhar com APIs
- Estruturar prompts
- Aplicar versionamento profissional

---

## Tecnologias

- Python
- Git/GitHub
- API

---

## Estrutura do Projeto

```text
src/
api/
services/
prompts/
```

---

# Como executar


### Entrar na pasta

```bash
cd chatbot-ai-assistant
```

### Instalar dependências

```bash
pip install -r requirements.txt
```

### Executar projeto

```bash
python app.py
```

---

## Funcionalidades

- Recebimento de mensagens
- Processamento de prompts
- Respostas automatizadas
---

## Melhorias futuras


- Interface web
- Autenticação
- Histórico de conversas
