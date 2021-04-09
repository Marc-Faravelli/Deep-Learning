# Deep-Learning

Enunciado

El objetivo de este Caso Práctico es simular cómo se haría un análisis completo de un problema para resolverlo con Deep Learning. Os pondréis en la piel de un Data Scientist, dedicado a analizar y crear modelos de Deep Learning para pasarlos a producción y ser desplegados en una aplicación.

Imaginemos que tenemos un dataset completo que queremos explotar, vuestra labor será coger este dataset de imágenes (CIFAR10) y realizar varios experimentos con distintas redes para descubrir cuál funciona mejor, y cuál elegís para pasar a producción. Por lo tanto, al final debéis justificar cuál de todos los modelos entrenados es el más óptimo para desplegar.

Cada experimento que tendréis que hacer estará bien definido, las redes que deberéis crear y entrenar serán proporcinadas, por lo que solamente tendréis que crear la red que se os indica en cada experimento con TensorFlow, y realizar el entrenamiento de la misma. Por cada experimento, deberéis sacar conclusiones de cómo de bueno o malo ha sido ese entrenamiento. Al final de todos los experimentos, deberéis generar una pequeña documentación donde justificar cuál de los modelos entrenados es el más óptimo para pasar a producción.

Parte obligatoria

Será obligatorio realizar cada uno de los experimentos que están definidos. En cada experimento está definida la red que se tiene que crear y la configuración con la que se tiene que entrenar, por lo que solamente tendréis que pasar esa definición a código con TensorFlow. Al finalizar cada experimento, tendréis que escribir un pequeño texto explicando cómo ha sido el entrenamiento y sacar conclusiones de los resultados.

Al final de todo el cuaderno, después de realizar cada uno de los experimentos, se deberá escribir una pequeña documentación justificando cuál de los modelos entrenados es el óptimo para ser desplegado en producción.

Es muy importante destacar que el objetivo de este Caso Práctico no es que obtengáis unos resultados muy buenos, de hecho, los resultados que obtendréis son los pre-definidos por las redes que tenéis que hacer. El objetivo principal es que veáis cómo se aborda un problema para ser resuelto con Deep Learning, donde partimos de un dataset y un objetivo, y vamos realizando diferentes experimentos hasta encontrar la solución más óptima que podemos llegar a desplegar en producción.

Además, otro objetivo es que entendáis qué estáis haciendo y los resultados que obtenéis con cada experimento: sin son buenos o malos, si hay sobreajuste en los datos de entrenamiento, si nuestra red no termina de aprender, si nuestra red se estanca en algún punto y ya no aprende más, etc.

Para tener una buena práctica en la realización de este Caso Práctico, se ofrecen estas recomendaciones:

Utiliza correctamente el sistema de celdas de jupyter. La libreta está realizada de tal forma que solo tendréis que completar las celdas que se indican, ya sea con código o con texto en markdown. Se recomienda rellenar solamente las celdas indicadas para que quede un informe limpio y fácil de seguir. Si fuera necesario incluir más celdas por cualquier motivo, se puede hacer, pero realizadlo con cuidado para no ensuciar demasiado la libreta.

Las redes que tendréis que crear en cada experimento son las vistas en clase, por lo que os podéis inspirar en los ejemplos de los tutoriales. Os recomiendo que no copiéis y peguéis el código tal cual, sino que lo escribáis por vuestra cuenta y entendáis lo que estáis haciendo en cada momento. Tomaros el tiempo que haga falta para entender cada paso.

Comprobad que todo se ejecuta correctamente antes de enviar vuestro trabajo. La mejor forma de enviarlo es exportando la libreta a pdf o html para enviarla en un formato más profesional.
