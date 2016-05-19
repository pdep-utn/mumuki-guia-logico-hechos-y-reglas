Antes de seguir avanzando, hay algo muuuuy interesante que se puede hacer en el paradigma Lógico a la hora de consultar nuestra base de conocimientos.

En el ejemplo anterior teníamos la información sobre en qué año ocurrió cada acontecimiento. ¿Qué clase de preguntas podríamos esperar que sea capaz de responder el motor a partir de esa información?

Hasta ahora sólo veníamos haciendo consultas que denominaremos *individuales*, en donde esperábamos que el motor nos dijera si era o no cierta una afirmación, por ejemplo si es cierto que Frodo es un personaje de ficción.

Sin embargo, el verdadero poder del paradigma es que trabaja con relaciones que, a diferencia de las funciones que son unidireccionales (a partir de una entrada perteneciente al dominio podemos obtener una salida perteneciente a la imagen) y deben cumplir con el principio de unicidad (sólo una imagen para cada valor del dominio), pueden ser consultadas de distintas formas.

Si te preguntás de qué estamos hablando, copiá las siguientes consultas en la consola y fijate qué te responde.

```prolog
acontecimiento(caidaConstantinopla, Cuando).
acontecimiento(Acontecimiento, 1986).
acontecimiento(Acontecimiento, Cuando).
```

A estas consultas que contienen al menos una variable las llamaremos *existenciales*.