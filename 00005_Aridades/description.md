Hasta ahora todo lo que venimos afirmando del mundo era información simple: que `drHouse` es un personaje de ficción, que el `ganges` es un río, etc. Nos dicen **propiedades** de las cosas. 

A nivel Prolog, estos hechos tienen una característica distintiva: tienen exactamente un argumento. Por ejemplo, acá tenemos otro hecho de un sólo argumento

```prolog
politico(marianoMoreno).
politico(manuelBelgrano).
politico(juanJoseCastelli).
%              ^
%              |
%              +-- argumento
```

Sin embargo, podemos tener hechos de más de un argumento: se los conoce como **relaciones**. 

Ejemplo: 

```prolog
duenio(gardfield, john).
duenio(oddie, john).
duenio(nermal, tioDeJohn).
```

> Probá en la consola este predicado. 
