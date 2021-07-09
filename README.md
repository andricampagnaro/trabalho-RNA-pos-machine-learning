# Trabalho sobre Redes Neurais Artificiais
Trabalho sobre Redes Neurais Artificiais, para a pós em Machine Learning.

## Resumo da solução
O trabalho tinha como objetivo analisar um dataset de contagem de arruelas, para que fosse possível criar um modelo que aprendesse a classificar a quantidade de arruelas entre uma e duas. 

O modelo já vinha pré-desenhado e com uma solução proposta pelo professor, a qual garantia uma acurácia de 86,1%. O objetivo era melhorar o modelo, aumentando esta acurácia. 

Após analisar o dataset e a solução inicial proposta pelo professor, tentei efetuar algumas alterações a nível de quantidade de neurônios e quantidade de épocas de treino, para verificar se o modelo poderia ser melhorado sem alteração nas features utilizadas. 

Como não houve evolução da acurácia, alterei as features de entrada, adicionando duas que me pareceram interessantes ao aprendizado às demais já inclusas. 

Originalmente, estavam sendo consideradas as features “NumAmostra”, “Area” e “Delta”, e eu adicionei as features “Tamanho” e “Referência”. 

Além disso, aumentei a quantidade de neurônios da camada oculta de cinco para dez. 

E, após analisar o gráfico de evolução do erro, concluí que poderia reduzir a quantidade de épocas de aprendizado de 200000 para 6000. 

Ao todo, foram realizados 15 testes até chegar à solução final. 

Assim, com as alterações acima descritas, a acurácia do modelo passou de 86,1% para 97,5%, o que foi um ganho significativo na resposta dada pelo modelo.

## PALAVRAS-CHAVE
Redes Neurais. Machine Learning. RNA.
