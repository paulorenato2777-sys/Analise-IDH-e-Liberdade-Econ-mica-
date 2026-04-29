# 📊 Machine Learning: Liberdade Econômica vs. IDH

Este projeto utiliza inteligência artificial para identificar quais fatores da liberdade econômica global possuem o maior impacto no desenvolvimento humano (**IDH**).

---

### 🛠️ Metodologia Técnica

*   **Modelo:** `Random Forest Regressor`
*   **Validação:** Validação Cruzada (10-fold)
*   **Escalonamento:** `StandardScaler`
*   **Hiperparâmetros:** `n_estimators=200`, `max_features=3`, `min_samples_split=5`

---

### 🏆 Ranking de Impacto (Feature Importance)

O modelo analisou as 12 características fundamentais e definiu o seguinte peso de importância:

1.  **Liberdade Empresarial** (*Business Freedom*): **26,28%**
2.  **Direitos de Propriedade** (*Property Rights*): **15,49%**
3.  **Liberdade de Comércio** (*Trade Freedom*): **14,09%**
4.  **Integridade Governamental** (*Gov. Integrity*): **12,20%**
5.  **Eficácia Judicial** (*Judicial Effectiveness*): **7,33%**
6.  **Liberdade Financeira**: 6,04%
7.  **Gastos do Governo**: 4,95%
8.  **Liberdade de Investimento**: 3,54%
9.  **Carga Tributária**: 3,42%
10. **Liberdade do Trabalho**: 2,36%
11. **Saúde Fiscal**: 2,33%
12. **Liberdade Monetária**: 1,97%

---

### 💡 Principais Insights

*   **Concentração de Impacto:** As 5 principais características sozinhas explicam aproximadamente **75% da variação** do modelo.
*   **O "Top 3":** Liberdade para empreender, segurança jurídica (propriedade) e abertura comercial são os motores primários do desenvolvimento.
*   **Instituições Fortes:** A presença de *Integridade Governamental* e *Eficácia Judicial* no topo mostra que o crescimento econômico só se traduz em bem-estar social quando há instituições sólidas.

---

### 📂 Fontes dos Dados

*   **IDH:** Programa das Nações Unidas para o Desenvolvimento (**PNUD/ONU**).
*   **Liberdade Econômica:** **The Heritage Foundation**.

---
**Contato:** [paulorenato2777@gmail.com](mailto:paulorenato2777@gmail.com)
