# Projeto: Aprenda NumPy com Dados de Vendas de Maçãs

Este projeto é parte de um estudo prático sobre análise de dados usando a biblioteca **NumPy**, baseado em dados de vendas de maçãs na Rússia. Ele serve como um roteiro para quem deseja aprender, na prática, conceitos fundamentais de análise de dados com Python.

---

## 🎯 Objetivos do Projeto

- Ler e escrever dados usando o NumPy diretamente de arquivos CSV de fontes externas.
- Criar, manipular e operar arrays multidimensionais (ndarrays).
- Gerar números aleatórios e trabalhar com reprodutibilidade usando seeds.
- Realizar cálculos de regressão linear utilizando apenas funções básicas do NumPy.
- Explorar funções de agregação para sumarizar, analisar e visualizar grandes conjuntos de dados.

---

## 📚 Conteúdo Abordado

### 1. Leitura e Escrita de Dados

- Importação de dados diretamente de um CSV hospedado no GitHub com `np.loadtxt`.
- Manipulação de colunas e linhas para trabalhar apenas com os dados necessários.

### 2. Arrays Multidimensionais

- Criação de sequências numéricas com `np.arange`.
- Uso de slicing para separar dados por períodos (anos/meses).
- Análise da estrutura dos dados com `.ndim`, `.shape` e `.size`.

### 3. Números Aleatórios e Seeds

- Geração de vetores de inteiros e floats aleatórios com `np.random.randint` e `np.random.uniform`.
- Uso de `np.random.seed` para garantir reprodutibilidade.

### 4. Regressão Linear Simples

- Cálculo dos coeficientes angular (a) e linear (b) da reta dos mínimos quadrados usando apenas arrays NumPy.
- Medição do ajuste da regressão com a norma euclidiana (`np.linalg.norm`).
- Comparação de diferentes ajustes com linhas de regressão variando coeficientes.

### 5. Funções de Agregação

- Cálculo de médias por período e localidade com `np.mean`.
- Substituição de valores faltantes (`np.nan`) de forma programática.
- Aplicação de diferentes funções de agregação para análises exploratórias.

---

## 🛠️ Ferramentas Utilizadas

- **NumPy**: manipulação de arrays, operações matemáticas, geração de amostras aleatórias, agregações e regressão linear.
- **Matplotlib**: visualização de dados e resultados.
- **Python 3**: linguagem base para ciência de dados.

---

## ▶️ Como Executar

1. Clone este repositório e instale os pacotes necessários.
2. Execute os exemplos no Jupyter Notebook, Google Colab, ou diretamente via scripts Python.
3. Explore os scripts, modifique as análises, visualize gráficos e aprofunde seu aprendizado.
