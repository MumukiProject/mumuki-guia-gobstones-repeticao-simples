Sempre que tiver problemas como este poderá solucionar da mesma maneira: **processando o último caso separadamente**.

Outra variante não tão comum, e talvez mais difícil de construir também , é a de processar o **primeiro** caso isoladamente:

``` gobstones
procedure LinhaPreta4Leste() {
  Colocar(Preto)
  repeat(3) {
    Mover(Leste)
    Colocar(Preto)
  }
}
```

Por convenção, vamos preferir a forma que processa de maneira diferente  o último caso, embora com frequência ambas sejam equivalentes (isto é, produzem o mesmo resultado).
 
