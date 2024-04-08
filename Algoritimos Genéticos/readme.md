# Algoritmo Genético para Resolver o Problema do Caixeiro Viajante

Este é um exemplo de implementação de um algoritmo genético em Python para resolver o clássico problema do caixeiro viajante. O objetivo é encontrar a rota mais curta que passa por todas as cidades exatamente uma vez e retorna à cidade de origem.

## Dependências

- Python 3.x
- Biblioteca DEAP
- NumPy
- Matplotlib

## Instalação das Dependências

```bash
pip install deap numpy matplotlib

Descrição do Código
Utiliza a biblioteca DEAP para simplificar a implementação do algoritmo genético.
Define a estrutura básica do algoritmo genético, incluindo a definição de tipos de indivíduos, operadores genéticos e funções de avaliação.
O problema consiste em encontrar a rota mais curta entre um conjunto de cidades, representadas por um grafo completo com as distâncias entre cada par de cidades.
Utiliza uma representação de permutação para os indivíduos, onde cada indivíduo é uma permutação das cidades.
A aptidão de um indivíduo é calculada como o comprimento total da rota, ou seja, a soma das distâncias entre cada par de cidades na permutação.
O algoritmo utiliza o método de seleção de torneio, crossover PMX (Partially Mapped Crossover) e mutação de troca de índices para operações genéticas.
Aplica estatísticas de acompanhamento do progresso do algoritmo, incluindo média, mínimo e máximo da aptidão da população em cada geração.
Após a execução do algoritmo, plota um gráfico mostrando a evolução da aptidão ao longo das gerações.

Uso
Basta executar o código Python fornecido para iniciar o algoritmo genético e resolver o problema do caixeiro viajante.
```
