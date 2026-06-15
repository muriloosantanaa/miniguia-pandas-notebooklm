# Miniguia de Estudos - Pandas para Análise de Dados com NotebookLM

## Objetivo

Este projeto foi desenvolvido como parte do desafio da DIO utilizando o NotebookLM como ferramenta de aprendizagem ativa.

O tema escolhido foi:

**Python para Análise de Dados com Pandas**

O objetivo foi compreender os principais conceitos da biblioteca Pandas, suas aplicações na manipulação de dados e identificar boas práticas para utilização em projetos de análise de dados.

---

# Curadoria de Fontes

As seguintes fontes foram utilizadas no NotebookLM:

1. Learn Pandas | Kaggle
2. Pandas Tutorial | W3Schools
3. Documentação Oficial do Pandas
4. Guia Oficial Pandas User Guide
5. Documentação Oficial Matplotlib

---

# Engenharia de Prompts

## Prompt 1

### Pergunta

> Quais são os principais recursos da biblioteca Pandas para manipulação de dados?

### Principais Aprendizados

- Leitura de arquivos CSV, JSON, Excel e SQL
- Limpeza de dados
- Filtragem e indexação
- Transformação de dados
- Agrupamentos e agregações
- Análises estatísticas

---

## Prompt 2

### Pergunta

> Quais erros iniciantes costumam cometer ao trabalhar com DataFrames?

### Principais Aprendizados

- Não tratar valores ausentes
- Utilizar indexação incorretamente
- Ignorar tipos de dados
- Problemas com Chained Assignment
- Alterações indevidas em DataFrames

---

# Cicatriz Encontrada

Durante os testes foi possível perceber que prompts muito genéricos produziam respostas superficiais.

## Prompt Inicial

> Explique Pandas.

### Problema

A resposta apresentou conceitos corretos, porém sem foco em estudantes iniciantes.

---

## Prompt Refinado

> Explique Pandas para um estudante iniciante de Análise e Desenvolvimento de Sistemas, utilizando exemplos simples em Python.

### Resultado

A resposta ficou mais contextualizada, prática e fácil de compreender.

Essa experiência demonstrou a importância da Engenharia de Prompts para obtenção de respostas mais úteis e direcionadas.

---

# Miniguia de Estudos

## O que é Pandas?

Pandas é uma biblioteca Python voltada para manipulação, tratamento e análise de dados.

Ela permite trabalhar com grandes volumes de informações utilizando estruturas eficientes.

---

## Estruturas Principais

### Series

Estrutura unidimensional semelhante a uma coluna de dados.

Exemplo:

```python
import pandas as pd

idades = pd.Series([20, 21, 22])
print(idades)
```

### DataFrame

Estrutura bidimensional semelhante a uma planilha Excel.

```python
import pandas as pd

dados = {
    "Nome": ["Ana", "Carlos"],
    "Idade": [20, 25]
}

df = pd.DataFrame(dados)
print(df)
```

---

## Limpeza de Dados

Principais técnicas:

- Remover valores nulos
- Substituir valores ausentes
- Corrigir tipos de dados
- Remover duplicidades

Exemplo:

```python
df.dropna()
```

---

## Visualização de Dados

O Matplotlib pode ser utilizado juntamente com o Pandas para gerar gráficos.

Exemplo:

```python
df["Idade"].plot(kind="bar")
```

---

# Glossário

| Conceito | Descrição |
|-----------|------------|
| Pandas | Biblioteca para análise de dados |
| Series | Estrutura unidimensional |
| DataFrame | Estrutura tabular |
| CSV | Formato de arquivo para dados |
| Data Cleaning | Processo de limpeza dos dados |
| Indexação | Seleção de linhas e colunas |
| Matplotlib | Biblioteca para visualização de dados |

---

# Prompts Reutilizáveis

### Aprendizado

> Explique [tema] para um estudante iniciante utilizando exemplos simples.

### Comparação

> Compare [conceito A] e [conceito B] mostrando vantagens e desvantagens.

### Resumo

> Resuma os principais conceitos de [tema] em tópicos.

### Exercícios

> Crie 5 exercícios práticos sobre [tema] com respostas comentadas.

### Revisão

> Gere um guia rápido de revisão sobre [tema].

---

# Conclusão

O NotebookLM demonstrou ser uma ferramenta eficiente para organização do conhecimento, permitindo explorar conteúdos de forma estruturada através de fontes confiáveis e prompts bem elaborados.

O estudo reforçou conceitos fundamentais da biblioteca Pandas e destacou a importância da engenharia de prompts para potencializar o aprendizado com Inteligência Artificial.
