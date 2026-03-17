# petroleo-timeseries-analysis
Exploring historical oil prices with time series models and visualizations in R
# Petroleum Time Series Analysis

Análise do preço do petróleo usando modelos clássicos de séries temporais em **R**, incluindo AR, MA, ARMA, ARIMA, SARIMA e Holt-Winters. Este projeto explora tendências históricas, padrões sazonais e simulações futuras de preços.

---

## 🔹 Objetivo

- Entender como o histórico do petróleo ajuda a prever tendências futuras.
- Aplicar **modelos de séries temporais** para capturar memória de curto prazo, padrões sazonais e flutuações regulares.
- Simular cenários futuros de preço com base em dados históricos.

---

## 🔹 Modelos Utilizados

| Modelo | Uso |
|--------|-----|
| AR / MA / ARMA | Captura memória de curto prazo |
| ARIMA / SARIMA | Detecta tendências e padrões sazonais |
| Holt-Winters | Modela média, tendência e sazonalidade juntas |

---

## 🔹 Principais Descobertas

- O petróleo apresenta **memória de curto prazo** e **leve padrão sazonal anual**.
- Os modelos capturam **quase toda a variação histórica** sem deixar resíduos importantes.
- Com o **choque do Estreito de Ormuz**, os modelos projetam:
  - **Aumento e queda nos dois meses seguintes**
  - **Retorno ao patamar anterior em cerca de 8 meses**
- ⚠️ Os modelos **não captam choques inesperados isolados**, apenas padrões históricos.

---

## 🔹 Código e Visualizações

O repositório inclui:

- Scripts em **R** para:
  - Baixar histórico do preço do petróleo (`quantmod`)  
  - Transformar dados em retornos logarítmicos  
  - Ajustar **AR, MA, ARMA, ARIMA, SARIMA e Holt-Winters**  
  - Simular projeções futuras  
- Gráficos de séries temporais e projeções.

---

## 🔹 Como Usar

1. Clone o repositório:  
```bash
git clone https://github.com/seu-usuario/petroleo-timeseries-analysis.git
