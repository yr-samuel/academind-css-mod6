### Usando o valor *fixed* para o position

* O elemento que estiver com esse valor na propriedade position se comportará como um elemento *inline-block*.

* O elemento é removido do fluxo normal, então os elementos irmãos se comportam como se o elemento com __position: fixed__  não existisse por ali.

* O contexto de posicionamento, vulgo a referência que as propriedades top, left, bottom e right terão será a viewport quando forem usadas.