¿Y si algo es verdadero cuando se cumplen varias condiciones? Por ejemplo, podríamos decir que un personaje es popular si aparece en una novela y una película. 

```prolog
personajePopular(Personaje) :-
   personajeDeNovela(Personaje),
   personajeDePelicula(Personaje).
```

Como ves, la `,` la usamos para decir que s tiene