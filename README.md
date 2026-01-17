# projeto-etl-vendas-dio

# Relatório do Projeto – DIO

## 1. Visão Geral

Este projeto consiste no desenvolvimento de um **Pipeline de Engenharia de Dados para análise de vendas**, simulando um cenário real de mercado onde dados brutos são coletados, tratados, armazenados e preparados para consumo analítico.

O foco principal é demonstrar domínio de conceitos fundamentais de **engenharia e análise de dados**, organização de código, boas práticas e visão de negócio, tornando o projeto relevante tanto para avaliação acadêmica quanto para portfólio profissional.

---

## 2. Objetivo do Projeto

Construir um pipeline simples, porém robusto, capaz de transformar dados brutos de vendas em informações estruturadas prontas para análise.

* Objetivo principal: Implementar um fluxo ETL (Extract, Transform, Load) funcional.
* Objetivos secundários:

  * Garantir qualidade e consistência dos dados
  * Facilitar análises futuras
  * Simular um cenário real de dados corporativos
* Público-alvo: Analistas e engenheiros de dados iniciantes
* Benefícios esperados: Dados confiáveis para tomada de decisão

---

## 3. Escopo e Requisitos

### 3.1 Requisitos Funcionais

* RF01 – Leitura de dados brutos em formato CSV
* RF02 – Tratamento de dados inconsistentes ou nulos
* RF03 – Geração de dataset final consolidado

### 3.2 Requisitos Não Funcionais

* RNF01 – Código legível e modular
* RNF02 – Facilidade de manutenção
* RNF03 – Execução local sem dependências complexas

### 3.3 Fora de Escopo

* Integrações em tempo real
* Deploy em cloud

---

## 4. Tecnologias e Ferramentas Utilizadas

* Linguagem: Python
* Bibliotecas: Pandas
* Banco de dados: Arquivo CSV (simulação)
* Versionamento: Git e GitHub
* Documentação: Markdown

Justificativa técnica das escolhas:
Python e Pandas foram escolhidos por serem amplamente utilizados no mercado para manipulação e análise de dados, além de possuírem excelente suporte da comunidade.

---

## 5. Arquitetura e Estrutura do Projeto

O projeto segue uma arquitetura simples e organizada, focada em clareza e escalabilidade futura.

```
projeto-etl-vendas/
├── data/
│   ├── raw/
│   └── processed/
├── src/
│   ├── extract.py
│   ├── transform.py
│   └── load.py
├── README.md
└── modelo-relatorio.md
```

* Padrões adotados: Separação por responsabilidades
* Boas práticas aplicadas: Código modular e reutilizável

---

## 6. Implementação

### 6.1 Principais Funcionalidades

* Extração de dados brutos de vendas
* Limpeza e padronização dos dados
* Geração de base final pronta para análise

### 6.2 Pontos Técnicos Relevantes

* Uso de funções reutilizáveis
* Tratamento de valores nulos
* Padronização de tipos de dados

---

## 7. Evidências do Projeto

* Repositório GitHub: [https://github.com/seu-usuario/projeto-etl-vendas](https://github.com/seu-usuario/projeto-etl-vendas)
* Base de dados: Arquivo CSV fictício
* Prints de execução local

---

## 8. Resultados Obtidos

* Pipeline funcional executando corretamente
* Dataset final estruturado e confiável
* Projeto pronto para expansão futura

---

## 9. Desafios Encontrados

* Tratamento de dados inconsistentes
* Organização do pipeline ETL

As soluções envolveram validações e modularização do código.

---

## 10. Aprendizados

* Conceitos práticos de ETL
* Organização de projetos de dados
* Boas práticas de versionamento

---

## 11. Melhorias Futuras

* Integração com banco de dados SQL
* Automação do pipeline
* Criação de dashboard analítico

---

## 12. Conclusão

O projeto atingiu seus objetivos ao demonstrar, de forma prática, conceitos fundamentais de engenharia de dados, sendo uma base sólida para evolução técnica e profissional.

---

## 13. Referências

* Documentação oficial do Pandas
* Materiais da plataforma DIO

---

**Autor:** Bruno Bandeira
**Plataforma:** DIO
**Data:** ****/****/______
