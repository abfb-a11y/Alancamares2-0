# 🎉 Eventify - Sistema Moderno de Gerenciamento de Eventos

## Demonstração Online

[![Demonstração Online](https://img.shields.io/badge/Demonstração-Online-brightgreen)](https://event-manager-p021.onrender.com/)

### [![Captura da Página Inicial](./screenshots/Home-light-mode.png)](https://event-manager-p021.onrender.com/)

**_Uma solução simplificada de gerenciamento de eventos desenvolvida com JavaScript puro e Node.js._**

## 📋 Índice

- [Visão Geral](#-visão-geral)
- [Motivação do Projeto](#-motivação-do-projeto)
- [Desafios e Aprendizados](#-desafios-e-aprendizados)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto-)
- [Processo de Desenvolvimento](#-processo-de-desenvolvimento)
- [Metas e Conquistas](#-metas-e-conquistas)
- [Como Começar](#como-começar-)
- [Configuração do Banco de Dados](#-configuração-do-banco-de-dados)
- [Documentação da API](#-endpoints-da-api)
- [Exemplos de Uso](#-exemplos-de-uso)
- [Casos de Teste](#-casos-de-teste)
- [Guia de Implantação](#-guia-de-implantação)
- [Capturas da Interface](#-capturas-da-interface)
- [Implementações Futuras](#-implementações-futuras-e-melhorias)
- [Contribuição](#-contribuição)
- [Integrantes do Grupo](#-integrantes-do-grupo)
- [Agradecimentos](#-agradecimentos)
- [Contato](#-entre-em-contato)

## 🌟 Visão Geral

O Eventify transforma o gerenciamento de eventos por meio de uma interface moderna e intuitiva, desenvolvida para facilitar a organização de eventos.

O projeto foi desenvolvido como parte do desafio S-Hook Hackathon e demonstra conhecimentos de desenvolvimento full-stack utilizando HTML, CSS, JavaScript puro, Node.js, Express e MySQL.

## 🌟 Motivação do Projeto

O Eventify foi desenvolvido com o objetivo de simplificar o gerenciamento de eventos para organizadores e participantes, buscando solucionar problemas relacionados à acessibilidade, organização e comunicação durante o S-Hook Hackathon.

## 🧠 Desafios e Aprendizados

- **Desafios:** Implementação de design responsivo, otimização das consultas ao banco de dados e gerenciamento do estado utilizando JavaScript puro.
- **Aprendizados:** Aperfeiçoamento dos conhecimentos sobre indexação no MySQL, desenvolvimento de APIs RESTful e melhoria da experiência do usuário utilizando CSS puro.

## ✨ Funcionalidades

### Funcionalidades Principais

- **Gerenciamento de Eventos**
  - Criar e editar eventos com informações detalhadas
  - Fazer upload de imagens dos eventos
  - Definir limite de participantes
  - Adicionar localização e horário dos eventos

- **Organização Inteligente**
  - Sistema de eventos favoritos
  - Funcionalidade de arquivamento
  - Visualização em calendário
  - Alternância entre visualização em grade e lista

- **Interface e Experiência do Usuário**
  - Modo escuro/claro
  - Design responsivo
  - Pesquisa em tempo real
  - Animações personalizadas
  - Ordenação por data

## 🛠 Tecnologias Utilizadas

### Frontend

- HTML5
- CSS3 (animações utilizando CSS puro)
- JavaScript puro
- Ícones FontAwesome

### Backend

- Node.js
- Express.js
- MySQL
- API RESTful

## Estrutura do Projeto 📁

```text
event-manager/
├── public/
│   ├── index.html
│   ├── add-event.html
│   └── view-event.html
    └── help.html
    └── favorites.html
    └── calendar.html
    └── archive.html
    └── styles.css
    └── main.js
├── server.js
├── event_manager.sql
├── package.json
└── README.md
