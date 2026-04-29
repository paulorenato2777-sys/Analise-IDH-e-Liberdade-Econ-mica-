# Análise de Machine Learning - Liberdade Econômica x IDH

## Método Utilizado
- **Modelo:** Random Forest Regressor
- **Validação:** Cross-Validation (10 folds)
- **Pré-processamento:** StandardScaler
- **Hiperparâmetros:** n_estimators=200, max_features=3, min_samples_split=5

## Resultado Final - Ranking das 12 Características

| Posição | Característica | Importância (%) |
|---------|----------------|-----------------|
| 1º | Business Freedom | 26.28% |
| 2º | Property Rights | 15.49% |
| 3º | Trade Freedom | 14.09% |
| 4º | Government Integrity | 12.20% |
| 5º | Judicial Effectiveness | 7.33% |
| 6º | Financial Freedom | 6.04% |
| 7º | Government Spending | 4.95% |
| 8º | Investment Freedom | 3.54% |
| 9º | Tax Burden | 3.42% |
| 10º | Labor Freedom | 2.36% |
| 11º | Fiscal Health | 2.33% |
| 12º | Monetary Freedom | 1.97% |

## Principais Achados

As 5 características da liberdade econômica que mais impactam o IDH são:

1. **Business Freedom (26.28%)** - Liberdade para fazer negócios
2. **Property Rights (15.49%)** - Direito à propriedade
3. **Trade Freedom (14.09%)** - Liberdade comercial
4. **Government Integrity (12.20%)** - Integridade do governo 
5. **Judicial Effectiveness (7.33%)** - Eficiência judicial

## Conclusão

O modelo demonstra que a liberdade econômica tem relação significativa com o IDH, com destaque para fatores relacionados ao ambiente de negócios, direitos de propriedade e integridade institucional. As 5 principais características concentram aproximadamente 75% da importância total do modelo.
---
**Contato:** [paulorenato2777@gmail.com](mailto:paulorenato2777@gmail.com)
