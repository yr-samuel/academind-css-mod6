### Entendendo a propriedade z-index

* Por padrão, cada elemento em qualquer site tem o valor *auto* aplicado a propriedade __z-index__, e este valor é equivalente a 0 (zero).

* A propriedade *z-index* só fica habilitada para ser alterada, quando o elemento tem position diferente de static e também em flex-items.

* Para os elementos que estão com o z-index com o valor *auto* (equivalente a 0) a decisão de ficar por cima ou por baixo é baseada na posição deste elemento no DOM em comparação com os outros elementos que contém um position definido, logo quem está por primeiro vai ficando por baixo e quem está adiante vai ficando por cima. Para elementos que contém um z-index definido (vulgo diferente de auto ou 0), o que vale é o seu valor, quanto menor for mais ficará por de baixo dos outros elementos e quanto maior for ficará por cima dos outros elementos (e esses elementos com z-index definido, levam em conta os elementos que estão com z-index auto que é equivalente a 0, logo se esse elemento com z-index definido for menor que 0 ficará por baixo, se for maior que 0 ficará por cima).

