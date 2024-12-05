# **Autoformer com Soft-DTW para Predição em Séries Temporais de Criptomoedas** 📊💸

## **📖 Descrição**

Neste trabalho, propõe-se a adaptação do modelo Autoformer para incorporar o Soft-DTW Loss.

### **Objetivos:**
- Adaptar o Autoformer para utilizar o Soft-DTW como medida de perda durante o treinamento.
- Comparar o desempenho do modelo adaptado com o original e outros modelos baseline.  

---

## **🚀 Funcionalidades**

- ✅ Predição com Long Short Term Memory (LSTM).
- ✅ Predição com Gated Recurrent Unit (GRU).
- ✅ Predição com Autoformer Simplficado utilizando MSE Loss.
- ✅ Predição com Autoformer Simplficado utilizando Soft-DTW Loss.
- ✅ Aplicação de métricas de desempenho para comparação dos modelos.

---

## **🛠️ Tecnologias Utilizadas**

Este projeto foi desenvolvido com as seguintes bibliotecas e ferramentas:

- **Python**: Linguagem principal utilizada para o desenvolvimento do projeto.
- **Pandas**: Manipulação e análise de dados estruturados em DataFrames.
- **NumPy**: Operações matemáticas eficientes em arrays multidimensionais.
- **Matplotlib**: Criação de gráficos e visualizações simples.
- **Seaborn**: Visualização de dados estatísticos com gráficos detalhados.
- **Statsmodels**: Decomposição sazonal e análise de séries temporais.
- **PyTorch**: Framework para construção e treinamento de modelos de aprendizado profundo.
- **torch.nn**: Módulo de construção de redes neurais com camadas personalizadas.
- **Scikit-learn**: Utilizado para divisão de dados com `train_test_split`.
- **tslearn.metrics**: Implementação da função de perda DTW suave (`SoftDTWLossPyTorch`).
- **MultiheadAttention (PyTorch)**: Mecanismo de atenção multi-cabeça para modelos baseados em Transformer.
- **Scikit-learn (Métricas)**: Avaliação do modelo com:
  - `mean_absolute_error` (Erro Absoluto Médio)
  - `mean_squared_error` (Erro Quadrático Médio)
  - `root_mean_squared_error` (Raiz do Erro Quadrático Médio)

