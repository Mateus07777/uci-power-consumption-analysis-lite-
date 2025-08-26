
# Individual Household Electric Power Consumption — **(2007)**

Este repositório contém a solução dos **20 exercícios** usando apenas o **ano de 2007** do dataset
*Individual Household Electric Power Consumption* (UCI). Essa redução torna o projeto leve e adequado para o GitHub.

## Como reproduzir
```bash
pip install pandas numpy matplotlib scikit-learn statsmodels
```
Coloque o arquivo `data/household_power_consumption_2007.csv` no lugar (já incluído) e use os notebooks ou scripts para gerar resultados.

## Entregáveis
- `results/` → tabelas .csv (médias diárias/mensais, correlações, K-means, etc.)
- `figures/` → gráficos (itens 6, 7, 14, 16, 19)
- `scripts/analysis.py` → script com notas e métricas (item 20)

## Notas importantes
- **Global_active_power (kW)** é potência ativa (energia útil).  
- **Global_reactive_power (kVAR)** é potência reativa (não realiza trabalho útil).

## Métricas do item 20 (Linear Regression — 2007 deste ambiente)
- Coeficiente (a): 0.236648
- Intercepto (b): -0.010502
- MAE: 0.034041
- RMSE: 0.050336
- R²: 0.998124
