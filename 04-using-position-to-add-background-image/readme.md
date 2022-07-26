### Usando position para adicionar uma imagem como background.

* Primeiro de tudo, adicionamos a imagem para o projeto.

* Em seguida, adicionamos uma div, para que pudessemos mostrar a imagem.

* Já no CSS, selecionamos a div através da classe *.background*, definimos seu background passando a url da imagem que adicionamos no projeto, após isso colocamos __position: fixed__.

* De praxe, definimos o *top* e *left* como 0, e como sabemos o fixed se referencia a viewport, e a viewport tem um tamanho especificado de height, logo conseguimos usar 100% tanto para width quanto para height, assim fazendo com que a imagem preenchesse toda a página.

* Porém, contudo, entretanto, todavia, a imagem ficou por cima de tudo (cards), e para resolver isso veremos sobre a propriedade __z-index__ na próxima aula.