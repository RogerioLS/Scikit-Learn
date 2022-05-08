# O que você vai aprender 

Neste módulo, entraremos em detalhes sobre os modelos que utilizam parametrização linear. Veremos como usar essa família de modelos para problemas de classificação e regressão. Além disso, vamos explicar como combater o sobreajuste usando a regularização.
Finalmente, mostraremos como modelos lineares podem ser usados com dados que apresentam não linearidade.

# Antes de começar

As habilidades técnicas necessárias para continuar este módulo são:

* habilidades adquiridas durante o módulo “The Predictive Modeling Pipeline” com o uso básico de scikit-learn;

* habilidades adquiridas durante o módulo “Selecting The Best Model”, principalmente em torno do conceito de underfit / overfit e o uso de validação cruzada no scikit-learn.

# Objetivos e cronograma

Neste módulo, seus objetivos são:

* compreender a parametrização dos modelos lineares;

* compreender a implicação dos modelos lineares na regressão e na classificação;

* obter intuições de modelos lineares aplicados em conjuntos de dados de dimensões superiores;

* compreender o efeito da regularização e como configurá-lo;

* entenda como os modelos lineares podem ser usados mesmo com dados que mostram uma relação não linear com o alvo a ser previsto.

O tempo estimado para passar por este módulo é de cerca de 6 horas.

# Wrap-up

Neste módulo, vimos que:

* as previsões de um modelo linear dependem de uma soma ponderada dos valores dos recursos de entrada adicionados a um parâmetro de interceptação;

* ajustar um modelo linear consiste em ajustar tanto os coeficientes de peso quanto a interceptação para minimizar os erros de predição no conjunto de treinamento;

* para treinar modelos lineares com sucesso, muitas vezes é necessário dimensionar os recursos de entrada aproximadamente para a mesma faixa dinâmica;

* a regularização pode ser usada para reduzir o sobreajuste: os coeficientes de peso são restringidos para permanecer pequenos durante o ajuste;

* o hiperparâmetro de regularização precisa ser ajustado por validação cruzada para cada novo problema de aprendizado de máquina e conjunto de dados;

* modelos lineares podem ser usados em problemas em que a variável de destino não está linearmente relacionada aos recursos de entrada, mas isso requer trabalho de engenharia de recurso extra para transformar os dados a fim de evitar o ajuste insuficiente.

# To go further

Você pode consultar os seguintes exemplos de scikit-learn que estão relacionados aos conceitos abordados durante este módulo:

* [`Exemplo de regressão linear`](https://scikit-learn.org/stable/auto_examples/linear_model/plot_ols.html#sphx-glr-auto-examples-linear-model-plot-ols-py)

* [`Comparação entre uma regressão linear e um regressor de crista`](https://scikit-learn.org/stable/auto_examples/linear_model/plot_ols_ridge_variance.html#sphx-glr-auto-examples-linear-model-plot-ols-ridge-variance-py)