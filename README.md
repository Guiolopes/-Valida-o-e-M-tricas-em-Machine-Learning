# 📊 Validação e Métricas em Machine Learning

## 📌 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de estudar e aplicar técnicas de validação e métricas de avaliação em modelos de Machine Learning.

O foco principal está em compreender como avaliar corretamente o desempenho de modelos de classificação, evitando interpretações equivocadas causadas por métricas isoladas ou divisões incorretas dos dados.

---

## 🎯 Objetivos

- Entender a importância da separação correta dos dados
- Aplicar técnicas de validação
- Avaliar modelos utilizando diferentes métricas
- Interpretar matrizes de confusão
- Identificar problemas como overfitting e viés

---

## 🚀 Tecnologias Utilizadas

- Python
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn

---

## 🔎 Conceitos Trabalhados

### 🔹 Separação de Dados

O projeto aborda a importância da divisão dos dados em:

- Treino
- Validação
- Teste

Além disso, explora os riscos de modelos treinados em bases enviesadas ou mal distribuídas.

---

### 🔹 Estratificação

Foi utilizada estratificação para manter a proporção das classes durante a separação dos dados, reduzindo distorções estatísticas.

---

### 🔹 Overfitting

O projeto demonstra como modelos podem memorizar padrões específicos da base de treino e perder capacidade de generalização.

Também foram analisados:

- Underfitting
- Generalização do modelo
- Impacto da complexidade do algoritmo

---

## 📈 Métricas de Avaliação

Foram utilizadas métricas fundamentais para classificação supervisionada:

| Métrica | Função |
|---|---|
| Accuracy | Mede o desempenho geral |
| Precision | Mede a proporção de positivos corretos |
| Recall | Mede a capacidade do modelo encontrar positivos reais |
| F1-Score | Equilibra precisão e recall |
| Matriz de Confusão | Mostra acertos e erros detalhadamente |

---

## 🧠 Principais Aprendizados

- Acurácia nem sempre representa um bom modelo
- Bases desbalanceadas podem gerar interpretações equivocadas
- A validação correta reduz riscos de overfitting
- Métricas devem ser analisadas em conjunto
- Separação incorreta dos dados pode enviesar resultados

---

## 📂 Estrutura do Projeto

```bash
📁 projeto
 ┣ 📓 Classificação_Validação_e_Metricas_.ipynb
 ┗ 📄 README.md
