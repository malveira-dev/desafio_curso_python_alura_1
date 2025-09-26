# Desafio: Automação de Perguntas e Respostas com IA

## Visão Geral do Projeto

Este projeto, desenvolvido como parte do curso "Python para IA" da Alura, demonstra um fluxo completo de automação para gerar, processar e responder a um conjunto de perguntas utilizando uma Inteligência Artificial generativa. O objetivo é ilustrar a integração entre a manipulação de arquivos em Python e o poder de um Grande Modelo de Linguagem (LLM) para processar informações em lote.

## Etapas do Processo

O fluxo de trabalho foi dividido nas seguintes etapas:

1.  **Criação do Dataset de Perguntas:**
    * Uma lista de perguntas predefinidas em Python foi utilizada como fonte de dados.
    * Um script Python foi criado para iterar sobre essa lista e persistir cada pergunta em um arquivo `.txt`, formatando o `dataset` inicial.

2.  **Leitura e Preparação dos Dados:**
    * O arquivo `.txt` contendo as perguntas foi lido pelo script.
    * As perguntas foram carregadas em uma nova lista em Python, preparando-as para serem processadas pelo modelo de IA.

3.  **Integração com IA Generativa (Google Gemini):**
    * Utilizando a API do Google Gemini, foi implementada uma função para enviar cada pergunta da lista ao modelo.
    * O sistema aguarda a resposta gerada pelo LLM para cada uma das perguntas.

4.  **Armazenamento dos Resultados:**
    * As respostas fornecidas pela IA foram coletadas e organizadas.
    * Um novo arquivo `.txt` foi gerado para armazenar de forma estruturada cada pergunta seguida de sua respectiva resposta.

5.  **Verificação Final:**
    * Como etapa de validação, o arquivo final com as respostas foi lido para garantir que todo o processo foi executado com sucesso.

## Tecnologias Utilizadas

* **Linguagem:** Python
* **IA Generativa:** API do Google Gemini
* **Bibliotecas Principais:**
    * `google.generativeai` para interação com o LLM.
    * Manipulação de arquivos nativa do Python (`open`).

## Conclusão

Este projeto demonstra uma solução prática e escalável para automatizar a obtenção de respostas, sendo aplicável em cenários como a criação de FAQs, análise de dados textuais ou qualquer tarefa que exija o processamento em lote de informações por uma IA.
