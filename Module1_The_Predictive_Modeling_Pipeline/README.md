# O que você vai aprender

Este módulo dará um exemplo de um pipeline de modelagem preditiva típico desenvolvido usando dados tabulares (dados que podem ser estruturados em uma tabela bidimensional). Apresentaremos esse pipeline de forma progressiva. Primeiramente, faremos uma análise do conjunto de dados utilizado. Posteriormente, treinaremos nosso primeiro pipeline de previsão com um subconjunto do conjunto de dados. Em seguida, daremos atenção especial ao tipo de dados, numéricos e categóricos, que nosso modelo deve tratar. Por fim, estenderemos nosso pipeline para usar tipos mistos de dados, ou seja, dados numéricos e categóricos.

# Antes de começar

As habilidades técnicas necessárias para continuar este módulo são:


* conhecimento básico de programação Python
* alguma experiência anterior com as bibliotecas NumPy, pandas e Matplotlib é recomendada, mas não obrigatória

Para uma introdução rápida sobre esses requisitos, você pode usar os seguintes recursos:

* [`Introdução ao Python`](https://scipy-lectures.org/intro/language/python_language.html)
* [`Introdução ao NumPy`](https://sebastianraschka.com/blog/2020/numpy-intro.html)
* [`Introdução aos Pandas`](https://pandas.pydata.org/docs/user_guide/10min.html)
* [`Introdução ao Matplotlib`](https://sebastianraschka.com/blog/2020/numpy-intro.html#410-matplotlib)

# Objetivos e cronograma

Os objetivos do módulo são os seguintes:

* construir intuições sobre um conjunto de dados desconhecido;

* identificar e diferenciar características numéricas e categóricas;

* crie um pipeline preditivo avançado com o scikit-learn.

O tempo estimado para passar por este módulo é de cerca de 6 horas

# Wrap-up

Neste módulo, você aprendeu:

* para criar um modelo preditivo scikit-learn;

* sobre a API scikit-learn para treinar e testar um modelo preditivo;

* para processar dados numéricos, principalmente usando a Pipeline.

* para processar dados categóricos, principalmente usando um OneHotEncodere um OrdinalEncoder;

para tratar e processar tipos de dados mistos (ou seja, dados numéricos e categóricos), principalmente usando a ColumnTransformer.

# Ir além

Você pode consultar os seguintes exemplos de scikit-learn que estão relacionados aos conceitos abordados durante este módulo:

* [`Pipeline de aprendizado de máquina preditivo com tipos de dados mistos`](https://scikit-learn.org/stable/auto_examples/compose/plot_column_transformer_mixed_types.html#sphx-glr-auto-examples-compose-plot-column-transformer-mixed-types-py)
* [`Importância do dimensionamento de recursos`](https://scikit-learn.org/stable/auto_examples/preprocessing/plot_scaling_importance.html#sphx-glr-auto-examples-preprocessing-plot-scaling-importance-py)