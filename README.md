# Aplicação de Árvores de Hoeffding para Predição de Preços de Energia Elétrica sob Mudanças de Conceito

<p align="justify">
O mercado de energia elétrica caracteriza-se por alta volatilidade e complexidade estrutural, tornando a previsão precisa de preços essencial para formulação de estratégias comerciais e mitigação de riscos financeiros. Abordagens tradicionais de aprendizado de máquina, como ARIMA e SVMs, frequentemente assumem estacionariedade dos dados, hipóteses que se tornam nulas em ambientes sujeitos a mudanças estruturais, sazonalidades complexas e fenômenos de deriva de conceito.
</p>

<p align="justify">
Este trabalho investiga a aplicabilidade de <strong>Árvores de Hoeffding</strong> e a variante <strong>Árvores Adaptativas de Hoeffding</strong> para predição de preços de energia elétrica considerando as eventuais mudanças de conceito. O objetivo é avaliar comparativamente o desempenho preditivo dos algoritmos de Hoeffding, verificando se a incorporação de mecanismos de detecção e adaptação a mudanças de conceito resulta em desempenho superior.
</p>

<p align="justify">
A metodologia, estruturada segundo os frameworks <strong>CRISP-DM</strong> e <strong>KDD</strong>, utiliza o dataset público <em><strong>"Hourly energy demand generation and weather"</strong></em> da Espanha, contendo 35.000 observações horárias de 2015 a 2018. Os modelos serão avaliados por métricas quantitativas (<strong>RMSE, MAE, MAPE, R²</strong>) e análises de adaptação a mudanças de conceito, incluindo tempo de recuperação e substituições de ramos.
</p>

<p align="justify">
Espera-se demonstrar que <strong>algoritmos adaptativos incrementais</strong> apresentam vantagens significativas em ambientes não estacionários, contribuindo para o avanço teórico e prático em predição de séries temporais energéticas.
</p>


## Ambiente computacional

Uma stack de ML é composta por diversas categorias de ferramentas que cobrem o ciclo de vida completo de um projeto — desde a coleta de dados até a avaliação dos modelos.

---

## Como reproduzir os experimentos

---

## Autor

- [Kaique Moraes](https://www.linkedin.com/in/kaiquemoraesti/)
  
---

## Licença

- [MIT](https://choosealicense.com/licenses/mit/)

---

## Etiquetas

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Dataset](https://img.shields.io/badge/Dataset-Energy%20Consumption%20%26%20Weather-blueviolet.svg)](https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Hoeffding%20Trees-orange.svg)](https://riverml.xyz/dev/api/tree/HoeffdingTreeRegressor/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Hoeffding%20Adaptatives%20Trees-red.svg)](https://riverml.xyz/dev/api/tree/HoeffdingAdaptiveTreeRegressor/)


