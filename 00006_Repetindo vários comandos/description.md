Até o momento os exemplos que vimos só repetiam um comando, mas como mencionamos no começo é possível repetir qualquer **sequência de comandos** – em  resumo o que se repete é um **bloco** e, como já sabíamos, em um bloco podem existir tantos comandos como quisermos.

Vejamos o código de `DesenharLinhaPreta6` que poderíamos ter feito sem usar `repeat`, com alguns espaços em branco para nos ajudar a  reconhecer a sequência que se repete:

``` gobstones
procedure DesenharLinhaPreta6() {
  Colocar(Preto)
  Mover(Leste)

  Colocar(Preto)
  Mover(Leste)

  Colocar(Preto)
  Mover(Leste)

  Colocar(Preto)
  Mover(Leste)

  Colocar(Preto)
  Mover(Leste)  

  Colocar(Preto)
  Mover(Leste)  
}

```


Notou o que se repete e quantas vezes? Bom, isso é o que você deve colocar no `repeat`.

> Escreva uma versão melhor que supere o de `DesenharLinhaPreta6`, dessa vez usando `repeat`.
 
