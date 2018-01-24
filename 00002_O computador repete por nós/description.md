Como adiantamos para você no exercício anterior, na linguagem Gobstones existe uma forma de dizer "quero que **estes comandos** se **repitam esta quantidade de vezes**".

Então quando é necessário repetir um comando (como `Mover`, `Colocar`, `DesenharLinhaPreta`, etc.) um certo número de vezes, em lugar de copiar e colar como vínhamos fazendo até agora, podemos utilizar a sentença `repeat`.

Sabendo disso, assim  é como ficaria `MoverOeste10` usando `repeat`:

``` gobstones
procedure MoverOeste10() {
  repeat(10) {
    Mover(Oeste)
  }
}

```

> Prove você mesmo, escreva este código no editor e veja se funciona!
