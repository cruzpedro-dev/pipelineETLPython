#  Pipeline ETL com Python - Santander Dev Week 2023

Este projeto demonstra a implementação de um fluxo de dados completo seguindo o padrão **ETL (Extract, Transform, Load)**.

O objetivo principal é processar uma base de clientes e gerar mensagens de marketing personalizadas focadas em investimentos. Devido à descontinuação de APIs externas utilizadas na versão original do curso, este projeto foi refatorado para operar de forma resiliente através de processamento de dados locais e lógica de fallback em Python.

##  Arquitetura do Processo

* **Extract (Extração):** Leitura de dados estruturados a partir de um arquivo físico `.csv` utilizando a biblioteca **Pandas**.
* **Transform (Transformação):** Implementação de um motor de regras em Python para simular a geração de insights personalizados por IA, atribuindo mensagens dinâmicas para cada perfil de cliente.
* **Load (Carregamento):** Exportação dos dados enriquecidos para um arquivo `.json`, simulando a alimentação de um sistema de CRM ou banco de dados NoSQL.

##  Tecnologias e Ferramentas
* **Linguagem:** Python 3.12
* **Bibliotecas:** Pandas, JSON, Random
* **Ambiente:** Google Colab

##  Como executar
1. Clone o repositório.
2. Certifique-se de que o arquivo `arquivo.CSV` está no mesmo diretório do script.
3. Execute as células do notebook para visualizar a extração e a geração do arquivo final.
