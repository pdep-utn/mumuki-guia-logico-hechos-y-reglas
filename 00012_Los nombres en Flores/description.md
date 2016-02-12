En el barrio de Flores hay muchas formas de llamar a las personas y otros seres
  
 1. A todos se los puede llamar por su nombre
 2. A los tahúres, se los puede llamar además por su apodo (todos los tahúres tienen un apodo)
 3. Y al diablo le dicen belcebú o asmodeo

Ejemplo: 

```prolog
? leDicen(bernardo, ruso).
yes. % por (2)
? leDicen(jorge, jorge).
yes. % por (1)
? leDicen(diablo, belcebu).
yes. % por (3)
? leDicen(elDiablo, elDiablo).
yes. % por (1)
```

> Escribí el predicado `leDicen/2`