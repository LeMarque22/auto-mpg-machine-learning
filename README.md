# auto-mpg-machine-learning

# Análise Preditiva de Consumo Automotivo com IA (Auto MPG)

Projeto desenvolvido para prever a eficiência de combustível de veículos (Milhas por Galão - MPG) com base em especificações mecânicas, unindo Inteligência Artificial e Ciência de Dados.

## 🛠️ Tecnologias Utilizadas
* Python (Pandas, NumPy, Matplotlib)
* Scikit-Learn (Perceptron Multicamadas - MLP)
* Scikit-Fuzzy (Lógica Fuzzy)

## 📊 O que foi feito
* **Pipeline de Dados:** Limpeza de dados nulos usando imputação por mediana, engenharia de atributos (extração de strings) e escalonamento de grandezas físicas com `MinMaxScaler`.
* **Redes Neurais (Conexionismo):** Treinamento de um `MLPRegressor` com otimização de hiperparâmetros. O modelo atingiu **85% de precisão (R²)** e um **Erro Médio Absoluto (MAE) de apenas 2.17 MPG** em dados invisíveis (Teste).
* **Lógica Fuzzy (Raciocínio Simbólico):** Desenvolvimento de um simulador linguístico para estabelecer um contraponto crítico: a precisão cirúrgica de um algoritmo "caixa preta" (MLP) versus a explicabilidade moral e transparência da inferência Fuzzy.
