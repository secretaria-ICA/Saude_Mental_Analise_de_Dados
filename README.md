# Projeto_Final
Projeto Final Bi Master - Business Intelligence Master
#### Aluno: [Silvana de Jesus Silva](https://github.com/Silvana-js)
#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler)
---
Data:

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

https://github.com/Silvana-js/Projeto_Final.git

---

### Resumo

O tema saúde mental tem crescido nos últimos anos, principalmente agora em virtude da pandemia relacionada à COVID-19.

Tanto o mundo científico quanto o empresarial está cada vez mais está preocupado com esse tema e infelizmente estamos passando pelo pior momento da pandemia no Brasil até agora.

Pensando nisso, o objetivo desse trabalho é auxiliar na identificação se o paciente será diagnosticado com alguma condição de saúde mental 

(coluna 'Have you been diagnosed with a mental health condition by a medical professional?').

Utilizamos uma base do Kaggle (https://www.kaggle.com/ron2112/mental-health-data) para iniciarmos esse estudo, embora os dados estejam em inglês,  os conceitos básicos são os mesmos, os mesmos tipos de sintomas são sentidos em qualquer lugar do mundo.

### Introdução

O trabalho envolveu a análise de 8 modelos diferentes com o apoio da ferramenta o RapidMiner 9.9, em todos eles foram considerados as etapas: análise exploratória de dados, missing values e reavaliação dos atributos pelo peso.

### Fundamentação Teórica

A mineração de dados pode ser considerada como uma parte do processo de Descoberta de Conhecimento em Banco de Dados (KDD – Knowledge Discovery in Databases).

Dentro do universo da mineração de dados temos 5 classes de problemas:

    Previsão
    Classificação
    Regressão
    Agrupamento
    Associação
    
  Destacamos que no caso desse trabalho foi feita análise através do método supervisionado - classificação, onde o rótulo é categórico.


### Modelagem

Primeiramente foi feita a análise dos dados para entender quais atributos manter no modelo, em seguida foi verificado quais atributos apresentaram missing values e com isso a funcionalidade de Replace Missing Values do RapidMiner foi utilizada.

Para entender a relevância de cada atributo em relação ao rótulo a ser classificado, as funcionalidades Weight by Information Gain e Select by Weights do RapidMiner foram consideradas para que somente os atributos com pesos relevantes fossem considerados.  

O balanceamento dos dados e processo para gerar as duas bases tratadas, nesse ponto fiz um processo no RapidMiner para gerar as duas bases, a de treino e a de teste.

Diferentes modelos foram testados usando os seguintes algoritmos de classificação: Decision Tree, Deep Learning, KNN, Naive Bayes, SVM, Random Forest, Random Tree e Neural Net.

### Resultados

    Decision Tree

    Deep Learning

    KNN

    Naive Bayes

    SVM

    Random Forest

    Random Tree

    Neural Net


### Conclusão

O modelo com a melhor acurácia...

### Considerações finais

Gostaria de agradecer a todos os professores do curso e em especial à professora Manoela Kohler pelas aulas e orientação nesse trabalho.

---

Matrícula: 192.671.163

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
