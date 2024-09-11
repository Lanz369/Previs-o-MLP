# Previsao-MLP
Modelo de machine learning utilizando MLPClassifier para fazer previsão de doenças cardíacas.
Utilizando biblioteca pública do kaggle: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset/data

# Contexto
Este conjunto de dados é de 1988 e consiste em quatro bases de dados: Cleveland, Hungria, Suíça e Long Beach V.
Ele contém 76 atributos, incluindo o atributo previsto, mas todos os experimentos publicados referem-se ao uso de um subconjunto de 14 deles.
O campo "target" refere-se à presença de doença cardíaca no paciente. É um valor inteiro onde 0 = sem doença e 1 = com doença.

# Conclusão
O modelo de MLP apresentou uma boa eficiência na previsão de doenças cardíacas, destacada pela alta pontuação da AUC. A curva ROC mostrou que o modelo é robusto em diferenciar entre os casos de doença e não doença, mesmo em cenários desafiadores.

Em resumo, o uso de técnicas de pré-processamento robustas, a escolha de uma arquitetura de rede neural adequada, e a otimização através do GridSearchCV foram fundamentais para atingir um modelo eficiente e confiável para a previsão de doenças cardíacas. Este trabalho demonstra a importância de cada etapa no pipeline de machine learning para alcançar resultados de alta qualidade em tarefas de classificação médica.

# Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.
