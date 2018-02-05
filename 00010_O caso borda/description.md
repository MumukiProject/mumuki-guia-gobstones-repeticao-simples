Muitas vezes quando usamos um `repeat` nos deparamos com que o último caso é levemente distinto aos anteriores, situação que chamamos de **caso borda**. Mas é melhor que vejamos um exemplo.

O procedimento `LinhaPreta4Leste` que te apresentamos desenha uma linha preta em direção ao Leste deixando a garra **fora da linha**, uma célula em direção ao Leste.

``` gobstones
procedure LinhaPreta4Leste() {
  repeat(4) {
    Colocar(Preto)
    Mover(Leste)
  }
}
```

Se agora queremos fazer com que a garra  fique na última célula da linha, temos duas opções:

* **Mover a garra em direção ao Oeste depois de desenhar a linha.** Um truque meio sem graça, porque para funcionar necessita que exista pelo menos 5 espaços em direção ao Leste partindo da posição inicial, quando nossa linha ocupará apenas 4.
* **Tratar o último caso de maneira especial.** Esta opção é mais interessante e mais fiel ao que queremos fazer: a última vez não queremos que a garra se mova, basta simplesmente que  coloque a pedra preta.

> Levando em conta a última opção, escreva uma nova versão de `LinhaPreta4Leste` que deixe a garra na última célula da linha.
