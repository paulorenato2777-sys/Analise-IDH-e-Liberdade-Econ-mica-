# Analise-IDH-e-Liberdade-Econ-mica-
Análise de Machine Learning (Random Forest e K-Means) para identificar o impacto dos 12 pilares da liberdade econômica no IDH global.
# 🌍 Análise de Dados: Impacto da Liberdade Econômica no IDH

Este projeto utiliza **Machine Learning** para investigar a relação entre os 12 pilares da liberdade econômica (Heritage Foundation) e o Índice de Desenvolvimento Humano (IDH - ONU). O objetivo é identificar quais características institucionais e econômicas possuem maior peso no desenvolvimento social global.

## 🚀 Destaques do Projeto
*   **Integração de Dados:** Cruzamento automatizado de bases de dados CSV e Excel via Pandas.
*   **Feature Importance:** Uso do algoritmo **Random Forest** para ranquear as variáveis mais influentes.
*   **Clustering:** Agrupamento de países em 5 perfis distintos utilizando **K-Means**.
*   **Automação:** Script configurado para download direto de fontes em nuvem.

## 📊 Resultados do Modelo
O modelo identificou que a **Liberdade de Negócios (Business Freedom)** é o fator preponderante, representando aproximadamente **67%** da importância no impacto sobre o IDH, seguida por Direitos de Propriedade e Liberdade Comercial.


| Rank | Variável | Importância |
| :--- | :--- | :--- |
| 1º | Business Freedom | 67.57% |
| 2º | Property Rights | 6.71% |
| 3º | Trade Freedom | 6.28% |
| 4º | Government Spending | 3.69% |

## 🛠️ Tecnologias Utilizadas
*   **Python 3.x**
*   **Pandas & NumPy:** Manipulação e tratamento de dados.
*   **Scikit-Learn:** Pré-processamento (`MinMaxScaler`), Clustering (`KMeans`) e Regressão (`RandomForestRegressor`).
*   **Matplotlib & Seaborn:** Visualização de dados e gráficos de importância.

## 📂 Como rodar este projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com
   ```
2. Instale as dependências:
   ```bash
   pip install pandas scikit-learn seaborn matplotlib requests
   ```
3. Execute o script Python para gerar os gráficos e o ranking.

---
**Contato:** [paulorenato2777@gmail.com](mailto:paulorenato2777@gmail.com)
