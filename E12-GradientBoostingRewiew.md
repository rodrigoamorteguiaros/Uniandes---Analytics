# E12 - Gradient Boosting Review

Dentro de los algoritmos de “ensembling”, más usados en Machine Learning, están AdaBoost (Adaptive Boosting), Gradient Boosting, XGBoosting (Xtreme Gradient Boosting) y más recientemente LightGBM, creado por Microsoft.

Gradient Boosting, es una técnica que funciona bajo el principio de potenciación, donde el algoritmo crea arboles de decisión a partir de la información de anteriores iteraciones y los ensambla creando arboles de mayor peso.  Mientras que AdaBoost identifica errores calculando los pesos que se asignan a cada nodo, el algoritmo GradienBoost realiza el cálculo de gradientes con la función de perdida.  La función de perdida es una medidad de como el modelo ajusta los datos que está entrenando (si es un problema de regresión se usa el MSE y si es un problema de clasificación, se usa la perdida logarítmica).  El algoritmo de gradiente descendente es usado para minimizar la perdida cuando se adicionan árboles.

Por su parte XGBoost, conocido como Extreme Gradient Boosting, es una variante de Gradient Boosting la cual tiene como objetivo mejorar la velocidad de procesamiento y desempeño, mediante la creación de árboles en paralelo el concepto de “feature importances calculated from the training dataset”. 
