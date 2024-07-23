# Análise de Qualidade de Vinhos

Este projeto realiza uma análise exploratória e preditiva em um conjunto de dados de vinhos para entender os fatores que influenciam a qualidade do vinho.

## Contexto

O conjunto de dados contém várias características físico-químicas dos vinhos, juntamente com a avaliação de qualidade. O objetivo principal é identificar quais características mais influenciam a qualidade do vinho, com o objetivo de descobrir tendencias e padrões de como fazer uma produção de niveis mais elevados, o conjunto de dados utiliza várias métricas e caracteristicas junto de sua nota que varia de 3 a 8 

## Análise Exploratória

Primeiro, verificamos a presença de valores nulos no conjunto de dados e constatamos que não há valores nulos a serem tratados. Em seguida, realizamos visualizações gráficas para entender como cada característica difere entre vinhos de diferentes níveis de qualidade.

Depois treinamos um modelo de Random Forest para identificar as características mais importantes para a classificação da qualidade do vinho, sendo a característica identificada como mais influente na qualidade foi a concentração de álcool.

## Avaliação do Modelo

Dividimos os dados em 70% para treino e 30% para teste, e avaliamos a precisão do modelo depois criamos uma visualização e um calculo percentual para avaliar como o modelo perfomou, a precisão do modelo foi aproximadamente 67%, o que é um resultado esperado considerando a quantidade de elementos presentes e as semelhanças entre muitas características dos vinhos.

## Conclusão
Apesar das várias características analisadas, a concentração de álcool foi a mais significativa para a classificação da qualidade do vinho. No entanto, é importante lembrar que a qualidade do vinho é subjetiva e pode variar conforme o gosto do consumidor. O objetivo final deve ser sempre atender às expectativas e proporcionar uma experiência agradável ao cliente.

