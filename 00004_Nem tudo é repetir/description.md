Os exemplos que você fez nos exercícios anteriores se solucionavam simplesmente repetindo coisas. Mas nem tudo é repetir, também podemos colocar comandos tanto **antes** como **depois** do `repeat`, como vínhamos fazendo até agora.

Por exemplo, este é um programa que se move para o Sul e **em seguida** coloca 4 pedras vermelhas:

``` gobstones
program {
  Mover(Sul)

  repeat(4) {
    Colocar(Vermelho)
  }
}

```


Observe que o `Mover(Sul)` colocamos **antes** do `repeat`, e portanto se executa apenas uma vez.

> Sabendo disso, escreva `Colocar3AoNordeste()`, que coloque 3 pedras pretas na primeira célula ao Nordeste da garra. 