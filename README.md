# Atividade-Regr# 📈 Atividade – Módulo 11 | Regressão Avançada e Regularização

Este repositório contém uma atividade prática desenvolvida no **Módulo 11 do curso de Python / Ciência de Dados**, com foco em **regressão linear avançada**, **polinomial** e **técnicas de regularização** como **Ridge** e **Lasso**, utilizando **scikit-learn**.

O objetivo do projeto é **comparar modelos de regressão**, entender o impacto da complexidade do modelo e analisar como a regularização ajuda a evitar **overfitting**.

---

## 🧠 O que é feito neste projeto

O notebook executa as seguintes etapas:

1. **Importação de bibliotecas**

   * pandas, numpy
   * matplotlib
   * scikit-learn

2. **Geração de dados sintéticos**

   * Uso de datasets artificiais com `make_friedman1`
   * Criação de dados para simular problemas reais de regressão

3. **Regressão Linear Simples**

   * Treinamento de um modelo base com `LinearRegression`
   * Avaliação do comportamento inicial do modelo

4. **Regressão Polinomial**

   * Expansão das features com `PolynomialFeatures`
   * Análise do impacto do aumento do grau do polinômio

5. **Pipeline de Machine Learning**

   * Encadeamento de etapas com `Pipeline`
   * Padronização dos dados com `StandardScaler`
   * Treinamento do modelo de forma organizada e reutilizável

6. **Regularização Ridge (L2)**

   * Redução da complexidade do modelo
   * Controle de coeficientes grandes
   * Comparação com regressão linear comum

7. **Regularização Lasso (L1)**

   * Seleção automática de variáveis
   * Zerar coeficientes menos relevantes

8. **Comparação entre modelos**

   * Linear vs Polinomial
   * Ridge vs Lasso
   * Avaliação visual e conceitual dos resultados

9. **Visualização dos resultados**

   * Gráficos para análise do ajuste dos modelos
   * Comparação entre curvas previstas

---

## 📁 Estrutura do repositório

```
📂 projeto-modulo-11
 ├── atividade_modulo_11.ipynb
 └── README.md
```

---

## 📦 Bibliotecas utilizadas

* pandas
* numpy
* matplotlib
* scikit-learn

---

## ▶️ Como executar o projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. Instale as dependências:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

3. Abra o notebook:

   ```bash
   jupyter notebook
   ```

4. Execute as células em ordem.

---

## 🎯 Aprendizados principais

* Diferença entre modelos simples e polinomiais
* Problemas de overfitting em modelos complexos
* Importância da regularização
* Uso de Ridge e Lasso para controle de coeficientes
* Organização de código com Pipelines

---

## 👤 Autor

Projeto desenvolvido por **Samuel Lopes**
Estudante de Ciência de Dados | Python | SQL | Machine Learning

---

📌 *Projeto com finalidade educacional, voltado ao aprendizado de regressão e regularização em Machine Learning.*
ess-o-Avan-ada-Regulariza-o
