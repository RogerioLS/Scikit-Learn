# O que você vai aprender

No módulo anterior, apresentamos a estrutura geral de validação cruzada e a usamos para avaliar o desempenho dos modelos. No entanto, é importante ter em mente que alguns elementos na validação cruzada precisam ser decididos dependendo da natureza do problema: (i) a estratégia de validação cruzada e (ii) as métricas de avaliação. Além disso, é sempre bom comparar o desempenho dos modelos com algum modelo de linha de base.

Neste módulo, apresentamos os dois aspectos e fornecemos insights sobre quando usar uma estratégia de validação cruzada específica e uma métrica. Além disso, também daremos alguns insights sobre como comparar um modelo com alguma linha de base.

# Antes de começar

As habilidades técnicas necessárias para continuar este módulo são:

* habilidades adquiridas durante o módulo “The Predictive Modeling Pipeline” com o uso básico de scikit-learn;

* habilidades adquiridas durante o módulo “Selecionando o melhor modelo”, principalmente em torno do conceito de underfit / overfit e o uso de validação cruzada no scikit-learn.

# Objetivos e cronograma

Os objetivos do módulo são os seguintes:

* compreender a necessidade de usar uma estratégia de validação cruzada apropriada dependendo dos dados;

* obtenha as intuições por trás da comparação de um modelo com alguns modelos básicos que podem ser usados ​​como linha de base;

* compreender os princípios por trás do uso de validação cruzada aninhada quando o modelo precisa ser avaliado, bem como otimizado;

* compreender as diferenças entre regressão e métricas de classificação;

* entender as diferenças entre as métricas.

# Wrap-up

Neste caderno, apresentamos o framework usado em aprendizado de máquina para avaliar o desempenho de um modelo preditivo: a validação cruzada.

Além disso, apresentamos várias estratégias de divisão que podem ser usadas na estrutura geral de validação cruzada. Essas estratégias devem ser usadas com sabedoria ao encontrar alguns padrões ou tipos de dados específicos.

Finalmente, mostramos como realizar validação cruzada aninhada para selecionar um modelo ideal e avaliar seu desempenho de generalização.

# Ir adiante

Você pode consultar os seguintes exemplos de scikit-learn, que estão relacionados aos conceitos abordados neste módulo:

* [`Comparison of cross-validation strategies`](https://scikit-learn.org/stable/auto_examples/model_selection/plot_cv_indices.html#sphx-glr-auto-examples-model-selection-plot-cv-indices-py)