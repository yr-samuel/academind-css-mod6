### Introdução ao posicionamento sticky

* Quando aplicamos *position: sticky;* sem fazer nenhum tipo de deslocamento, esse elemento continua no fluxo normal do documento.
* Quando aplicamos um deslocamento de por exemplo uns 50px na propriedade __top__ (top: 50px), estamos dizendo que quando o bloco que tem o scroll chegar a 50px do elemento com position sticky, esse elemento ficará fixado na tela dentro da área visível do seu containing block*, e quando essa containing block não estiver mais vísivel o elemento com sticky rolará junto e desaparecerá.

### Sobre containing block

* Basicamente a containing block é uma certa área do elemento ancestral ao elemento que tem algum position definido, no caso dos position *sticky*, *static* e *relative*, o containg block é o espaço que vai até o limite do bloco de conteúdo, vulgo content area. 

* No caso do elemento ser um position *absolute*, o containing block é o espaço que vai até o limite do padding, isso se algum elemento ancestral tiver um position diferente de *static*.

* E por fim, a containing block dos elementos com positon *fixed* é a viewport.

Há mais algumas regrinhas interessantes: https://developer.mozilla.org/en-US/docs/Web/CSS/Containing_block#identifying_the_containing_block