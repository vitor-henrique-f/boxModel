# Questões 

(Questão 1) O tamanho visual da caixa mudou? por quê?
 O tamanho VISUAL da caixa não mudou, pois o padding altera somente o espaçamento do conteúdo INTERNO da caixa.

(Questão 2) Agora qual é o tamanho total da caixa incluindo conteúdo, padding e borda?
 O tamanho TOTAL da caixa é: 325 px (widyth + padding + border + margin)

(Questão 3) Qual delas ultrapassou os 300px de largura? Por quê?
 A div sem o "box-sizing: border-box;" ultrapassa os 300 px de largura pois o "padding" e o "border" foram incluidos no tamanho
 de largura e altura da caixa.
 Já a caixa com o "box-sizing: border-box" exclui o "padding" e o "border" do tamanho largura e altura.
 