# O que você vai aprender

Este módulo oferece uma introdução intuitiva aos conceitos fundamentais de overfitting e underfitting no aprendizado de máquina.

Os modelos de aprendizado de máquina nunca podem fazer previsões perfeitas: o erro de teste nunca é exatamente zero. Essa falha vem de uma troca fundamental entre a flexibilidade de modelagem e o tamanho limitado do conjunto de dados de treinamento .

A primeira apresentação definirá esses problemas e caracterizará como e por que eles surgem.

Em seguida, apresentaremos uma metodologia para quantificar esses problemas, contrastando o erro do trem com o erro de teste para várias escolhas da família do modelo, parâmetros do modelo. Mais importante, enfatizaremos o impacto do tamanho do conjunto de treinamento sobre essa compensação .

Finalmente, relacionaremos o overfitting e o underfitting aos conceitos de variância estatística e viés.

# Antes de começar

As habilidades técnicas necessárias para continuar este módulo são:

habilidades adquiridas durante o módulo “The Predictive Modeling Pipeline” com o uso básico do scikit-learn.

Objetivos e cronograma
Os objetivos do módulo são os seguintes:

compreender o conceito de overfitting e underfitting;

compreender o conceito de generalização;

compreender a estrutura geral de validação cruzada usada para avaliar um modelo.

O tempo estimado para passar por este módulo é de cerca de 3 horas.



* O overfitting é causado pelo tamanho limitado do conjunto de treinamento , pelo ruído nos dados e pela alta flexibilidade dos modelos comuns de aprendizado de máquina.

* O subajuste ocorre quando as funções de previsão aprendidas sofrem de erros sistemáticos . Isso pode ser causado por uma escolha de família de modelo e parâmetros, o que leva a uma falta de flexibilidade para capturar a estrutura repetível do verdadeiro processo de geração de dados.

* Para um conjunto de treinamento fixo, o objetivo é minimizar o erro de teste ajustando a família do modelo e seus parâmetros para encontrar a melhor compensação entre overfitting para underfitting .

* Para uma determinada escolha de família de modelo e parâmetros, aumentar o tamanho do conjunto de treinamento diminuirá o overfitting, mas também pode causar um aumento de underfitting.

* O erro de teste de um modelo que não é nem overfitting nem underfitting pode ainda ser alto se as variações da variável de destino não puderem ser totalmente determinadas pelos recursos de entrada. Esse erro irredutível é causado pelo que às vezes chamamos de ruído de rótulo. Na prática, isso geralmente acontece quando não temos acesso a recursos importantes por um motivo ou outro.


# Ir além


É possível dar um tratamento matemático preciso do viés e da variância de um modelo de regressão. O artigo da Wikipedia sobre compensação de [`Bias-variance tradeoff`](https://en.wikipedia.org/wiki/Bias%E2%80%93variance_tradeoff) explica como o erro de teste quadrado pode ser decomposto como a soma da polarização quadrada, a variância e o erro irredutível para um determinado erro de regressão.

Os próximos capítulos sobre modelos lineares, árvores de decisão e conjuntos darão exemplos concretos de como diagnosticar e lidar com overfitting e underfitting.

Você pode consultar os seguintes exemplos de scikit-learn que estão relacionados aos conceitos abordados durante este módulo:

* [`Ilustração de conceitos de underfitting e overfitting`](https://scikit-learn.org/stable/auto_examples/model_selection/plot_underfitting_overfitting.html#sphx-glr-auto-examples-model-selection-plot-underfitting-overfitting-py)
* [`Difference between train and test scores`](https://scikit-learn.org/stable/auto_examples/model_selection/plot_train_error_vs_test_error.html#sphx-glr-auto-examples-model-selection-plot-train-error-vs-test-error-py)
* [`Example of a validation curve`](https://scikit-learn.org/stable/auto_examples/model_selection/plot_validation_curve.html#sphx-glr-auto-examples-model-selection-plot-validation-curve-py)
