# 📊 Projeto: IDH e Liberdade Econômica

## 🎯 Objetivo

Analisar a relação entre as **características da Liberdade Econômica** (índice da Heritage Foundation) e o **Índice de Desenvolvimento Humano (IDH)**, utilizando dois métodos estatísticos para validar os resultados e **identificar as 3 principais características mais conectadas ao IDH**.

---

## 📁 Base de Dados

- **IDH**: dados do Programa das Nações Unidas para o Desenvolvimento (PNUD)
- **Liberdade Econômica**: dados da Heritage Foundation (12 características)

---

## 🛠️ Métodos Utilizados

- **Correlação**: mede a relação linear entre cada característica e o IDH
- **Random Forest Regressor**: mede a importância de cada característica na previsão do IDH

---

## 💡 Análise das Principais Características

Para entender os resultados, veja por que essas características impactam tanto o IDH na prática:

* **Liberdade Empresarial (Business Freedom):** Reduz a burocracia para abrir e operar negócios. Isso facilita a criação de empresas, estimula a contratação de funcionários e gera salários mais altos, impactando diretamente a renda e o bem-estar da população.
* **Direitos de Propriedade (Property Rights):** Garante a segurança jurídica de que o cidadão é dono do que construiu ou comprou. Sem medo de expropriação, as pessoas e empresas investem mais no longo prazo em saúde, educação e infraestrutura.
* **Integridade Governamental (Government Integrity - Forte na Correlação):** Menos corrupção significa que o dinheiro dos impostos é melhor investido em serviços públicos essenciais que compõem o IDH, como saúde e educação básica.
* **Liberdade Comercial (Trade Freedom - Forte no Random Forest):** O acesso a mercados globais barateia o custo de vida e permite que o país importe tecnologias e medicamentos, elevando o padrão de desenvolvimento humano.


---

## 📈 Resultados

### 1. Correlação com IDH

| Característica | Correlação |
|----------------|------------|
| Business Freedom | 0.86 |
| Property Rights | 0.78 |
| Government Integrity | 0.73 |
| Trade Freedom | 0.69 |
| Judicial Effectiveness | 0.68 |
| Financial Freedom | 0.63 |
| Investment Freedom | 0.52 |
| Labor Freedom | 0.38 |
| Monetary Freedom | 0.25 |
| Fiscal Health | 0.22 |
| Tax Burden | -0.20 |
| Government Spending | -0.50 |

---

### 2. Importância no Random Forest

| Característica | Importância |
|----------------|-------------|
| Business Freedom | 63.6% |
| Property Rights | 12.9% |
| Trade Freedom | 5.7% |
| Government Integrity | 3.4% |
| Tax Burden | 3.0% |
| Government Spending | 2.8% |
| Fiscal Health | 2.2% |
| Labor Freedom | 2.1% |
| Judicial Effectiveness | 1.3% |
| Investment Freedom | 1.3% |
| Monetary Freedom | 1.0% |
| Financial Freedom | 0.7% |

---

## 🧠 Conclusão Principal

> **A Liberdade Empresarial (Business Freedom) é a característica da Liberdade Econômica com maior relação com o IDH, seguida pelos Direitos de Propriedade (Property Rights).**

Os dois métodos utilizados (correlação e Random Forest) chegaram a resultados **consistentes**, reforçando a validade da conclusão.

---

## ⚠️ Ressalva

Os resultados indicam **associação**, não causalidade. Países com alta liberdade empresarial tendem a ter IDH mais alto, mas isso não significa que uma seja causa direta da outra.

---

## 🔍 Próximos Passos (Sugestão)

- Analisar a relação ao longo do tempo (séries temporais)
- Incluir outras variáveis (PIB per capita, Gini, educação, saúde)
- Investigar exceções (países que fogem à regra)

