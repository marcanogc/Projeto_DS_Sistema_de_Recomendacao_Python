# Projeto de Data Science: Sistema de Recomendação e Aplicação Python

## Descrição
Este projeto apresenta uma abordagem completa para resolver um problema empresarial no campo de **Data Science**. O objetivo é criar um **sistema de recomendação** utilizando técnicas de similaridade entre usuários e desenvolver uma aplicação funcional utilizando **Python**. O projeto é projetado para ser replicável e oferece código e dados para download.

### Objetivo
Criar um sistema de recomendação utilizando **métricas de similaridade** para recomendar co-proprietários de propriedades com base nas características dos usuários. A solução inclui o desenvolvimento de uma aplicação interativa que visualiza as recomendações e permite a interação com os dados.

## Tecnologias e Ferramentas
- **Linguagem de programação**: Python
- **Bibliotecas utilizadas**:
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - Flask (para o desenvolvimento da aplicação)
  - GPT-4 (para automatizar parte da documentação)
- **Ambiente de desenvolvimento**:
  - Jupyter Notebook / Visual Studio Code
  - Python 3.x

## Estrutura do Projeto
O projeto está dividido em vários scripts que gerenciam o fluxo de dados e as funcionalidades do sistema de recomendação.

### Scripts principais:
1. **data_preprocessing.py**: Código para a **carga** e **transformação de dados**.
2. **similarity_calculation.py**: Implementação da **distância euclidiana** e da **matriz de similaridade** entre usuários.
3. **app.py**: Aplicação em **Flask** que interage com os usuários e exibe as recomendações.

## Passos do Projeto

### 1. **Entender o Contexto Empresarial**
- O projeto é baseado em uma startup que busca encontrar co-proprietários compatíveis para propriedades imobiliárias. Um sistema de recomendação é utilizado para sugerir compradores adequados com base nos interesses e características dos usuários.

### 2. **Explicar o Problema**
- O desafio é identificar pessoas com perfis similares e gerar recomendações precisas de co-proprietários.

### 3. **Solução Analítica**
- Utilizamos a **similaridade entre usuários** para medir a compatibilidade utilizando técnicas como a **distância euclidiana**.
  
### 4. **Desenvolvimento da Aplicação**
- A aplicação é desenvolvida utilizando **Flask** para criar uma interface web onde os usuários podem interagir com o sistema, inserir dados e receber recomendações personalizadas.

## Implementação do Sistema de Recomendação
### 1. **Métricas de Similaridade**
- A similaridade entre usuários é calculada através de **vetores** e a **distância euclidiana** é utilizada para medir a proximidade entre eles. Usuários mais semelhantes receberão recomendações de propriedades em comum.

### 2. **Matriz de Similaridade**
- Uma **matriz de similaridade** é gerada a partir dos dados dos usuários, o que permite visualizar e comparar a compatibilidade entre diferentes pessoas.

## Instalação

Para executar este projeto localmente, siga os seguintes passos:

### 1. Clone o repositório
```bash
git clone https://github.com/marcanogc/Projeto_DS_Sistema_de_Recomendacao_Python.git
cd Projeto_DS_Sistema_de_Recomendacao_Python
