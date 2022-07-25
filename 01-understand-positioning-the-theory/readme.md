### Entendendo o posicionamento - A teoria.

* Por padrão, todos os elementos recebem uma propriedade *position* com o valor *static* fazendo com que o elemento siga o fluxo normal da página.

* Os valores possíveis para o position são: *static, relative, absolute, fixed e sticky*.

* Porém, só setando um position só estamos dizeno que o elemento pode ser movido, e quando definimos um position (diferente de *static*) é "meio" que liberado quatro novas propriedades do CSS para esse elemento, que são: *top, right, bottom e left*, que nos permite de fato mudar a posição do elemento.

* Por padrão (sem definirmos nenhum valor para essas 4 propriedades) elas são referentes a posição do elemento no fluxo normal, mas quando elas são alteradas a referência da posição do elemento muda de acordo com o que foi definido no position (a referência está relacionada ao contexto de posicionamento).