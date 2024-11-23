# Breve resumo da aula "Criando um Assistente de Delivery com AWS Step Functions e Bedrock" na DIO

## Step Functions
As Step Functions são, basicamente, uma ferramenta de integração de serviços. É um facilitador visual para gerenciamento de componentes de aplicações distribuídas. 

A proposta é ser uma ferramenta de low code para visualização de orquestração de serviços e de comunicação entre eles.

Máquina de estado (state machine) é o nome dado para um projeto AWS Step Functions, aplicativo que irá controlar o fluxo de várias etapas do trabalho. 
Eles são definidos como máquinas de estado, compostos por passos semelhante a um diagrama e que podem ser usados para orquestração dos múltiplos serviços.

Para criar e gerenciar as etapas de fluxos de trabalho, é utilizado o Workflow Studio que nada mais é que a interface visual da AWS Step Functions. 

Benefícios:
- Integração rápida
- Automação simples
- Processar dados sob demanda
- Visualização da arquitetura orientada por eventos

## ASL
Os Workflows do Step Functions são escritos em ASL (Amazon State Language).
ASL é a linguagem de controle de estado e foi baseada em JSON.

## Bedrock
Bedrock é o serviço da AWS para facilitar o uso e integração de IA, que permite tarefas como traduções, geração e análise de texto e diversas outras aplicações. Seus principais modelos, chamados de família Claude 3, são: Haiku, Sonnet e Opus.
