# GoodWe ChargeOps Assistant

## Integrantes

- Kaique Da Silva Assis — RM-572718
- Andre Debiazzi - RM 569062
- Lucas Barros - RM 571528
- Renan Eskildssen RM 571097
- Vinicius Cristal de Oliveira RM 572048

---

# Problema Abordado

O EV Challenge 2026 propõe soluções voltadas para a gestão inteligente de eletropostos e carregamento de veículos elétricos.

Um dos principais problemas identificados é a ausência de mecanismos integrados para:

- gerenciamento de potência;
- controle de carregamento;
- faturamento individual;
- comunicação entre usuários;
- uso compartilhado em condomínios.

Essas limitações dificultam a administração eficiente dos eletropostos, especialmente em ambientes residenciais com múltiplos usuários.

---

# Proposta do Chatbot

O projeto propõe um chatbot inteligente especializado em auxiliar síndicos, moradores e operadores de condomínios que utilizam eletropostos compartilhados.

O chatbot será responsável por:

- responder dúvidas sobre carregamento;
- informar disponibilidade dos carregadores;
- explicar falhas e interrupções;
- orientar sobre consumo energético;
- auxiliar no faturamento individual;
- oferecer suporte operacional básico.

O sistema será contextualizado especificamente para o cenário GoodWe ChargeOps.

---

# Persona Escolhida

## Síndicos e moradores de condomínios

A escolha foi realizada porque condomínios representam um dos ambientes mais desafiadores para gestão de carregamento compartilhado de veículos elétricos.

O chatbot atuará como ferramenta operacional para facilitar a comunicação e o gerenciamento do sistema.

---

# Tecnologias Selecionadas

- Python
- Gemini API
- LangChain
- Streamlit
- GitHub

---

# Justificativa Técnica

## Python
Linguagem principal do projeto devido à simplicidade e integração com ferramentas de IA.

## Gemini API
Modelo de IA com boa capacidade de interpretação contextual e geração de respostas naturais.

## LangChain
Utilizado para gerenciamento do fluxo conversacional e integração de prompts.

## Streamlit
Permite criar uma interface simples e rápida para demonstração do chatbot.

## GitHub
Responsável pelo versionamento e documentação do projeto.

---

# Fluxo de Funcionamento

1. Usuário envia pergunta.
2. A interface recebe a mensagem.
3. O system prompt contextualiza o modelo.
4. O modelo processa a solicitação.
5. O chatbot retorna resposta contextualizada.

---

# Fluxograma

O fluxograma do funcionamento do chatbot está disponível no arquivo:

docs/fluxograma.png

docs/fluxograma.png