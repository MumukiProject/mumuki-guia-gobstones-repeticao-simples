Viu como é importante definir bem quais comandos devem se repetir e quais não devem?

É muito comum, a princípio, esquecer de colocar as chaves ou pensar que não são importantes. Mas tenha muito cuidado: colocar as chaves em um lugar errado pode mudar completamente o que  o seu programa faz. Veja que diferente seria o resultado se tivesse inserido o Mover(Leste) dentro do repeat:

``` gobstones
procedure Colocar3AoNordeste() {
  Mover(Norte)
  
  repeat(3) {
    Mover(Leste)
    Colocar(Preto)
  }
}

```

<gs-board>
 GBB/1.0
    size 4 4
    cell 1 1 Negro 1
    cell 2 1 Negro 1
    cell 3 1 Negro 1
    head 3 1
</gs-board>
