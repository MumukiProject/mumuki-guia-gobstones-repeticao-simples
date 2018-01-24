Enquanto corrigíamos os exercícios de um colega seu, nos encontramos com uma solução para LinhaVermelha4 que contém um erro, veja:

| Tabuleiro inicial | O que faz | O que esperávamos |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| <gs_board>
  GBB/1.0
    size 2 5
    head 0 0
  </gs_board> | 
  <gs_board>
  GBB/1.0
    size 2 5
    cell 0 4 Rojo 1
    cell 0 3 Rojo 1
    cell 0 2 Rojo 1
    cell 0 1 Rojo 1
    head 0 4
  </gs_board> |
  <gs_board>
  GBB/1.0
    size 2 5
    cell 0 0 Rojo 1
    cell 0 3 Rojo 1
    cell 0 2 Rojo 1
    cell 0 1 Rojo 1
    head 0 4
  </gs_board> |

<br>
Pode nos ajudar a corrigir? Deixamos o código no editor.
