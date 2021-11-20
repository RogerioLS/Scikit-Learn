# O que você vai aprender

Nos módulos anteriores, mostramos como criar, treinar, prever e até mesmo avaliar um modelo preditivo. No entanto, não alteramos os parâmetros dos modelos que podem ser dados ao criar uma instância. Por exemplo, para k-vizinhos mais próximos, inicialmente usamos este parâmetro padrão: `n_neighbors=5antes` de tentar outros parâmetros do modelo.

Esses parâmetros são chamados de **hiperparâmetros** : são parâmetros usados para controlar o processo de aprendizagem, por exemplo, o parâmetro `k` dos k-vizinhos mais próximos. Os hiperparâmetros são especificados pelo usuário, geralmente ajustados manualmente (ou por uma busca automática exaustiva) e não podem ser estimados a partir dos dados. Eles não devem ser confundidos com os outros parâmetros que são inferidos durante o processo de treinamento. Esses parâmetros definem o próprio modelo, por exemplo, coef_para os modelos lineares.

Neste módulo, mostraremos primeiro que os hiperparâmetros afetam o desempenho do modelo e que os valores padrão não são necessariamente a melhor opção. Posteriormente, mostraremos como definir hiperparâmetros no modelo scikit-learn. Finalmente, mostraremos estratégias que permitem pegar uma combinação de hiperparâmetros que maximiza o desempenho do modelo.

# Antes de começar

As habilidades técnicas necessárias para continuar este módulo são:

- habilidades adquiridas durante o “Pipeline de modelagem preditiva” com o uso básico do scikit-learn;

- habilidades relacionadas ao uso da estrutura de validação cruzada para avaliar um modelo.

# Objetivos e cronograma

Os objetivos do módulo são os seguintes:

- entender o que é um modelo de hiperparâmetro;

- entender como obter e definir o valor de um hiperparâmetro de um modelo scikit-learn;

- ser capaz de ajustar um pipeline completo de modelagem preditiva;

- compreender e visualizar a combinação de parâmetros que melhora o desempenho de um modelo.

O tempo estimado para passar por este módulo é de cerca de 3 horas.

# Wrap-up

* Os hiperparâmetros têm impacto no desempenho dos modelos e devem ser escolhidos com sabedoria;

* A busca pelos melhores hiperparâmetros pode ser automatizada com uma abordagem de pesquisa em grade ou uma abordagem de pesquisa aleatória;

* Uma pesquisa em grade é cara e não aumenta quando o número de hiperparâmetros a serem otimizados aumenta. Além disso, a combinação é amostrada apenas em uma grade regular.

* Uma pesquisa aleatória permite uma pesquisa com um orçamento fixo, mesmo com um número crescente de hiperparâmetros. Além disso, a combinação é amostrada em uma grade não regular.

# Ir além

Você pode consultar os seguintes exemplos de scikit-learn que estão relacionados aos conceitos abordados durante este módulo:

* [`Exemplo de grig-search`](https://scikit-learn.org/stable/auto_examples/model_selection/plot_grid_search_digits.html#sphx-glr-auto-examples-model-selection-plot-grid-search-digits-py)

* [`Exemplo de randomized-search`](https://scikit-learn.org/stable/auto_examples/model_selection/plot_randomized_search.html#sphx-glr-auto-examples-model-selection-plot-randomized-search-py)

* [`Exemplo de nested cross-validation`](https://scikit-learn.org/stable/auto_examples/model_selection/plot_nested_cross_validation_iris.html#sphx-glr-auto-examples-model-selection-plot-nested-cross-validation-iris-py)
