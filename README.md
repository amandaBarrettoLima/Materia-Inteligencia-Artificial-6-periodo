# Matéria de Inteligência Artificial — 6º Período

**Amanda Barreto Lima · Turma A**

Repositório criado para armazenar os exercícios e trabalhos realizados na disciplina de **Inteligência Artificial** (6º período, Turma A). Todos os trabalhos estão em formato **Jupyter Notebook** (`.ipynb`) e cobrem quatro frentes de estudo:

- **Base em Python e Ciência de Dados:** 130 exercícios (Python puro, NumPy, SciPy, Pandas e Matplotlib).
- **Aprendizado supervisionado:** regressão, SVM, Árvores de Decisão, Random Forest e Boosting.
- **Aprendizado não supervisionado:** agrupamento com K-Means.
- **AutoML:** comparação entre FLAML e Auto-Sklearn.

---

## Sumário

- [Conteúdo do repositório](#conteúdo-do-repositório)
- [Explicação de cada arquivo](#explicação-de-cada-arquivo)
- [Lista dos 130 exercícios](#lista-dos-130-exercícios)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Como executar](#como-executar)
- [Autora](#autora)

---

## Conteúdo do repositório

| Arquivo | Assunto | Resumo |
|---|---|---|
| [`Exercícios_Python_[AmandaBarreto][Turma_A][Período_6].ipynb`](Exerc%C3%ADcios_Python_%5BAmandaBarreto%5D%5BTurma_A%5D%5BPer%C3%ADodo_6%5D.ipynb) | Fundamentos de Python | 50 exercícios de lógica de programação, strings, listas, busca, ordenação, recursão e pequenos jogos |
| [`Exercicios_dataScience[Amanda_Barreto][6_Periodo][Turma_A].ipynb`](Exercicios_dataScience%5BAmanda_Barreto%5D%5B6_Periodo%5D%5BTurma_A%5D.ipynb) | Ciência de Dados | 80 exercícios de NumPy, SciPy, Pandas e Matplotlib |
| [`Regressao_ScikitLearn_Diabetes_[AmandaBarreto_6A].ipynb`](Regressao_ScikitLearn_Diabetes_%5BAmandaBarreto_6A%5D.ipynb) | Regressão | Aula guiada de regressão com Scikit-learn usando o dataset Diabetes |
| [`notebook-svm.ipynb`](notebook-svm.ipynb) | Classificação (SVM) | SVM aplicado ao dataset Iris, com ajuste de hiperparâmetros |
| [`classifica-o-do-breast-cancer-wisconsin.ipynb`](classifica-o-do-breast-cancer-wisconsin.ipynb) | Classificação (SVM) | Diagnóstico de câncer de mama (Breast Cancer Wisconsin) com SVM Linear e RBF |
| [`modelo com svm e arvores [Amanda Barreto 6A].ipynb`](modelo%20com%20svm%20e%20arvores%20%5BAmanda%20Barreto%206A%5D.ipynb) | SVM x Árvores | Comparação entre SVM e modelos de árvore em 6 datasets diferentes |
| [`KMeans_Iris_[Amanda_Barreto_6A]a.ipynb`](KMeans_Iris_%5BAmanda_Barreto_6A%5Da.ipynb) | Agrupamento (K-Means) | K-Means não supervisionado no dataset Iris, com métricas de qualidade dos clusters |
| [`AutoML_(FLAML_vs_Auto_Sklearn)_com_o_Dataset_Iris_[Amanda_Barreto_6A].ipynb`](AutoML_%28FLAML_vs_Auto_Sklearn%29_com_o_Dataset_Iris_%5BAmanda_Barreto_6A%5D.ipynb) | AutoML | Comparação entre FLAML e Auto-Sklearn no dataset Iris |
| `README.md` | Documentação | Este arquivo |

---

## Explicação de cada arquivo

### 1. Exercícios de Python (Parte 1)

Arquivo: [`Exercícios_Python_[AmandaBarreto][Turma_A][Período_6].ipynb`](Exerc%C3%ADcios_Python_%5BAmandaBarreto%5D%5BTurma_A%5D%5BPer%C3%ADodo_6%5D.ipynb)

- 50 exercícios (1–50) para praticar os fundamentos de programação necessários ao estudo de IA.
- Vão do clássico "Hello, World!" até pequenos projetos, como jogo da forca, jogo da velha e validação de CPF.
- Temas: estruturas de dados, strings, busca binária, Bubble Sort e Insertion Sort, recursão, Cifra de César e estatística básica.
- Cada exercício segue o formato **Enunciado → Código → Explicação**.

### 2. Exercícios de Ciência de Dados (Parte 2)

Arquivo: [`Exercicios_dataScience[Amanda_Barreto][6_Periodo][Turma_A].ipynb`](Exercicios_dataScience%5BAmanda_Barreto%5D%5B6_Periodo%5D%5BTurma_A%5D.ipynb)

- 80 exercícios (51–130), sendo 20 para cada biblioteca:
  - **NumPy (51–70):** arrays, matrizes, estatística e normalização.
  - **SciPy (71–90):** integrais, equações diferenciais, otimização, interpolação, álgebra linear e transformadas de Fourier.
  - **Pandas (91–110):** DataFrames, filtros, agrupamentos, tabelas dinâmicas, junção de tabelas e leitura/escrita de CSV e Excel.
  - **Matplotlib (111–130):** gráficos de linha, dispersão, histograma, barras, pizza, subplots e gráficos 3D.
- Mesmo formato da Parte 1: **Enunciado → Código → Explicação**.

### 3. Regressão com Scikit-learn (Diabetes)

Arquivo: [`Regressao_ScikitLearn_Diabetes_[AmandaBarreto_6A].ipynb`](Regressao_ScikitLearn_Diabetes_%5BAmandaBarreto_6A%5D.ipynb)

- Aula guiada, teórica e prática, usando o dataset Diabetes do scikit-learn (442 observações e 10 atributos).
- Organizada em módulos: fundamentos, conhecendo o dataset, análise exploratória, regressão linear simples e múltipla, métricas (MAE, MSE, RMSE e R²) com análise de resíduos, validação cruzada e overfitting, regularização (Ridge e Lasso) e regressão polinomial.
- Termina com um exercício final de questões dissertativas e um mini-relatório.

### 4. SVM com o dataset Iris

Arquivo: [`notebook-svm.ipynb`](notebook-svm.ipynb)

- Reavalia o dataset Iris carregando o CSV do Kaggle, em vez da função `load_iris()` do scikit-learn.
- Etapas: análise exploratória, pré-processamento (codificação do alvo, divisão 80/20 estratificada e padronização), SVM baseline com kernel RBF e otimização de `C`, `gamma` e kernel com `GridSearchCV`.
- Avaliação com acurácia, precisão, recall, F1-score e matriz de confusão (97% de acurácia no teste, 29 de 30 amostras corretas).

### 5. Breast Cancer Wisconsin com SVM

Arquivo: [`classifica-o-do-breast-cancer-wisconsin.ipynb`](classifica-o-do-breast-cancer-wisconsin.ipynb)

- Classifica tumores de mama como **malignos (M)** ou **benignos (B)** a partir de 30 atributos numéricos extraídos de imagens.
- Etapas: limpeza (remoção das colunas `id` e `Unnamed: 32`), codificação do alvo, análise exploratória, divisão 80/20 estratificada e padronização.
- Compara o SVM com kernel **Linear** e **RBF** usando `GridSearchCV`, avaliando acurácia, precisão, recall, F1-score e AUC-ROC.
- Interpreta a importância dos atributos pelos coeficientes do kernel linear. O RBF teve resultado melhor nas métricas avaliadas.

### 6. SVM e Árvores em vários datasets

Arquivo: [`modelo com svm e arvores [Amanda Barreto 6A].ipynb`](modelo%20com%20svm%20e%20arvores%20%5BAmanda%20Barreto%206A%5D.ipynb)

O maior notebook do repositório. Em cada dataset são treinados **SVM** (4 kernels, `C` e `gamma` com `GridSearchCV`) e **Árvore de Decisão, Random Forest e Gradient Boosting**, sempre seguidos de uma comparação entre as duas famílias de modelos. Ao final há uma **conclusão geral**.

| Dataset | Tarefa | Alvo | Modelos comparados |
|---|---|---|---|
| Breast Cancer Wisconsin | Classificação | `diagnosis` | SVM x Árvores |
| Literary Digest 1936 | Regressão | `erro_1936` | Regressão Linear Simples x Árvores |
| UCI Heart Disease Data | Classificação | `num` | SVM x Árvores |
| Heart Disease Dataset | Classificação | `target` | SVM x Árvores |
| Student Stress Factors (Prova B) | Classificação | `stress_level` | SVM x Árvores |
| Fishmorph | Classificação | ordem taxonômica (`order`) | SVM x Árvores |

### 7. K-Means com o dataset Iris

Arquivo: [`KMeans_Iris_[Amanda_Barreto_6A]a.ipynb`](KMeans_Iris_%5BAmanda_Barreto_6A%5Da.ipynb)

- Atividade de aprendizado **não supervisionado**: agrupar as flores do Iris com K-Means **sem usar as espécies no treinamento**; elas só entram no final, para comparação.
- **Parte A:** perguntas conceituais (por que não usar o alvo e o efeito de não padronizar os dados).
- **Parte B:** K-Means com K = 3 nos dados padronizados e cálculo do coeficiente de Silhouette.
- **Parte C:** comparação de K = 2 a K = 6, escolha justificada de K, comparação com as espécies reais (ARI e matriz de contingência), efeito da padronização e conclusão crítica com limitações.

### 8. AutoML: FLAML x Auto-Sklearn

Arquivo: [`AutoML_(FLAML_vs_Auto_Sklearn)_com_o_Dataset_Iris_[Amanda_Barreto_6A].ipynb`](AutoML_%28FLAML_vs_Auto_Sklearn%29_com_o_Dataset_Iris_%5BAmanda_Barreto_6A%5D.ipynb)

- Compara duas ferramentas de **AutoML** no dataset Iris, avaliando desempenho, tempo de execução e custo computacional.
- Configuração justa: mesma divisão de dados (80/20 estratificada, `random_state=42`), mesma semente e mesmo orçamento de tempo de 60 s para os dois frameworks.
- O Auto-Sklearn roda em um ambiente separado com Python 3.9, criado dentro do notebook, pois não instala no Python 3.11/3.12 do Colab.
- Avalia acurácia, `classification_report`, matriz de confusão, tempo, número de configurações testadas e pico de memória.

Resultados de uma execução no Google Colab:

| Framework | Acurácia (teste) | Erros | Tempo (s) | Configurações avaliadas | Modelo escolhido |
|---|---|---|---|---|---|
| FLAML | 100% | 0 | 60,05 | 6 | `lrl1` (regressão logística com L1) |
| Auto-Sklearn | 96,67% | 1 | 54,67 | 21 | Ensemble de 12 modelos |

A diferença é de uma única amostra em um teste com 30 e varia entre execuções, então não permite afirmar que um framework seja melhor que o outro. O FLAML entrega um único modelo, mais simples de explicar; o Auto-Sklearn explora mais configurações no mesmo tempo, mas gera um ensemble mais difícil de interpretar.

---

## Lista dos 130 exercícios

<details>
<summary><b>Parte 1 — Fundamentos de Python (1–50)</b></summary>

### Fundamentos de Python

| # | Exercício |
|----|--------------------------------------------------------|
| 1  | Imprimir "Hello, World!" no console                    |
| 2  | Somar dois números digitados pelo usuário              |
| 3  | Calcular a área de um círculo                          |
| 4  | Converter Celsius para Fahrenheit                      |
| 5  | Imprimir a tabuada de um número                        |
| 6  | Exibir os números pares de 1 a 20                      |
| 7  | Verificar se um número é par ou ímpar                  |
| 8  | Verificar se uma palavra é palíndromo                  |
| 9  | Calcular o fatorial de um número                       |
| 10 | Gerar os 10 primeiros termos da sequência de Fibonacci |

### Listas, Strings e Estruturas de Dados

| # | Exercício |
|----|----------------------------------------------------|
| 11 | Encontrar o maior e o menor número de uma lista    |
| 12 | Contar ocorrências de cada caractere em uma string |
| 13 | Ordenar uma lista de números                       |
| 14 | Somar todos os elementos de uma lista              |
| 15 | Calcular a média de uma lista de números           |
| 16 | Inverter uma string                                |
| 17 | Contar a frequência de cada palavra em uma frase   |
| 18 | Verificar se um número é primo                     |
| 19 | Jogo de adivinhar o número                         |
| 20 | Transpor uma matriz                                |

### Algoritmos e Criptografia

| # | Exercício |
|----|-----------------------------------------------------|
| 21 | Implementar busca binária                           |
| 22 | Criptografar uma mensagem com a Cifra de César      |
| 23 | Descriptografar uma mensagem com a Cifra de César   |
| 24 | Validar CPF brasileiro                              |
| 25 | Classificar números em positivos, negativos e zeros |
| 26 | Criar uma calculadora                               |
| 27 | Verificar se duas palavras são anagramas            |
| 28 | Criar um gráfico de barras com Matplotlib           |
| 29 | Implementar o FizzBuzz                              |
| 30 | Criar um jogo da forca                              |

### Algoritmos de Ordenação e Jogos

| # | Exercício |
|----|--------------------------------------------|
| 31 | Implementar o Bubble Sort                  |
| 32 | Criar um jogo da velha para dois jogadores |
| 33 | Verificar anagramas — variação             |
| 34 | Contar vogais em uma string                |
| 35 | Gerar Fibonacci até um número n            |
| 36 | Criar um gerador de senhas aleatórias      |
| 37 | Calcular fatorial utilizando recursão      |
| 38 | Contar palavras em um texto                |
| 39 | Simular o lançamento de dois dados         |
| 40 | Criar uma lista de compras                 |

### Estruturas de Dados e Estatística

| # | Exercício |
|----|---------------------------------------------------|
| 41 | Remover duplicatas de uma lista                   |
| 42 | Gerar números primos até n                        |
| 43 | Converter metros para centímetros                 |
| 44 | Gerar Fibonacci até um número de termos           |
| 45 | Classificar números em pares e ímpares            |
| 46 | Calcular média e desvio padrão                    |
| 47 | Contar a frequência de números em uma lista       |
| 48 | Implementar o Insertion Sort                      |
| 49 | Calcular a soma dos dígitos de um número          |
| 50 | Calcular a frequência de cada letra em uma string |

</details>

<details>
<summary><b>Parte 2 — NumPy, SciPy, Pandas e Matplotlib (51–130)</b></summary>

### NumPy (51–70)

| # | Exercício |
|----|---------------------------------------------------------------------------------------------------|
| 51 | Criar um array unidimensional de 50 elementos contendo números inteiros aleatórios entre 10 e 100 |
| 52 | Gerar uma matriz 4x4 com números inteiros de 1 a 16 e extrair a última linha                      |
| 53 | Criar um array de zeros com comprimento 15 e substituir os valores da 5ª à 10ª posição por 1      |
| 54 | Gerar um array de 100 números inteiros aleatórios e encontrar a mediana e a moda dos valores      |
| 55 | Criar um array de 20 elementos entre 1 e 100 e substituir todos os valores múltiplos de 3 por -3  |
| 56 | Gerar uma matriz 5x5 de números aleatórios entre 0 e 1 e encontrar a soma de cada coluna          |
| 57 | Criar dois arrays de números aleatórios e encontrar a correlação entre eles                       |
| 58 | Gerar uma matriz 3x3 com números inteiros aleatórios e elevar todos os elementos ao quadrado      |
| 59 | Criar um array com 10 números aleatórios e normalizar seus valores entre 0 e 1                    |
| 60 | Criar uma matriz identidade 6x6 e substituir a diagonal principal por valores crescentes de 1 a 6 |
| 61 | Gerar um array de 100 números inteiros e encontrar o valor que mais se repete no array            |
| 62 | Criar uma matriz 4x4 e substituir os valores da diagonal principal por 7                          |
| 63 | Criar um array com os 10 primeiros números pares e calcular sua soma cumulativa                   |
| 64 | Calcular a diferença entre dois arrays de mesmo comprimento e encontrar a média das diferenças    |
| 65 | Gerar um array de 20 números e substituir todos os valores maiores que 50 por 50                  |
| 66 | Criar um array unidimensional e reorganizar seus valores em uma matriz 3x4                        |
| 67 | Gerar uma matriz 4x4 de números aleatórios e multiplicar cada valor por sua posição na matriz     |
| 68 | Criar um array de 10 elementos entre 1 e 100 e substituir os múltiplos de 5 por 0                 |
| 69 | Criar dois arrays de tamanho 20 e calcular o ângulo entre eles (produto escalar normalizado)      |
| 70 | Criar uma matriz de números inteiros e encontrar o valor mínimo de cada linha                     |

### SciPy (71–90)

| # | Exercício |
|----|-----------------------------------------------------------------------------------------|
| 71 | Calcular a integral da função f(x) = x²·sin(x) no intervalo de 0 a π                    |
| 72 | Resolver a equação diferencial dy/dx = x − y, com y(0) = 1, no intervalo de 0 a 10      |
| 73 | Encontrar as raízes da função f(x) = x⁴ − 3x³ + 2 utilizando SciPy                      |
| 74 | Usar a função de otimização de SciPy para maximizar f(x) = −x² + 4x + 1                 |
| 75 | Calcular a transformada de Fourier de um sinal composto de sin(2πt) e cos(4πt)          |
| 76 | Encontrar a matriz inversa de uma matriz 5x5 de números aleatórios                      |
| 77 | Usar interpolação cúbica para interpolar os pontos (0,0), (1,2), (2,3), (3,5), (4,4)    |
| 78 | Resolver o sistema de equações 3x + 2y = 5 e x + 4y = 6                                 |
| 79 | Ajustar uma curva quadrática aos pontos (1,2), (2,4), (3,5), (4,7), (5,8)               |
| 80 | Calcular a integral dupla de f(x,y) = xy + x² no intervalo [0,2] para x e [0,1] para y  |
| 81 | Encontrar os autovalores e autovetores de uma matriz 4x4 de números inteiros aleatórios |
| 82 | Resolver a equação eˣ − x² = 0 para encontrar a raiz mais próxima de x = 1              |
| 83 | Calcular o determinante de uma matriz 6x6 de números aleatórios entre -10 e 10          |
| 84 | Usar otimização multivariada para minimizar f(x,y) = (x−2)² + (y−3)²                    |
| 85 | Calcular a transformada de Fourier inversa de um sinal complexo aleatório               |
| 86 | Resolver a equação diferencial de 2ª ordem d²y/dx² + y = 0, com y(0)=1 e y′(0)=0        |
| 87 | Encontrar a raiz cúbica de 27 utilizando SciPy                                          |
| 88 | Interpolar f(x) = x² nos pontos [1,2,3,4,5] utilizando spline cúbica                    |
| 89 | Realizar a transformada de Fourier de um sinal discreto composto de senos e cossenos    |
| 90 | Resolver um sistema de equações lineares com três variáveis utilizando SciPy            |

### Pandas (91–110)

| #   | Exercício |
|-----|---------------------------------------------------------------------------------------------------|
| 91  | Criar um DataFrame contendo as colunas Produto, Preço e Quantidade com 5 produtos                 |
| 92  | Ler um arquivo Excel chamado vendas.xlsx e exibir as 10 primeiras linhas                          |
| 93  | Filtrar um DataFrame para exibir apenas os valores onde a coluna Preço é maior que 100            |
| 94  | Adicionar uma coluna Desconto ao DataFrame com 10% de desconto para todos os produtos             |
| 95  | Remover as linhas do DataFrame que contenham valores nulos                                        |
| 96  | Ordenar o DataFrame pela coluna Produto em ordem alfabética                                       |
| 97  | Criar uma coluna Total que seja o produto entre as colunas Preço e Quantidade                     |
| 98  | Agrupar o DataFrame pela coluna Categoria e calcular o total de produtos por categoria            |
| 99  | Exportar o DataFrame resultante para um arquivo CSV chamado resultados.csv                        |
| 100 | Ler um arquivo CSV, renomear as colunas e exibir as 5 últimas linhas do DataFrame                 |
| 101 | Preencher os valores nulos de uma coluna numérica com a mediana dessa coluna                      |
| 102 | Verificar quais colunas de um DataFrame contêm valores duplicados                                 |
| 103 | Criar uma tabela dinâmica calculando a soma de Quantidade por Categoria                           |
| 104 | Mesclar dois DataFrames baseados em uma coluna comum chamada ID utilizando um join                |
| 105 | Criar um DataFrame com dados faltantes e usar interpolação linear para preenchê-los               |
| 106 | Criar um gráfico de barras a partir de um DataFrame usando a biblioteca Pandas                    |
| 107 | Adicionar uma coluna que calcule o imposto (5%) sobre o valor da coluna Total                     |
| 108 | Exibir apenas as linhas onde o nome do produto começa com a letra "B"                             |
| 109 | Criar um DataFrame a partir de um dicionário de listas e calcular a média de cada coluna numérica |
| 110 | Agrupar os dados por uma coluna categórica e calcular a mediana de uma coluna numérica            |

### Matplotlib (111–130)

| #   | Exercício |
|-----|--------------------------------------------------------------------------------------------|
| 111 | Criar um gráfico de linha para a função y = x³ no intervalo de x = −10 até x = 10          |
| 112 | Plotar um gráfico de dispersão para 100 pontos aleatórios com cor baseada nos valores de y |
| 113 | Gerar um histograma para 500 números inteiros aleatórios entre 0 e 100                     |
| 114 | Criar um gráfico de barras para 5 categorias, colorindo cada barra de uma cor diferente    |
| 115 | Criar um gráfico de pizza para quatro setores de mercado com rótulos personalizados        |
| 116 | Plotar dois gráficos de linha em subplots diferentes: y1 = eˣ e y2 = log(x)                |
| 117 | Criar um gráfico de dispersão com tamanho dos pontos variando conforme os valores de y     |
| 118 | Plotar um gráfico de linha com intervalo de confiança (sombreamento) para y = sin(x)       |
| 119 | Adicionar título, rótulos e uma grade personalizada a um gráfico de linha                  |
| 120 | Plotar três gráficos de linha em um único gráfico, com cores e estilos diferentes          |
| 121 | Criar um gráfico de barras empilhadas para três categorias com três grupos de valores      |
| 122 | Plotar uma função quadrática ajustando os limites do eixo para x = −5 a x = 5              |
| 123 | Gerar um gráfico de dispersão 3D para 100 pontos aleatórios                                |
| 124 | Criar um gráfico de barras horizontal para 4 categorias com valores aleatórios             |
| 125 | Plotar a função y = 1/x com x variando de 1 a 100                                          |
| 126 | Criar um gráfico de linha com títulos nos eixos e um rótulo de texto no ponto x = 5        |
| 127 | Plotar um gráfico de linha e salvá-lo como um arquivo PDF                                  |
| 128 | Criar um gráfico de barras com valores positivos e negativos, usando cores diferentes      |
| 129 | Plotar um gráfico de linha com duas séries e adicionar uma legenda                         |
| 130 | Adicionar uma grade com espaçamento personalizado a um gráfico de linha para y = x²        |

</details>

---

## Tecnologias utilizadas

**Linguagem**

- Python 3

**Exercícios de Python e Ciência de Dados**

- `math` e `random` — operações matemáticas e valores aleatórios
- `numpy` — arrays e álgebra linear
- `scipy` — integração, otimização, interpolação e transformadas de Fourier
- `pandas` — análise de dados tabulares
- `matplotlib` — visualização de dados
- `openpyxl` — leitura e escrita de arquivos `.xlsx` no Pandas (exercício 92)

**Aprendizado de máquina**

- `scikit-learn` — regressão, SVM, árvores, Random Forest, Boosting, K-Means, PCA, `GridSearchCV` e métricas
- `seaborn` — gráficos estatísticos
- `kagglehub` — download dos datasets do Kaggle

**AutoML**

- `flaml` — AutoML
- `auto-sklearn` — AutoML (Python 3.9, ambiente separado)
- `psutil` — medição de uso de memória

---

## Como executar

Os trabalhos estão em formato Jupyter Notebook (`.ipynb`). Você pode executá-los com:

- Google Colab
- Jupyter Notebook
- JupyterLab
- VS Code com suporte a notebooks

### Google Colab

1. Acesse o [Google Colab](https://colab.research.google.com).
2. Abra o arquivo `.ipynb`.
3. Execute as células em ordem.
4. Nos exercícios que utilizam `input()`, digite os valores solicitados.

### Instalação das bibliotecas (execução local)

```bash
# Exercícios de Python e Ciência de Dados
pip install numpy scipy pandas matplotlib openpyxl

# Notebooks de aprendizado de máquina
pip install scikit-learn seaborn kagglehub

# Notebook de AutoML (FLAML)
pip install flaml psutil
```

No Google Colab, `numpy`, `scipy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn` e `openpyxl` já vêm instalados, então normalmente não é preciso rodar nenhum comando extra.

> **Observações:**
> - Os notebooks de classificação baixam os datasets do Kaggle, então é necessário ter conexão com a internet.
> - O notebook de AutoML foi feito para o Google Colab: o Auto-Sklearn é instalado em um ambiente separado com Python 3.9, criado pelo próprio notebook (leva alguns minutos na primeira execução).

---

## Autora

**Amanda Barreto Lima** — 6º período, Turma A · Disciplina de Inteligência Artificial
