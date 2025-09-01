# Desafio: Copiloto de Atendimento - DIO Viagens

Este repositório documenta a criação e as funcionalidades de um copiloto de atendimento desenvolvido no **Microsoft Copilot Studio**. O projeto demonstra a aplicação prática de conceitos de inteligência artificial conversacional para criar um assistente virtual capaz de interagir de forma inteligente e automatizar tarefas.

---

## Objetivo do Projeto

O objetivo principal deste projeto foi construir um assistente virtual com base em um cenário de negócios (uma agência de viagens fictícia, **DIO Viagens**). O foco foi em:

* **Compreender a estrutura de um copiloto:** Organizar fluxos de diálogo e tópicos de forma eficiente.
* **Automatizar interações:** Criar respostas automáticas para perguntas frequentes e roteiros de atendimento.
* **Explorar funcionalidades avançadas:** Personalizar respostas e simular integrações com serviços externos para enriquecer a experiência do usuário.

---

## Funcionalidades e Aprendizados

Durante o desenvolvimento deste projeto, explorei as seguintes funcionalidades do Microsoft Copilot Studio, validando-as em um cenário prático.

### 1. Fluxos de Conversa e Tópicos

Criei e configurei tópicos específicos para lidar com as principais interações de um cliente de agência de viagens.

* **Exemplo de Tópico:** Um tópico de `Consulta de Vistos`, acionado por frases como "preciso de visto para [país]" ou "documentos para viagem".
* **Cadeia de Diálogo:** A partir da intenção inicial, o Copiloto guia o usuário por um fluxo de perguntas e respostas para coletar informações necessárias, como destino e nacionalidade, até fornecer uma resposta completa ou encaminhar para um agente humano.

### 2. Integração com Serviços Externos

Compreendi como a integração com serviços externos é crucial para a utilidade do Copiloto. A plataforma permite conectar a dados e APIs para fornecer informações em tempo real.

* **Exemplo de Funcionalidade:** Para um tópico de `Informações de Destino`, o Copiloto poderia, hipoteticamente, conectar-se a uma API de clima para informar a previsão do tempo no destino, ou a uma API de câmbio para mostrar a cotação da moeda local.

### 3. Personalização e Enriquecimento das Respostas

Utilizei variáveis e elementos visuais para tornar as conversas mais naturais e úteis.

* **Variáveis:** O Copiloto pode coletar dados do usuário, como o nome, e usá-los nas respostas para criar uma experiência mais personalizada. Por exemplo: "Olá, **[Nome do Cliente]**, posso te ajudar com a cotação de um voo?"
* **Respostas Enriquecidas:** Em vez de apenas texto, as respostas podem incluir cartões adaptáveis com imagens e botões, melhorando a interação do usuário e facilitando ações como "Agendar uma Consulta" ou "Ver Pacotes Promocionais".

---

## Conclusão

Este projeto demonstra minha capacidade de usar o **Microsoft Copilot Studio** para desenvolver soluções de IA conversacional que atendem a necessidades de negócios. O processo de criação e os conceitos aplicados aqui são diretamente transferíveis para a construção de assistentes virtuais em escala, provando o potencial da plataforma para automatizar e otimizar o atendimento ao cliente.