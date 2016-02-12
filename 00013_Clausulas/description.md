Lo que acabamos de definir es un predicado, empleando reglas:

```prolog
personajeDeFiccion(Alguien) :- 
    personajeDeNovela(Alguien).
personajeDeFiccion(Alguien) :-
    personajeDeSerie(Alguien).
personajeDeFiccion(Alguien) :-
    personajeDePelicula(Alguien).
```

Y se lee de la siguiente forma: 

   * _si alguien es un personaje de novela, entonces es personaje de ficción_
   * _si alguien es un personaje de serie, entonces es personaje de ficción_
   * _si alguien es un personaje de película, entonces es personaje de ficción_

Dicho de otra forma, nos está diciendo que un personaje de ficción es aquel individuo que cumpla alguna de las condiciones anteriores. 

